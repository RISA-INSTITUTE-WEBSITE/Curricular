# COMS103 — Network Hacking

**Institution:** RISA Institution of Applied Sciences  
**Discipline:** Ethical Hacking (COMS)  
**Module code:** COMS103  
**Module title:** Network Hacking  
**Level:** Introductory / progressive sequence (formal level to be decided)  
**Document:** Proposed learning outcomes, syllabus and assessment activities  
**Status:** Draft — pending academic, technical, legal and safety review  
**Version:** 0.1  
**Date:** 22 November 2026

## 1. Module purpose

Teach the responsible assessment of network exposure and security controls in expressly authorized environments, emphasizing packet interpretation, safe discovery and defensible reporting.

## 2. Proposed entry preparation

COMS101 and COMS102 recommended; basic TCP/IP competence should be verified before testing.

*Recommendations only; formal prerequisites and equivalency pathways require academic approval.*

## 3. Proposed measurable learning outcomes

Upon successful completion, learners should be able to:

| Code | Learning outcome |
| --- | --- |
| **LO1** | Explain TCP/IP, common ports, routing, DNS, switching and basic segmentation relevant to security. |
| **LO2** | Define target scope, authorization, prohibited actions and safe network-test limits. |
| **LO3** | Map an approved lab network from supplied topology and configuration information. |
| **LO4** | Interpret packet captures to identify normal communications, anomalies and sensitive-data exposure. |
| **LO5** | Perform bounded network and service discovery on instructor-provided isolated lab targets. |
| **LO6** | Evaluate the purpose and limitations of firewalls, segmentation, encryption and secure network configuration. |
| **LO7** | Correlate observed exposure with a plausible risk and recommend least-disruptive mitigation. |
| **LO8** | Write a reproducible network assessment report and verify a defensive change. |

## 4. Teaching-section alignment

| Section | Core content | Outcomes |
| --- | --- | --- |
| **A — Networking Review** | IP, TCP/UDP, DNS, protocols, routing and segmentation | LO1 |
| **B — Engagement Rules and Lab Design** | Written permission, target allowlists, test budgets and network isolation | LO2–LO3 |
| **C — Observation and Discovery** | Topology review, offline packet captures and bounded discovery of approved services | LO3–LO5 |
| **D — Defense Validation** | Firewalls, ACLs, encrypted services, segmentation and configuration review | LO6–LO7 |
| **E — Reporting and Retesting** | Evidence correlation, safe reporting, remediation and verification | LO7–LO8 |

The teaching sections, learning outcomes and sequencing are **new syllabus proposals**, not a verbatim transcription of the handwritten list.

## 5. Proposed practical learning and assessment

| Activity | Learning task / evidence | Outcomes |
| --- | --- | --- |
| **Topology and packet analysis** | Study an instructor-provided offline capture and annotate communications and risks | LO1, LO4 |
| **Authorized discovery** | Document the allowed local subnet and collect minimal service inventory from sandbox hosts | LO2, LO3, LO5 |
| **Segmentation verification** | Apply a defensive rule in a simulated network and show before/after reachability | LO6–LO8 |

Each lab requires a written scope and authorized target list, readiness verification, instructor-tested fixtures, a recovery/reset procedure, sanitized evidence, and a rubric. Activities are proposals until lab scripts, guides, model results and marking criteria are reviewed and piloted.

## 6. Teaching and safety boundaries

Discovery is restricted to specifically enumerated lab assets. No scanning public address space, institutional production networks, denial-of-service tests or interception of third-party traffic. Controlled training activities must use safe rate limits and a clearly defined stop condition.

Learners must seek written authorization **before** any security test, preserve privacy, refrain from testing systems outside scope and follow the instructor's stop-and-escalate procedure. Any unsafe or unapproved activity is outside this curriculum.

## 7. Proposed assessment evidence

- **Knowledge checkpoint:** Explain key concepts and ethical scope constraints for the module.
- **Setup readiness (Pass/Retry):** Verify isolation, target authorization, basic tools and rollback method before practical tasks.
- **Practical task(s):** Submit independently explainable, sanitized outputs, observations and remediation/retest evidence.
- **Final module assessment:** Analyze a permitted case, justify findings and communicate security improvements with limitations.

**Unresolved decisions:** contact/notional hours, formal academic level, credit value, prerequisite enforcement, assessment weighting, pass criteria, appeals/moderation, exact lab toolchain, equipment needs and academic approval.

## 8. Provenance and review status

**Source:** Handwritten *Ethical Hacking (COMS)* outline supplied 22 November 2026, giving module COMS103 and its topic. All detailed learning outcomes, sections, laboratories, assessment evidence and safety controls above are proposed curriculum developments and must not be portrayed as already approved or delivered.

---

*RISA Institution of Applied Sciences — Curriculum Development Draft*
