# COMS103 — Network Hacking

**Institution:** RISA Institution of Applied Sciences  
**Discipline:** Ethical Hacking (COMS)  
**Module code:** COMS103  
**Module title:** Network Hacking  
**Level:** Introductory / progressive sequence (formal level to be decided)  
**Document:** Proposed learning outcomes, syllabus and assessment activities  
**Status:** Draft — pending academic, technical, legal and safety review  
**Version:** 0.2 (practical learning-outcomes revision)  
**Date:** 22 November 2026

## 1. Module purpose

Teach the responsible assessment of network exposure and security controls in expressly authorized environments, emphasizing packet interpretation, safe discovery and defensible reporting.

## 2. Proposed entry preparation

COMS101 and COMS102 recommended; basic TCP/IP competence should be verified before testing.

*Recommendations only; formal prerequisites and equivalency pathways require academic approval.*

## 3. Practical, assessable learning outcomes

Upon successful completion of COMS103, a learner should be able to **independently demonstrate** the following in an expressly authorized, resettable environment. Each outcome has a tangible assessment artifact.

| Code | Practical learning outcome | Minimum observable evidence |
| --- | --- | --- |
| **LO1** | Construct or validate an isolated training-network topology and demonstrate expected connectivity between designated nodes. | Topology diagram and permitted connectivity tests |
| **LO2** | Prepare a written test plan with explicitly allowed targets, methods, exclusions, observation limits and stop conditions. | Approved laboratory scope and test plan |
| **LO3** | Examine an instructor-provided packet capture to classify protocols, endpoints and notable communication patterns. | Annotated packet-analysis worksheet |
| **LO4** | Document the observed hosts and exposed services within an instructor-allowlisted sandbox using bounded, non-disruptive discovery. | Service inventory matched to the approved target list |
| **LO5** | Inspect the behavior and configuration of name resolution and encrypted connections in controlled network services. | DNS/TLS observation and misconfiguration notes |
| **LO6** | Apply an approved firewall or segmentation rule in a simulated network and verify expected allowed and blocked traffic. | Rule change and before/after test matrix |
| **LO7** | Diagnose a seeded reachability or exposure problem using routing information, packet evidence and network policy; verify the correction. | Troubleshooting log, supported root cause and retest |
| **LO8** | Deliver a network assessment report that connects observations to risks, defensive changes, limitations and reproducible evidence. | Scoped findings report and sanitized evidence pack |

**Outcome standard:** Assess what the learner can perform, verify and justify—not only what they can define or recall. Passing a setup-readiness check is necessary before lab access but is not proof of module competence.

## 4. Teaching-section alignment

| Section | Practical teaching emphasis | Outcomes |
| --- | --- | --- |
| **A — Networks in Practice** | Topology, IP, transport behavior and controlled connectivity tests | LO1 |
| **B — Authorization and Scoping** | Written permission, allowlists, testing constraints and stop rules | LO2 |
| **C — Traffic and Exposure** | Offline packet analysis and bounded service inventory in isolated targets | LO3, LO4 |
| **D — Network Defenses** | DNS/TLS checks, firewall and segmentation tests, seeded fault diagnosis | LO5, LO6, LO7 |
| **E — Evidence and Retesting** | Network reporting, corrective verification and limitations | LO7, LO8 |

The learning outcomes, teaching sections, laboratory activities and assessment evidence are **proposals** developed from the module topics; they are not a verbatim transcription of the handwritten source.

## 5. Proposed practical learning and assessment

Practical activities should involve hands-on demonstration and repeatable observation, accompanied by brief explanations of the findings.

| Activity | Student task and required evidence | Outcomes |
| --- | --- | --- |
| **Lab 1 — Virtual topology** | Set up or inspect a simulated network and record approved targets and expected paths | LO1, LO2 |
| **Lab 2 — Packet investigation** | Analyze a synthetic/offline capture and inventory sandbox services within scope | LO3, LO4 |
| **Lab 3 — Defensive controls** | Validate a lab DNS/TLS setting and demonstrate firewall isolation using synthetic traffic | LO5, LO6 |
| **Lab 4 — Diagnose and report** | Resolve a seeded routing/firewall fault and document before/after verification | LO7, LO8 |

**Integrated practical exit task (proposal):** Assess an isolated practice network against its authorized scope, explain observable traffic and service exposure, verify a firewall/segmentation control and submit a reproducible security assessment.

**Lab gate:** Written authorization, a limited target list, safe readiness check, instructor-tested fixtures, a recovery/reset path, redacted evidence and a marking rubric are mandatory. These lab briefs remain **unpiloted proposals** until the learning environment, student instructions, reference results and marking instruments are developed and verified.

## 6. Teaching and safety boundaries

Discovery is restricted to specifically enumerated lab assets. No scanning public address space, institutional production networks, denial-of-service tests or interception of third-party traffic. Controlled training activities must use safe rate limits and a clearly defined stop condition.

Learners must seek written authorization **before** any security test, preserve privacy, refrain from testing systems outside scope and follow the instructor's stop-and-escalate procedure. Any unsafe or unapproved activity is outside this curriculum.

## 7. Practical-first assessment evidence (proposed)

- **Setup and authorization — prerequisite gate (Pass/Retry):** Independently verify that the student is operating within an approved isolated fixture and can restore the environment. This readiness check is **not** a graded learning outcome by itself.
- **Hands-on laboratory portfolio:** Assessor checks actual configuration, captured safe observations, negative/positive test cases, commands or code, and explanations linked to the LO evidence column above.
- **Integrated practical exit task:** In an unseen but equivalent instructor-owned fixture, independently complete the bounded task, investigate a seeded issue, demonstrate a defensible improvement, retest and document limitations.
- **Short knowledge checkpoint and technical explanation:** Explain why results matter and justify safety, controls, analysis and corrective action; a written definition alone cannot substitute for verified lab competence.

**Practical orientation:** A **provisional** teaching-time target is 70% supervised practical work, 20% theory/demonstration and 10% review/reporting. This is **not** an approved mark distribution, credit allocation or pass standard. Assessment weighting and moderation must be academically approved.

**Unresolved decisions:** notional/contact hours, formal academic level, credit value, prerequisite enforcement, mark weighting, pass criteria, appeals/moderation, exact lab toolchain, learner hardware, academic approval, and final safety-gate policy.

## 8. Provenance and review status

**Source:** Handwritten *Ethical Hacking (COMS)* outline supplied 22 November 2026, giving module COMS103 and its topic. Detailed outcomes were refactored on 22 November 2026 to emphasize independently assessable practical competence; all outcomes, sections, laboratories, assessment evidence and safety controls remain proposed curriculum developments and must not be portrayed as already approved or delivered.

---

*RISA Institution of Applied Sciences — Curriculum Development Draft*
