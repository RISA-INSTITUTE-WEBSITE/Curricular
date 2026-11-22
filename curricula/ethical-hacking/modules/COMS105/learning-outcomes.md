# COMS105 — Website Hacking

**Institution:** RISA Institution of Applied Sciences  
**Discipline:** Ethical Hacking (COMS)  
**Module code:** COMS105  
**Module title:** Website Hacking  
**Level:** Introductory / progressive sequence (formal level to be decided)  
**Document:** Proposed learning outcomes, syllabus and assessment activities  
**Status:** Draft — pending academic, technical, legal and safety review  
**Version:** 0.2 (practical learning-outcomes revision)  
**Date:** 22 November 2026

## 1. Module purpose

Develop skills in the ethical assessment and remediation of web-application security weaknesses using intentionally vulnerable, isolated training applications and documented authorization.

## 2. Proposed entry preparation

COMS101–COMS104 recommended; basic HTTP, client–server architecture and web forms should be understood or bridged.

*Recommendations only; formal prerequisites and equivalency pathways require academic approval.*

## 3. Practical, assessable learning outcomes

Upon successful completion of COMS105, a learner should be able to **independently demonstrate** the following in an expressly authorized, resettable environment. Each outcome has a tangible assessment artifact.

| Code | Practical learning outcome | Minimum observable evidence |
| --- | --- | --- |
| **LO1** | Deploy or access an isolated, deliberately vulnerable training website with synthetic accounts, explicit scope and a verified reset path. | Web-lab readiness and authorized target checklist |
| **LO2** | Capture and sanitize HTTP request/response evidence from a training session and map the application's login, cookie and session behavior. | Annotated HTTP/session flow diagram and redacted traces |
| **LO3** | Reproduce one instructor-defined authentication, authorization or input-handling weakness using non-destructive checks and synthetic data. | Minimal, scope-bound observation and expected/actual results |
| **LO4** | Review the approved application's example source code or configuration to identify and explain the cause of the seeded weakness. | Root-cause note referencing the affected file or setting |
| **LO5** | Implement an authorized defensive change, such as a server-side access check, safe input handling or configuration correction, in the training application. | Code/configuration change and reasoned fix description |
| **LO6** | Create and run repeatable positive and negative tests that verify intended secure behavior and guard against regressions. | Automated or scripted regression-test results |
| **LO7** | Compare observed behavior before and after the fix, confirming effectiveness and documenting remaining limitations. | Sanitized before/after verification record |
| **LO8** | Submit a web application security report with scope, reproducible evidence, justified risk, remediation and retest results. | Complete technical and executive findings report |

**Outcome standard:** Assess what the learner can perform, verify and justify—not only what they can define or recall. Passing a setup-readiness check is necessary before lab access but is not proof of module competence.

## 4. Teaching-section alignment

| Section | Practical teaching emphasis | Outcomes |
| --- | --- | --- |
| **A — Web Lab and HTTP Essentials** | Authorized application setup, requests, cookies and sessions | LO1, LO2 |
| **B — Scope and Controlled Testing** | Synthetic accounts, non-destructive tests, narrowly defined seeded weaknesses | LO1, LO3 |
| **C — Secure Code Investigation** | Source/config review, root cause and safe remediation | LO4, LO5 |
| **D — Regression Testing** | Positive and negative tests and before/after observations | LO6, LO7 |
| **E — Evidence and Report** | Risk rationale, redaction, limitations and stakeholder reporting | LO7, LO8 |

The learning outcomes, teaching sections, laboratory activities and assessment evidence are **proposals** developed from the module topics; they are not a verbatim transcription of the handwritten source.

## 5. Proposed practical learning and assessment

Practical activities should involve hands-on demonstration and repeatable observation, accompanied by brief explanations of the findings.

| Activity | Student task and required evidence | Outcomes |
| --- | --- | --- |
| **Lab 1 — Controlled HTTP tracing** | Verify safe local web-app setup and annotate redacted request/session flows | LO1, LO2 |
| **Lab 2 — Seeded issue investigation** | Confirm a preapproved training weakness using synthetic data and locate its root cause | LO3, LO4 |
| **Lab 3 — Fix and test** | Apply a defensive coding/configuration change and run security regression cases | LO5, LO6 |
| **Lab 4 — Retest and report** | Produce evidence of before/after behavior and a reproducible findings report | LO7, LO8 |

**Integrated practical exit task (proposal):** Assess an instructor-owned deliberately vulnerable application, document one instructor-seeded weakness, implement an authorized defensive change, demonstrate passing security regression tests, and present an evidence-based report.

**Lab gate:** Written authorization, a limited target list, safe readiness check, instructor-tested fixtures, a recovery/reset path, redacted evidence and a marking rubric are mandatory. These lab briefs remain **unpiloted proposals** until the learning environment, student instructions, reference results and marking instruments are developed and verified.

## 6. Teaching and safety boundaries

Do not test public or production websites, scrape private accounts, harvest session tokens or conduct destructive or uncontrolled exploitation. Approved training apps must be isolated, seeded only with synthetic records, and fully resettable.

Learners must seek written authorization **before** any security test, preserve privacy, refrain from testing systems outside scope and follow the instructor's stop-and-escalate procedure. Any unsafe or unapproved activity is outside this curriculum.

## 7. Practical-first assessment evidence (proposed)

- **Setup and authorization — prerequisite gate (Pass/Retry):** Independently verify that the student is operating within an approved isolated fixture and can restore the environment. This readiness check is **not** a graded learning outcome by itself.
- **Hands-on laboratory portfolio:** Assessor checks actual configuration, captured safe observations, negative/positive test cases, commands or code, and explanations linked to the LO evidence column above.
- **Integrated practical exit task:** In an unseen but equivalent instructor-owned fixture, independently complete the bounded task, investigate a seeded issue, demonstrate a defensible improvement, retest and document limitations.
- **Short knowledge checkpoint and technical explanation:** Explain why results matter and justify safety, controls, analysis and corrective action; a written definition alone cannot substitute for verified lab competence.

**Practical orientation:** A **provisional** teaching-time target is 70% supervised practical work, 20% theory/demonstration and 10% review/reporting. This is **not** an approved mark distribution, credit allocation or pass standard. Assessment weighting and moderation must be academically approved.

**Unresolved decisions:** notional/contact hours, formal academic level, credit value, prerequisite enforcement, mark weighting, pass criteria, appeals/moderation, exact lab toolchain, learner hardware, academic approval, and final safety-gate policy.

## 8. Provenance and review status

**Source:** Handwritten *Ethical Hacking (COMS)* outline supplied 22 November 2026, giving module COMS105 and its topic. Detailed outcomes were refactored on 22 November 2026 to emphasize independently assessable practical competence; all outcomes, sections, laboratories, assessment evidence and safety controls remain proposed curriculum developments and must not be portrayed as already approved or delivered.

---

*RISA Institution of Applied Sciences — Curriculum Development Draft*
