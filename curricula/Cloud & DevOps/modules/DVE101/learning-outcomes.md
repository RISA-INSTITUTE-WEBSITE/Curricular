# DVE101 — DevOps Systems and Collaborative Computing Foundations

**Repository:** RISA Institution of Applied Sciences — Curricular
**Discipline:** Cloud & DevOps
**Module code:** DVE101
**Module title:** DevOps Systems and Collaborative Computing Foundations
**Proposed duration:** 11 teaching weeks · 132 notional learning hours · programme weeks 1–11
**Document:** Draft module learning outcomes, syllabus and practical requirements
**Status:** Draft — pending technical pilot and institutional academic approval
**Version:** 0.1 (adapted from BIH source curriculum v1.2)
**Date:** 21 November 2026

## 1. Module purpose

Establish practical Linux administration, basic networking, shell scripting, operations automation, source control, and machine-readable configuration skills.

## 2. Entry requirements and progression

**Mandatory:** Basic computer literacy, terminal access and ability to create/organize files. No previous DevOps qualification is required.

**Recommended/corequisites:** Basic understanding of software applications and web requests is useful; it is taught when needed.

Approved, documented practical equivalence may substitute for prerequisites where indicated by the programme policy; attendance alone does not prove competence.

## 3. Proposed module learning outcomes

**Upon successful completion of DVE101, learners should be able to:**

| Code | Outcome | Source section |
| --- | --- | --- |
| **LO1** | Inspect and manage a Linux practice environment safely. | A |
| **LO2** | Operate a service and justify each corrective action. | B |
| **LO3** | Locate and diagnose network reachability failures. | C |
| **LO4** | Develop a testable diagnostic script. | D |
| **LO5** | Operate a scheduled, auditable maintenance task. | E |
| **LO6** | Deliver a reviewed, traceable source change. | F |
| **LO7** | Produce valid YAML for a later automation task. | G |

These outcomes reproduce the assessable section outcomes in the source curriculum. The competency assessment must demonstrate them through independent evidence.

## 4. Teaching-section alignment and proposed hours

| Section | Syllabus focus | Core content | Hours |
| --- | --- | --- | ---: |
| **A — Introduction to Linux for DevOps** | Inspect and manage a Linux practice environment safely. | Linux architecture, filesystem hierarchy and navigation; permissions, identity, processes, text processing, storage, access policy. | 28 |
| **B — Linux System and Service Administration** | Operate a service and justify each corrective action. | DNF/RPM, repositories, systemd units, Apache, logs, verification and controlled service recovery. | 20 |
| **C — Linux Networking Fundamentals** | Locate and diagnose network reachability failures. | IP, TCP/UDP, ports, DNS, routing, SSH, HTTP/HTTPS and host firewall concepts. | 18 |
| **D — Bash Scripting** | Develop a testable diagnostic script. | Variables, conditionals, loops, functions, arguments, streams, exit status and error handling. | 20 |
| **E — Linux Automation and Operations** | Operate a scheduled, auditable maintenance task. | cron, systemd timers, repeatability, logging, health checks, backup/restore and safe scheduling. | 12 |
| **F — Git and GitHub** | Deliver a reviewed, traceable source change. | Branches, commits, remotes, pull requests, code reviews, conflicts, tags and repository access controls. | 22 |
| **G — YAML Fundamentals** | Produce valid YAML for a later automation task. | Mappings, sequences, quoting, types, anchors, indentation, validation and configuration review. | 8 |

**Proposed workload allocation:** A 28 · B 20 · C 18 · D 20 · E 12 · F 22 · G 8 · final assessment 4.

## 5. Setup-first laboratory readiness

The source prescribes Prepare → Verify → Explain → Demonstrate → Practise → Assess. Setup readiness is **Pass/Retry**, with support/retesting, and is distinct from summative marks. Setup time fits within the section hours above.

| Section | Environment setup | Pass/Retry readiness evidence |
| --- | --- | --- |
| A | Approved Fedora route, Bash, DNF5, editor and workspace from DVE101-00. | Independently verify identity, utilities and working directory. |
| B | Verify systemd, journal access, disposable Fedora host, DNF/RPM and Apache lab. | Inspect units and demonstrate a known-good recovery route. |
| C | Verify ip, ss, dig/getent, curl, SSH client and authorized local targets. | Resolve a test hostname, inspect sockets and reach a bounded service. |
| D | Verify Bash, shellcheck if available, editor, executable workspace and test inputs. | Run a script and return meaningful exit codes. |
| E | Verify scheduler, writable test logs and restore fixture. | Schedule, inspect and safely disable a test task. |
| F | Configure authorized Git identity, GitHub authentication/2FA, course repository and protected-branch workflow. | Create authorized commit, push and PR; demonstrate safe access. |
| G | Verify YAML-aware editor and parser/validator with test fixtures. | Validate correct YAML and identify malformed YAML. |

## 5A. DVE101-00 mandatory preparatory lesson

**Student Workstation Setup and Environment Verification:** 3–4 hours **within Section A's existing 28 hours**, no extra week. Delivery routes: Windows + approved Fedora WSL2, supported native Fedora, or institution-approved managed Linux. Instructor records Pass/Retry, not summative marks.

