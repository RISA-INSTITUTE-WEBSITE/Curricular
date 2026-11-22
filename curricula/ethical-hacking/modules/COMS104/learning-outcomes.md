# COMS104 — Gaining Access to Computers/Systems

**Institution:** RISA Institution of Applied Sciences  
**Discipline:** Ethical Hacking (COMS)  
**Module code:** COMS104  
**Module title:** Gaining Access to Computers/Systems  
**Level:** Introductory / progressive sequence (formal level to be decided)  
**Document:** Proposed learning outcomes, syllabus and assessment activities  
**Status:** Draft — pending academic, technical, legal and safety review  
**Version:** 0.2 (practical learning-outcomes revision)  
**Date:** 22 November 2026

## 1. Module purpose

Examine how access-control failures and host misconfigurations can produce unauthorized privilege, while teaching students to validate weaknesses solely in deliberately vulnerable, instructor-controlled systems and to harden those systems.

## 2. Proposed entry preparation

COMS101–COMS103 recommended; students must pass the authorization, isolation and recovery readiness checks.

*Recommendations only; formal prerequisites and equivalency pathways require academic approval.*

## 3. Practical, assessable learning outcomes

Upon successful completion of COMS104, a learner should be able to **independently demonstrate** the following in an expressly authorized, resettable environment. Each outcome has a tangible assessment artifact.

| Code | Practical learning outcome | Minimum observable evidence |
| --- | --- | --- |
| **LO1** | Provision and reset an isolated, instructor-controlled host fixture with synthetic identities, documented authorization and recovery checks. | Verified scope, fixture inventory and restoration record |
| **LO2** | Audit local host accounts, permissions, patch state and security configuration against an instructor-supplied baseline. | Completed access-control and configuration checklist |
| **LO3** | Validate one predefined access-control defect using only permitted synthetic roles and a bounded proof of behavior, then stop. | Minimal sanitized proof, target identifier and scope check |
| **LO4** | Correlate instructor-provided host audit events to reconstruct a simulated unexpected-access incident. | Evidence-based audit timeline and explanation |
| **LO5** | Implement an approved least-privilege, patching or security-configuration correction in a disposable host. | Documented defensive change |
| **LO6** | Execute authorized positive and negative access tests to establish whether the correction restored the intended security boundary. | Before/after access-test matrix |
| **LO7** | Run a repeatable host-hardening and recovery checklist, recording residual issues and confirming the lab is restored. | Hardening checklist and recovery confirmation |
| **LO8** | Write a technical host-security finding covering the observed condition, evidence, business impact, correction, retest and limitations. | Scoped host assessment report |

**Outcome standard:** Assess what the learner can perform, verify and justify—not only what they can define or recall. Passing a setup-readiness check is necessary before lab access but is not proof of module competence.

## 4. Teaching-section alignment

| Section | Practical teaching emphasis | Outcomes |
| --- | --- | --- |
| **A — Host Lab and Authorization** | Synthetic identities, isolation, safe testing and restoration | LO1 |
| **B — Host Security Review** | Authentication, permissions, patch state and configuration baseline | LO2 |
| **C — Supervised Access-Control Validation** | Minimal, preapproved testing of seeded faults and audit-event interpretation | LO3, LO4 |
| **D — Repair and Verification** | Least privilege, configuration repair, before/after access tests and hardening | LO5, LO6, LO7 |
| **E — Technical Reporting** | Evidence, risk, remediation, limitations and recovery | LO7, LO8 |

The learning outcomes, teaching sections, laboratory activities and assessment evidence are **proposals** developed from the module topics; they are not a verbatim transcription of the handwritten source.

## 5. Proposed practical learning and assessment

Practical activities should involve hands-on demonstration and repeatable observation, accompanied by brief explanations of the findings.

| Activity | Student task and required evidence | Outcomes |
| --- | --- | --- |
| **Lab 1 — Isolated host baseline** | Verify the approved fixture and audit synthetic identity and permission settings | LO1, LO2 |
| **Lab 2 — Bounded validation** | Test an instructor-seeded authorization failure using only safe dummy identities; review audit traces | LO3, LO4 |
| **Lab 3 — Restore security** | Apply an approved access-control repair and run positive/negative regression cases | LO5, LO6 |
| **Lab 4 — Harden and document** | Complete host-hardening checks, restore the lab and report residual risk | LO7, LO8 |

**Integrated practical exit task (proposal):** Investigate a deliberately misconfigured training host using synthetic credentials, demonstrate one bounded access-control issue, implement an approved fix, verify both permitted and denied access, and document recovery.

**Lab gate:** Written authorization, a limited target list, safe readiness check, instructor-tested fixtures, a recovery/reset path, redacted evidence and a marking rubric are mandatory. These lab briefs remain **unpiloted proposals** until the learning environment, student instructions, reference results and marking instruments are developed and verified.

## 6. Teaching and safety boundaries

This module does not authorize taking control of real systems, bypassing third-party authentication, covert persistence, lateral movement, credential theft or evading monitoring. Learners must use disposable lab identities and fixtures, and stop once the bounded authorized learning objective is demonstrated.

Learners must seek written authorization **before** any security test, preserve privacy, refrain from testing systems outside scope and follow the instructor's stop-and-escalate procedure. Any unsafe or unapproved activity is outside this curriculum.

## 7. Practical-first assessment evidence (proposed)

- **Setup and authorization — prerequisite gate (Pass/Retry):** Independently verify that the student is operating within an approved isolated fixture and can restore the environment. This readiness check is **not** a graded learning outcome by itself.
- **Hands-on laboratory portfolio:** Assessor checks actual configuration, captured safe observations, negative/positive test cases, commands or code, and explanations linked to the LO evidence column above.
- **Integrated practical exit task:** In an unseen but equivalent instructor-owned fixture, independently complete the bounded task, investigate a seeded issue, demonstrate a defensible improvement, retest and document limitations.
- **Short knowledge checkpoint and technical explanation:** Explain why results matter and justify safety, controls, analysis and corrective action; a written definition alone cannot substitute for verified lab competence.

**Practical orientation:** A **provisional** teaching-time target is 70% supervised practical work, 20% theory/demonstration and 10% review/reporting. This is **not** an approved mark distribution, credit allocation or pass standard. Assessment weighting and moderation must be academically approved.

**Unresolved decisions:** notional/contact hours, formal academic level, credit value, prerequisite enforcement, mark weighting, pass criteria, appeals/moderation, exact lab toolchain, learner hardware, academic approval, and final safety-gate policy.

## 8. Provenance and review status

**Source:** Handwritten *Ethical Hacking (COMS)* outline supplied 22 November 2026, giving module COMS104 and its topic. Detailed outcomes were refactored on 22 November 2026 to emphasize independently assessable practical competence; all outcomes, sections, laboratories, assessment evidence and safety controls remain proposed curriculum developments and must not be portrayed as already approved or delivered.

---

*RISA Institution of Applied Sciences — Curriculum Development Draft*
