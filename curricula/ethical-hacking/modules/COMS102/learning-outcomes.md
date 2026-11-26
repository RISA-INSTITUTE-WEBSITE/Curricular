# COMS102 — Linux Basics for Cybersecurity

**Institution:** RISA Institution of Applied Sciences  
**Discipline:** Ethical Hacking (COMS)  
**Module code:** COMS102  
**Module title:** Linux Basics for Cybersecurity  
**Level:** Introductory / progressive sequence (formal level to be decided)  
**Document:** Proposed learning outcomes, syllabus and assessment activities  
**Status:** Draft — pending academic, technical, legal and safety review  
**Version:** 0.2 (practical learning-outcomes revision)  
**Date:** 22 November 2026

## 1. Module purpose

Develop practical Linux fluency specifically for cybersecurity investigations, system defense and safe operation of controlled security-training laboratories.

## 2. Proposed entry preparation

COMS101 recommended; demonstrate basic computer literacy before operating a Linux lab.

*Recommendations only; formal prerequisites and equivalency pathways require academic approval.*

## 3. Practical, assessable learning outcomes

Upon successful completion of COMS102, a learner should be able to **independently demonstrate** the following in an expressly authorized, resettable environment. Each outcome has a tangible assessment artifact.

| Code | Practical learning outcome | Minimum observable evidence |
| --- | --- | --- |
| **LO1** | Start and verify an approved Linux cybersecurity lab, record host identity and tooling, and demonstrate its recovery route. | System baseline and passed lab-readiness verification |
| **LO2** | Use terminal commands to organize, search, inspect and safely transform files within a designated Linux workspace. | Reproducible command transcript and resulting files |
| **LO3** | Create synthetic users and groups, assign file ownership and permissions, and verify expected permitted and denied access. | Permission matrix, commands and access-test results |
| **LO4** | Inspect Linux processes, resource use and service status to diagnose an instructor-seeded service problem without disrupting other systems. | Diagnostic transcript and justified resolution |
| **LO5** | Inspect network interfaces, addressing, routes, name resolution and listening sockets on an authorized Linux host. | Annotated local networking diagnostic report |
| **LO6** | Filter and correlate local or supplied Linux log records to identify a predefined security-relevant event. | Sanitized log excerpts and timestamped incident note |
| **LO7** | Verify package status, apply an approved security maintenance or hardening change in a disposable host, and validate or roll back the result. | Change record and before/after verification |
| **LO8** | Write and run a read-only shell script that gathers non-sensitive host health indicators and produces a repeatable, clearly labeled output. | Runnable script, test runs and error-handling evidence |

**Outcome standard:** Assess what the learner can perform, verify and justify—not only what they can define or recall. Passing a setup-readiness check is necessary before lab access but is not proof of module competence.

## 4. Teaching-section alignment

| Section | Practical teaching emphasis | Outcomes |
| --- | --- | --- |
| **A — Setup and CLI** | Lab provisioning, restoration, Linux filesystem and command-line workflow | LO1, LO2 |
| **B — Identity and Permissions** | Users, groups, ownership and least-privilege access tests | LO3 |
| **C — Services and Incident Clues** | Processes, resource checks, service status and log investigation | LO4, LO6 |
| **D — Host Networking** | Interfaces, routes, DNS and listening sockets on authorized hosts | LO5 |
| **E — Security Maintenance and Bash** | Updates, safe hardening, rollback, read-only scripting and documentation | LO7, LO8 |

The learning outcomes, teaching sections, laboratory activities and assessment evidence are **proposals** developed from the module topics; they are not a verbatim transcription of the handwritten source.

## 5. Proposed practical learning and assessment

Practical activities should involve hands-on demonstration and repeatable observation, accompanied by brief explanations of the findings.

| Activity | Student task and required evidence | Outcomes |
| --- | --- | --- |
| **Lab 1 — Linux readiness** | Verify a resettable Linux environment and complete a terminal file-management exercise | LO1, LO2 |
| **Lab 2 — Least privilege** | Configure synthetic users and permissions; test positive and negative access cases | LO3 |
| **Lab 3 — Host triage** | Diagnose a preconfigured service fault using process, log and network observations | LO4, LO5, LO6 |
| **Lab 4 — Maintain and automate** | Apply an authorized update/hardening change and write a safe status-reporting script | LO7, LO8 |

**Integrated practical exit task (proposal):** Using an instructor-owned Linux fixture, investigate a seeded host problem, correct one configuration issue, run a safe repeatable health-check script, and submit sanitized, verifiable evidence.

**Lab gate:** Written authorization, a limited target list, safe readiness check, instructor-tested fixtures, a recovery/reset path, redacted evidence and a marking rubric are mandatory. These lab briefs remain **unpiloted proposals** until the learning environment, student instructions, reference results and marking instruments are developed and verified.

## 6. Teaching and safety boundaries

Students must use their own or approved lab Linux host only. No credential harvesting or testing against shared production hosts. Linux security work is distinguished from the more general DevOps Linux module by its emphasis on least privilege, logs, secure configuration, investigation and lab safety.

Learners must seek written authorization **before** any security test, preserve privacy, refrain from testing systems outside scope and follow the instructor's stop-and-escalate procedure. Any unsafe or unapproved activity is outside this curriculum.

## 7. Practical-first assessment evidence (proposed)

- **Setup and authorization — prerequisite gate (Pass/Retry):** Independently verify that the student is operating within an approved isolated fixture and can restore the environment. This readiness check is **not** a graded learning outcome by itself.
- **Hands-on laboratory portfolio:** Assessor checks actual configuration, captured safe observations, negative/positive test cases, commands or code, and explanations linked to the LO evidence column above.
- **Integrated practical exit task:** In an unseen but equivalent instructor-owned fixture, independently complete the bounded task, investigate a seeded issue, demonstrate a defensible improvement, retest and document limitations.
- **Short knowledge checkpoint and technical explanation:** Explain why results matter and justify safety, controls, analysis and corrective action; a written definition alone cannot substitute for verified lab competence.

**Practical orientation:** A **provisional** teaching-time target is 70% supervised practical work, 20% theory/demonstration and 10% review/reporting. This is **not** an approved mark distribution, credit allocation or pass standard. Assessment weighting and moderation must be academically approved.

**Unresolved decisions:** notional/contact hours, formal academic level, credit value, prerequisite enforcement, mark weighting, pass criteria, appeals/moderation, exact lab toolchain, learner hardware, academic approval, and final safety-gate policy.

## 8. Provenance and review status

**Source:** Handwritten *Ethical Hacking (COMS)* outline supplied 22 November 2026, giving module COMS102 and its topic. The user specifically requested the new title **Linux Basics for Cybersecurity**, replacing **Linux Basics**. Detailed outcomes were refactored on 22 November 2026 to emphasize independently assessable practical competence; all outcomes, sections, laboratories, assessment evidence and safety controls remain proposed curriculum developments and must not be portrayed as already approved or delivered.

---

*RISA Institution of Applied Sciences — Curriculum Development Draft*
