# COMS104 — Gaining Access to Computers/Systems

**Institution:** RISA Institution of Applied Sciences  
**Discipline:** Ethical Hacking (COMS)  
**Module code:** COMS104  
**Module title:** Gaining Access to Computers/Systems  
**Level:** Introductory / progressive sequence (formal level to be decided)  
**Document:** Proposed learning outcomes, syllabus and assessment activities  
**Status:** Draft — pending academic, technical, legal and safety review  
**Version:** 0.1  
**Date:** 22 November 2026

## 1. Module purpose

Examine how access-control failures and host misconfigurations can produce unauthorized privilege, while teaching students to validate weaknesses solely in deliberately vulnerable, instructor-controlled systems and to harden those systems.

## 2. Proposed entry preparation

COMS101–COMS103 recommended; students must pass the authorization, isolation and recovery readiness checks.

*Recommendations only; formal prerequisites and equivalency pathways require academic approval.*

## 3. Proposed measurable learning outcomes

Upon successful completion, learners should be able to:

| Code | Learning outcome |
| --- | --- |
| **LO1** | Distinguish authentication, authorization, sessions, privileges and trust boundaries on computer systems. |
| **LO2** | Explain common host-entry conditions including unpatched services, weak policies and excessive permissions. |
| **LO3** | Assess a supplied host configuration against a security checklist and documented test scope. |
| **LO4** | Demonstrate, in a deliberately vulnerable disposable lab, whether a predesignated access-control weakness exists without collecting real credentials. |
| **LO5** | Identify indicators of compromised access or unexpected privilege from provided system logs and traces. |
| **LO6** | Apply least-privilege or configuration remediation to an approved training system. |
| **LO7** | Retest an isolated fixture to demonstrate whether the vulnerability was addressed. |
| **LO8** | Write a scoped technical finding that includes impact, evidence, affected fixture, remediation, limitations and recovery confirmation. |

## 4. Teaching-section alignment

| Section | Core content | Outcomes |
| --- | --- | --- |
| **A — Identity and Trust** | Authentication, authorization, privilege boundaries and access models | LO1 |
| **B — Sources of Host Exposure** | Misconfiguration, patch hygiene, weak access-control policies and asset inventory | LO2–LO3 |
| **C — Controlled Validation** | Preconfigured vulnerable accounts, approved demonstration cases, scope checks and recovery | LO3–LO4 |
| **D — Detection and Mitigation** | Host audit logs, least privilege, defensive changes and hardening | LO5–LO7 |
| **E — Responsible Evidence** | Reproducibility, finding reports, retesting and secure disposal of test data | LO7–LO8 |

The teaching sections, learning outcomes and sequencing are **new syllabus proposals**, not a verbatim transcription of the handwritten list.

## 5. Proposed practical learning and assessment

| Activity | Learning task / evidence | Outcomes |
| --- | --- | --- |
| **Access-control review** | Review a deliberately misconfigured local fixture and document expected versus actual permissions | LO1–LO3 |
| **Supervised validation** | Verify only a preapproved synthetic-account flaw in a resettable host image; stop at the bounded proof point | LO3–LO4 |
| **Detection and repair** | Interpret synthetic audit logs, correct the policy and show the retest result | LO5–LO8 |

Each lab requires a written scope and authorized target list, readiness verification, instructor-tested fixtures, a recovery/reset procedure, sanitized evidence, and a rubric. Activities are proposals until lab scripts, guides, model results and marking criteria are reviewed and piloted.

## 6. Teaching and safety boundaries

This module does not authorize taking control of real systems, bypassing third-party authentication, covert persistence, lateral movement, credential theft or evading monitoring. Learners must use disposable lab identities and fixtures, and stop once the bounded authorized learning objective is demonstrated.

Learners must seek written authorization **before** any security test, preserve privacy, refrain from testing systems outside scope and follow the instructor's stop-and-escalate procedure. Any unsafe or unapproved activity is outside this curriculum.

## 7. Proposed assessment evidence

- **Knowledge checkpoint:** Explain key concepts and ethical scope constraints for the module.
- **Setup readiness (Pass/Retry):** Verify isolation, target authorization, basic tools and rollback method before practical tasks.
- **Practical task(s):** Submit independently explainable, sanitized outputs, observations and remediation/retest evidence.
- **Final module assessment:** Analyze a permitted case, justify findings and communicate security improvements with limitations.

**Unresolved decisions:** contact/notional hours, formal academic level, credit value, prerequisite enforcement, assessment weighting, pass criteria, appeals/moderation, exact lab toolchain, equipment needs and academic approval.

## 8. Provenance and review status

**Source:** Handwritten *Ethical Hacking (COMS)* outline supplied 22 November 2026, giving module COMS104 and its topic. All detailed learning outcomes, sections, laboratories, assessment evidence and safety controls above are proposed curriculum developments and must not be portrayed as already approved or delivered.

---

*RISA Institution of Applied Sciences — Curriculum Development Draft*
