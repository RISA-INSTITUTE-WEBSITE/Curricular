# COMS102 — Linux Basics for Cybersecurity

**Institution:** RISA Institution of Applied Sciences  
**Discipline:** Ethical Hacking (COMS)  
**Module code:** COMS102  
**Module title:** Linux Basics for Cybersecurity  
**Level:** Introductory / progressive sequence (formal level to be decided)  
**Document:** Proposed learning outcomes, syllabus and assessment activities  
**Status:** Draft — pending academic, technical, legal and safety review  
**Version:** 0.1  
**Date:** 22 November 2026

## 1. Module purpose

Develop practical Linux fluency specifically for cybersecurity investigations, system defense and safe operation of controlled security-training laboratories.

## 2. Proposed entry preparation

COMS101 recommended; demonstrate basic computer literacy before operating a Linux lab.

*Recommendations only; formal prerequisites and equivalency pathways require academic approval.*

## 3. Proposed measurable learning outcomes

Upon successful completion, learners should be able to:

| Code | Learning outcome |
| --- | --- |
| **LO1** | Explain the Linux operating system, shell, filesystem hierarchy and common administrative roles. |
| **LO2** | Navigate, create, inspect and manage files and directories safely using terminal commands. |
| **LO3** | Interpret Linux permissions, ownership, users, groups and the principle of least privilege. |
| **LO4** | Inspect running processes, services and resource use without destabilizing a host. |
| **LO5** | Identify basic network interfaces, addressing, listening sockets and DNS behavior on an approved Linux host. |
| **LO6** | Read and interpret local logs and system status for elementary security triage. |
| **LO7** | Use packages, updates and secure configuration practices in a disposable Linux lab. |
| **LO8** | Document reproducible, bounded command-line investigations while sanitizing secrets and restoring the initial lab state. |

## 4. Teaching-section alignment

| Section | Core content | Outcomes |
| --- | --- | --- |
| **A — Linux Lab Setup and Fundamentals** | Linux distributions, VM/WSL alternatives, terminal, filesystems and safe reset | LO1–LO2 |
| **B — Files, Permissions and Identity** | Navigation, paths, text utilities, access permissions, ownership, accounts and groups | LO2–LO3 |
| **C — Processes and Services** | Process viewing, service status, basic system monitoring and logs | LO4, LO6 |
| **D — Linux Networking for Security** | IP addressing, sockets, DNS, SSH client concepts and local diagnostics | LO5 |
| **E — Host Hygiene and Evidence** | Packages, security updates, minimal privileges, system snapshots and report writing | LO6–LO8 |

The teaching sections, learning outcomes and sequencing are **new syllabus proposals**, not a verbatim transcription of the handwritten list.

## 5. Proposed practical learning and assessment

| Activity | Learning task / evidence | Outcomes |
| --- | --- | --- |
| **Workstation readiness** | Start an approved Linux VM or managed host, verify user identity and record rollback method | LO1, LO8 |
| **Permissions and identity** | Apply least-privilege file access to synthetic training data and explain resulting access | LO2–LO3 |
| **Security triage** | Use local service, process, listening-port and log information to explain a preconfigured fault | LO4–LO6 |
| **Maintenance and recovery** | Apply approved updates to a disposable fixture, collect evidence and restore snapshot | LO7–LO8 |

Each lab requires a written scope and authorized target list, readiness verification, instructor-tested fixtures, a recovery/reset procedure, sanitized evidence, and a rubric. Activities are proposals until lab scripts, guides, model results and marking criteria are reviewed and piloted.

## 6. Teaching and safety boundaries

Students must use their own or approved lab Linux host only. No credential harvesting or testing against shared production hosts. Linux security work is distinguished from the more general DevOps Linux module by its emphasis on least privilege, logs, secure configuration, investigation and lab safety.

Learners must seek written authorization **before** any security test, preserve privacy, refrain from testing systems outside scope and follow the instructor's stop-and-escalate procedure. Any unsafe or unapproved activity is outside this curriculum.

## 7. Proposed assessment evidence

- **Knowledge checkpoint:** Explain key concepts and ethical scope constraints for the module.
- **Setup readiness (Pass/Retry):** Verify isolation, target authorization, basic tools and rollback method before practical tasks.
- **Practical task(s):** Submit independently explainable, sanitized outputs, observations and remediation/retest evidence.
- **Final module assessment:** Analyze a permitted case, justify findings and communicate security improvements with limitations.

**Unresolved decisions:** contact/notional hours, formal academic level, credit value, prerequisite enforcement, assessment weighting, pass criteria, appeals/moderation, exact lab toolchain, equipment needs and academic approval.

## 8. Provenance and review status

**Source:** Handwritten *Ethical Hacking (COMS)* outline supplied 22 November 2026, giving module COMS102 and its topic. The user specifically requested the new title **Linux Basics for Cybersecurity**, replacing **Linux Basics**. All detailed learning outcomes, sections, laboratories, assessment evidence and safety controls above are proposed curriculum developments and must not be portrayed as already approved or delivered.

---

*RISA Institution of Applied Sciences — Curriculum Development Draft*
