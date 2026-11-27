# Certificate eligibility — system implementation specification

**Version:** 1.0 · **Status:** Proposed technical specification, not deployed. Implement only approved policy versions and assessment schedules.

## 1. Required data and rules

Maintain curriculum version, course/pathway, enrolment, required topic/section/activity/assessment/practical IDs, approved electives and substitutions, finalised marks and weighting, moderation, integrity and safety clearance, research grade, policy version, approval history, award record and verification status. Derive requirements server-side from assigned curriculum and approved assessment plan; never trust client checkboxes or self-reported completion for issuance. Distinguish missing, failed, passed, exempt/not-applicable and pending; an unapproved exemption does not count.

## 2. Eligibility contract

Return one of ELIGIBLE, INELIGIBLE, HOLD_PENDING_REVIEW with reason codes and rule versions. Missing policy approval, missing authorised grade or unresolved moderation/integrity => hold (no issue); known missing required work or failed threshold => ineligible. All gates must pass; report all blockers. If both hold and ineligible exist, record both and never issue. Validate score bounds 0–100, reject malformed data, use exact decimal or rational arithmetic and compare before display rounding.

MCC: assigned required items complete, applicable assessment thresholds and final module result pass, verified competencies and clearance. LCC: all required module gates within level plus approved level average and research threshold where specified. CCC: all 20 current Applied Physics required module gates and electives for pathway plus net average >=60 and PHY307 >=70. PHY304 excluded unless future approved schedule changes required scope. Do not require unselected electives or prior LCC possession. Never issue based on an unresolved proposed threshold/average rule.

## 3. Issuance lifecycle

Requested → evaluated → held/ineligible or eligible → authorised → issued → optionally revoked/superseded. Evaluate again at authorisation/issuance against immutable versioned result snapshot. Require authorised reviewer and issuer permission. Atomic transaction/idempotency key (learner, award type, scope/pathway, curriculum version, award version); concurrent retries must not create duplicates. Store reasoned authorisation and immutable certificate data; regenerate only via controlled reissue. Verify token maps to current validity status. Keep client UI read-only for marks/eligibility; assessor and moderator grade transitions audited. Private records require least privilege. Do not commit secrets or real learner data.

## 4. Acceptance tests (to implement, not executed)

| ID | Scenario | Expected |
|---|---|---|
| AW-01 | Exact MCC 55% boundary, all gates pass | Eligible under adopted interpretation |
| AW-02 | Required graded assessment 54.99%, overall 85% | Ineligible under adopted per-item rule |
| AW-03 | Required lab or section incomplete | Ineligible |
| AW-04 | Wholly unselected elective section incomplete | Not a blocker |
| AW-05 | Approved selected elective incomplete | Ineligible |
| AW-06 | Missing official mark / moderation pending | Hold |
| AW-07 | Open integrity review | Hold |
| AW-08 | LCC level 60%, gates clear | Eligible only after proposed LCC rule adopted |
| AW-09 | LCC rule not adopted | Hold |
| AW-10 | CCC average 60%, project 70%, all gates clear | Eligible |
| AW-11 | CCC average 59.99% | Ineligible; no display rounding uplift |
| AW-12 | CCC project 69.99% despite high average | Ineligible |
| AW-13 | PHY304 omitted / optional high mark | No blocker / no change to required average |
| AW-14 | Duplicate module or missing compulsory module | Reject duplicate counting / ineligible |
| AW-15 | Course meets own gates but no LCC issued | Eligible, if no adopted rule requires LCC |
| AW-16 | Unapproved substitution or policy version | Hold or ineligible, never issue |
| AW-17 | Concurrent issuance retries | One award record |
| AW-18 | Unauthorised grade/issuance attempt | Deny and audit |
| AW-19 | Revoked credential token | Reports revoked, no private reason |
| AW-20 | New curriculum version after enrolment | Original assigned rules until authorised migration |
| AW-21 | Invalid, out-of-range or nonnumeric grade | Reject and hold |
| AW-22 | Missing rubric/weights or averaging approval | Hold |
| AW-23 | Project module passes MCC but research below 70% | CCC ineligible; MCC evaluated independently |
| AW-24 | Private verification record accessed without permission | Deny and audit |
| AW-25 | Reissued corrected credential | Old award superseded; new valid record linked |

## 5. Delivery gate

Implement server-side evaluator, test fixtures, access controls, authorised grade workflow, audit events, verification registry and signing process. Require approved policy, course-specific assessment plan, security/privacy review, moderation, accessibility review and automated boundary tests before production issuance. This repository records requirements only; changes to the website/LMS require a separate PR.
