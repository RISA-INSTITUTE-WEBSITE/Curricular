# DVE201 — Continuous Delivery and Container Systems Engineering

**Repository:** RISA Institution of Applied Sciences — Curricular
**Discipline:** Cloud & DevOps
**Module code:** DVE201
**Module title:** Continuous Delivery and Container Systems Engineering
**Proposed duration:** 8 teaching weeks · 96 notional learning hours · programme weeks 12–19
**Document:** Draft module learning outcomes, syllabus and practical requirements
**Status:** Draft — pending technical pilot and institutional academic approval
**Version:** 0.1 (adapted from BIH source curriculum v1.2)
**Date:** 21 November 2026

## 1. Module purpose

Design controlled CI/CD pipelines and reproducible container images, and compare GitHub Actions and Jenkins within testable non-production release workflows.

## 2. Entry requirements and progression

**Mandatory:** DVE101 passed or approved equivalent demonstrating Linux, shell exit codes, networking, Git/GitHub, YAML and basic test concepts.

**Recommended/corequisites:** Basic Python or JavaScript application familiarity and introductory application security.

Approved, documented practical equivalence may substitute for prerequisites where indicated by the programme policy; attendance alone does not prove competence.

## 3. Proposed module learning outcomes

**Upon successful completion of DVE201, learners should be able to:**

| Code | Outcome | Source section |
| --- | --- | --- |
| **LO1** | Implement and diagnose an automated quality gate. | A |
| **LO2** | Build, run and inspect a container image. | B |
| **LO3** | Operate a small reproducible multi-service application. | C |
| **LO4** | Develop a version-controlled pipeline. | D |
| **LO5** | Prove release controls and safe recovery. | E |

These outcomes reproduce the assessable section outcomes in the source curriculum. The competency assessment must demonstrate them through independent evidence.

## 4. Teaching-section alignment and proposed hours

| Section | Syllabus focus | Core content | Hours |
| --- | --- | --- | ---: |
| **A — CI/CD Architecture and GitHub Actions** | Implement and diagnose an automated quality gate. | Events, jobs, runners, permissions, secrets, caches, artifacts and troubleshooting. | 22 |
| **B — Docker Fundamentals** | Build, run and inspect a container image. | Engine, images, containers, Dockerfiles, layers, tags, registries and image security basics. | 18 |
| **C — Docker Networking, Storage and Compose** | Operate a small reproducible multi-service application. | Port mapping, bridge networks, volumes, bind mounts, Compose and environment configuration. | 16 |
| **D — Jenkins Pipeline Engineering** | Develop a version-controlled pipeline. | Controller/agent architecture, Jenkinsfile, declarative pipelines, credentials, triggers and agents. | 24 |
| **E — Secure Delivery and Pipeline Operations** | Prove release controls and safe recovery. | Test gates, least privilege, artifact versioning, approvals, rollback and run observability. | 12 |

**Proposed workload allocation:** A 22 · B 18 · C 16 · D 24 · E 12 · final assessment 4.

## 5. Setup-first laboratory readiness

The source prescribes Prepare → Verify → Explain → Demonstrate → Practise → Assess. Setup readiness is **Pass/Retry**, with support/retesting, and is distinct from summative marks. Setup time fits within the section hours above.

| Section | Environment setup | Pass/Retry readiness evidence |
| --- | --- | --- |
| A | Provide private training repository, minimum permissions and verified runner/build commands. | Run a harmless workflow test and record logs. |
| B | Provide authorized Docker Engine/Desktop or hosted daemon, approved storage and test images. | Build and run a small image; verify daemon and disk budget. |
| C | Verify Compose, test networks and volumes, and safe localhost ports. | Run and stop a controlled two-service example. |
| D | Provide isolated Jenkins controller/agent, plugin baseline and non-production credentials. | Execute minimal Jenkinsfile and inspect logs. |
| E | Provide scoped secrets, registry access, approval gate and rollback fixture. | Show an unsafe deployment blocked and a recoverable release. |

## 6. Practical activities and assessment evidence

| Reference | Planned practical / deliverable |
| --- | --- |
| M2-L01 | GitHub Actions quality gate, including failing and corrected tests. |
| M2-L02 | Build and inspect Docker image logs, layers, permissions and container lifecycle. |
| M2-L03 | Compose application with bounded storage and documented ports. |
| M2-L04 | Jenkinsfile implementing build, test and package stages. |
| M2-L05 | Secrets handling, artifact promotion and pipeline failure diagnosis. |

## 7. Module exit assessment

A source change triggers automated tests and reproducible Docker build, then an approval-controlled non-production deployment with verification. Explain CI, continuous delivery and continuous deployment.

**Evidence required:** Workflow YAML, Jenkinsfile, Dockerfile and Compose files, test reports, image reference, passing/failing runs, deployment record and rollback notes.

**Assessment standard (proposed):** overall mark at least 70% AND every mandatory safety/security gate passed. Rubrics require independently verifiable evidence and a recoverable failed-case demonstration.

## 8. Teaching boundaries, outstanding work and approval notes

Provide a maintained simple training application and short build/test bridge. Jenkins scope should prioritize declarative pipelines, agents, credentials, artifacts and failure recovery rather than exhaustive plugins.

Instructional slide copy, lecturer notes, lab instructions, answer keys, grading rubrics and tool-version baseline still require pilot validation and institutional review. Planned briefs do not prove labs have been executed.

**Source:** Beacon Innovation Hub, *Applied DevOps Engineering: Institutional Curriculum, Setup-First Delivery Plan & Technical Audit*, document BIH-CURR-DEVOPS-001, v1.2 dated 17 November 2026, module DVE201. The original names, hours, prerequisites and assessable section outcomes are preserved; the LO numbering and repository presentation are editorial adaptations.

**Ownership clarification:** The source identifies Beacon Innovation Hub as proposed programme owner. Inclusion in the RISA Curricular repository supports curriculum development; it does not establish RISA programme ownership, academic approval, accreditation, NQF level or credit allocation.

---

*RISA Institution of Applied Sciences — Curriculum Development Draft*
