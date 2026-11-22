# COMS105 — Website Hacking

**Institution:** RISA Institution of Applied Sciences  
**Discipline:** Ethical Hacking (COMS)  
**Module code:** COMS105  
**Module title:** Website Hacking  
**Level:** Introductory / progressive sequence (formal level to be decided)  
**Document:** Proposed learning outcomes, syllabus and assessment activities  
**Status:** Draft — pending academic, technical, legal and safety review  
**Version:** 0.1  
**Date:** 22 November 2026

## 1. Module purpose

Develop skills in the ethical assessment and remediation of web-application security weaknesses using intentionally vulnerable, isolated training applications and documented authorization.

## 2. Proposed entry preparation

COMS101–COMS104 recommended; basic HTTP, client–server architecture and web forms should be understood or bridged.

*Recommendations only; formal prerequisites and equivalency pathways require academic approval.*

## 3. Proposed measurable learning outcomes

Upon successful completion, learners should be able to:

| Code | Learning outcome |
| --- | --- |
| **LO1** | Describe HTTP/HTTPS requests, responses, cookies, sessions and common web architecture components. |
| **LO2** | Explain web authentication, authorization, input-handling and browser/server trust boundaries. |
| **LO3** | Define authorized target scope, permitted methods, test accounts and safe data-handling procedures. |
| **LO4** | Recognize common web weaknesses, including injection, cross-site scripting, access-control flaws, insecure configuration and session weaknesses, from controlled examples. |
| **LO5** | Use approved lab observations and non-destructive checks to validate instructor-defined vulnerabilities in a deliberately vulnerable application. |
| **LO6** | Identify root causes and recommend secure coding, validation, access-control and configuration changes. |
| **LO7** | Compare before/after results to show that a fix is effective in the training application. |
| **LO8** | Produce a concise web security assessment report with evidence, severity rationale, limitations and remediation verification. |

## 4. Teaching-section alignment

| Section | Core content | Outcomes |
| --- | --- | --- |
| **A — Web Technology Foundations** | HTTP/HTTPS, requests, responses, cookies, sessions and web architecture | LO1–LO2 |
| **B — Responsible Web Testing** | Written authorization, fixtures, isolated target, safe test inputs and evidence hygiene | LO3 |
| **C — Vulnerability Understanding** | Common weakness classes and their defensive causes using training cases | LO4–LO5 |
| **D — Secure Remediation** | Input handling, contextual output encoding, parameterization, access checks and hardening | LO6–LO7 |
| **E — Verification and Reporting** | Retesting, reproducible evidence, prioritization and communication | LO7–LO8 |

The teaching sections, learning outcomes and sequencing are **new syllabus proposals**, not a verbatim transcription of the handwritten list.

## 5. Proposed practical learning and assessment

| Activity | Learning task / evidence | Outcomes |
| --- | --- | --- |
| **HTTP and session observation** | Inspect instructor-provided HTTP traces and identify security-relevant headers and session behavior | LO1–LO2 |
| **Training-app security review** | Use a deliberately vulnerable local web app to document a bounded, preapproved weakness without real data | LO3–LO5 |
| **Remediation validation** | Compare training-app behavior before and after an instructor-provided security fix | LO6–LO8 |

Each lab requires a written scope and authorized target list, readiness verification, instructor-tested fixtures, a recovery/reset procedure, sanitized evidence, and a rubric. Activities are proposals until lab scripts, guides, model results and marking criteria are reviewed and piloted.

## 6. Teaching and safety boundaries

Do not test public or production websites, scrape private accounts, harvest session tokens or conduct destructive or uncontrolled exploitation. Approved training apps must be isolated, seeded only with synthetic records, and fully resettable.

Learners must seek written authorization **before** any security test, preserve privacy, refrain from testing systems outside scope and follow the instructor's stop-and-escalate procedure. Any unsafe or unapproved activity is outside this curriculum.

## 7. Proposed assessment evidence

- **Knowledge checkpoint:** Explain key concepts and ethical scope constraints for the module.
- **Setup readiness (Pass/Retry):** Verify isolation, target authorization, basic tools and rollback method before practical tasks.
- **Practical task(s):** Submit independently explainable, sanitized outputs, observations and remediation/retest evidence.
- **Final module assessment:** Analyze a permitted case, justify findings and communicate security improvements with limitations.

**Unresolved decisions:** contact/notional hours, formal academic level, credit value, prerequisite enforcement, assessment weighting, pass criteria, appeals/moderation, exact lab toolchain, equipment needs and academic approval.

## 8. Provenance and review status

**Source:** Handwritten *Ethical Hacking (COMS)* outline supplied 22 November 2026, giving module COMS105 and its topic. All detailed learning outcomes, sections, laboratories, assessment evidence and safety controls above are proposed curriculum developments and must not be portrayed as already approved or delivered.

---

*RISA Institution of Applied Sciences — Curriculum Development Draft*