| Part | Student topic | Verification / lecturer demonstration |
| --- | --- | --- |
| Opening | Outcomes, readiness, safety | Compare local/native/managed routes; separate readiness from competency. |
| 1 | Windows → WSL2 → Fedora; Bash, tools, VS Code | Distinguish host OS, distro, virtualization, shell and editor. |
| 2 | Workstation support, memory/disk and virtualization | Inspect WSL version/distributions and capacity without overwriting data. |
| 3 | Fedora WSL2 installation route | Confirm distribution ID, WSL2 and first launch; provide low-resource fallback. |
| 4 | Fedora identity and tools | Inspect OS, kernel, identity, DNF5/RPM, Git/curl/nano/Python and least privilege. |
| 5 | systemd | Distinguish systemd from systemctl; inspect PID 1 and service-manager capability. |
| 6 | VS Code WSL extension | Open Linux project and verify remote editor/terminal context. |
| 7 | Workspace | Create notes/, labs/ and evidence/ under ~/bih-dve101; keep secrets out of evidence. |
| 8 | Readiness verification | Confirm identity, tools, system-manager status, editor, folders and evidence sanitation. |

Readiness checks cover approved Linux route, tools, systemd feasibility, editor/files, and reproducible sanitized evidence. A diagnostic score may be recorded, but the decision remains **Pass/Retry** and is not part of DVE101 summative marks.

### Revised lesson teaching sequence

| Lesson | Topic / lab association |
| --- | --- |
| DVE101-00 | Workstation setup and verification (readiness only) |
| A1 | Introduction to Linux/system architecture |
| A2 | Filesystem hierarchy (/etc, /home, /var, /proc) |
| A3 | Navigation and file management — A-L01 |
| A4 | Permissions and ownership — A-L02 |
| A5 | Users, groups, access control — A-L03 |
| A6 | Processes and resource management — A-L04 |
| A7 | Streams, shell and text processing — A-L05 |
| A8 | Storage, filesystems and security — A-L06 and A-L07 |
| B1–B3 | Package management, systemd control, integrated incident — B-L01–L03 |

**Lesson packet:** a student-facing Canva slide with 3–6 essential ideas and one takeaway; separate detailed lecturer notes; a lab/assessment pack with setup, test inputs, expected state, negative cases, answer key and rubric.

## 6. Practical activities and assessment evidence

| Reference | Planned practical / deliverable |
| --- | --- |
| A-L01–L07 | Seven planned Linux foundation labs: navigation, permissions, identities, processes, streams, storage and security (original lab IDs 01–04 and 07–09). |
| B-L01–L03 | Three designed system labs: systemd, DNF/RPM package management and an integrated service incident (original lab IDs 05, 06 and 10). |
| C-L01 | Diagnose DNS, routing, socket/port and HTTP failures with ip, ss, dig/getent and curl; record fault and corrective verification. |
| D-L01 | Build an idempotent Bash health-check script with input validation, exit statuses, logs and failing-condition tests. |
| E-L01 | Schedule a safe recurring task using a systemd timer or cron; show logs, overlapping-run safeguards and restored backup. |
| F-L01 | Deliver a reviewed feature branch/PR; handle a conflict, use protected-main policy and produce a release tag. |
| G-L01 | Author and validate YAML mappings, sequences and quoting; explain parsed types and configuration errors. |

## 7. Module exit assessment

Integrated foundations practical: investigate a Linux host, administer it safely, troubleshoot an application service, deliver a controlled Git change, write an automation script and validate YAML.

**Evidence required:** Command transcripts, source-controlled scripts, Git PR evidence, YAML validation outputs, diagnostics and independent assessor result.

**Assessment standard (proposed):** overall mark at least 70% AND every mandatory safety/security gate passed. Rubrics require independently verifiable evidence and a recoverable failed-case demonstration.

## 8. Teaching boundaries, outstanding work and approval notes

Only Sections A–B have ten documented lab designs in the source. C–G labs are proposed briefs requiring learner guides, expected results, failure cases, model solutions and rubrics before claiming full assessability. The DVE101-00 setup gate is Pass/Retry and not a summative grade.

Instructional slide copy, lecturer notes, lab instructions, answer keys, grading rubrics and tool-version baseline still require pilot validation and institutional review. Planned briefs do not prove labs have been executed.

**Source:** Beacon Innovation Hub, *Applied DevOps Engineering: Institutional Curriculum, Setup-First Delivery Plan & Technical Audit*, document BIH-CURR-DEVOPS-001, v1.2 dated 17 November 2026, module DVE101. The original names, hours, prerequisites and assessable section outcomes are preserved; the LO numbering and repository presentation are editorial adaptations.

**Ownership clarification:** The source identifies Beacon Innovation Hub as proposed programme owner. Inclusion in the RISA Curricular repository supports curriculum development; it does not establish RISA programme ownership, academic approval, accreditation, NQF level or credit allocation.

---

*RISA Institution of Applied Sciences — Curriculum Development Draft*
