# DVE501 — Integrated DevOps Engineering Capstone

**Repository:** RISA Institution of Applied Sciences — Curricular
**Discipline:** Cloud & DevOps
**Module code:** DVE501
**Module title:** Integrated DevOps Engineering Capstone
**Proposed duration:** 5 teaching weeks · 60 notional learning hours · programme weeks 36–40
**Document:** Draft module learning outcomes, syllabus and practical requirements
**Status:** Draft — pending technical pilot and institutional academic approval
**Version:** 0.1 (adapted from BIH source curriculum v1.2)
**Date:** 21 November 2026

## 1. Module purpose

Integrate administration, delivery automation, infrastructure-as-code, orchestration and reliability into one auditable, non-production engineering solution.

## 2. Entry requirements and progression

**Mandatory:** DVE101, DVE201, DVE301 and DVE401 successfully assessed, or equivalence accepted through documented challenge assessments.

**Recommended/corequisites:** Team collaboration, project planning and documentation. A BIH Wall of Work representative application is suggested, not mandated.

Approved, documented practical equivalence may substitute for prerequisites where indicated by the programme policy; attendance alone does not prove competence.

## 3. Proposed module learning outcomes

**Upon successful completion of DVE501, learners should be able to:**

| Code | Outcome | Source section |
| --- | --- | --- |
| **LO1** | Defend a feasible design and acceptance criteria. | A |
| **LO2** | Deliver reproducible, secure infrastructure. | B |
| **LO3** | Demonstrate traceable build-to-deploy flow. | C |
| **LO4** | Run and observe the deployed application. | D |
| **LO5** | Recover against defined service objectives. | E |
| **LO6** | Demonstrate independent integration competency. | F |

These outcomes reproduce the assessable section outcomes in the source curriculum. The competency assessment must demonstrate them through independent evidence.

## 4. Teaching-section alignment and proposed hours

| Section | Syllabus focus | Core content | Hours |
| --- | --- | --- | ---: |
| **A — Requirements and Solution Architecture** | Defend a feasible design and acceptance criteria. | User needs, non-functional requirements, architecture diagrams, threat/risk assumptions. | 8 |
| **B — Infrastructure Engineering** | Deliver reproducible, secure infrastructure. | Terraform, Ansible, secrets boundaries, IAM and environment validation. | 12 |
| **C — Automated Software Delivery** | Demonstrate traceable build-to-deploy flow. | Git, tests, CI/CD, container registry, versioning and release controls. | 12 |
| **D — Deployment and Platform Operations** | Run and observe the deployed application. | Kubernetes manifests, policies, availability and telemetry. | 12 |
| **E — Reliability and Incident Management** | Recover against defined service objectives. | Controlled faults, rollback, recovery, incident evidence and improvements. | 10 |
| **F — Final Technical Review** | Demonstrate independent integration competency. | Documentation, demonstration, code review, oral defence and handover. | 6 |

**Proposed workload allocation:** A 8 · B 12 · C 12 · D 12 · E 10 · F (technical defence) 6; no separately added assessment hours.

## 5. Setup-first laboratory readiness

The source prescribes Prepare → Verify → Explain → Demonstrate → Practise → Assess. Setup readiness is **Pass/Retry**, with support/retesting, and is distinct from summative marks. Setup time fits within the section hours above.

| Section | Environment setup | Pass/Retry readiness evidence |
| --- | --- | --- |
| A | Assign bounded brief, resource budget, non-production target and assessors. | Architecture and acceptance criteria approved. |
| B | Validate sandbox IAM, Terraform/Ansible access and state controls. | Reviewed infrastructure plan and isolation check. |
| C | Verify test suite, repository gates, registry and pipeline credentials. | Independent clean build and release trace available. |
| D | Validate Kubernetes context, namespace, monitoring and health endpoints. | Only authorized workload deployed and monitored. |
| E | Prepare controlled failure scenario and independent evaluation scripts. | Safe recovery and documented incident evidence. |
| F | Verify submission integrity, assessor access, rubric, demonstration backup and appeals. | Reproducible artifacts and defence appointment confirmed. |

## 6. Practical activities and assessment evidence

| Reference | Planned practical / deliverable |
| --- | --- |
| M5-D01 | Approved requirements and architecture pack. |
| M5-D02 | Reviewed infrastructure and configuration repository. |
| M5-D03 | CI/CD build, test, image and deployment evidence. |
| M5-D04 | Operational non-production application with monitoring evidence. |
| M5-D05 | Controlled incident, rollback and postmortem evidence. |
| M5-D06 | Final portfolio, operations runbook and technical presentation. |

## 7. Module exit assessment

Integration evaluation, live demonstration and independent technical defence with security, credential handling, recovery and teardown gates enforced independently of total score.

**Evidence required:** Version-controlled solution, architecture diagrams, tests, pipeline runs, infrastructure code, Kubernetes manifests, telemetry, runbooks, risk register, incident report and signed rubric.

**Assessment standard (proposed):** overall mark at least 70% AND every mandatory safety/security gate passed. Rubrics require independently verifiable evidence and a recoverable failed-case demonstration.

## 8. Teaching boundaries, outstanding work and approval notes

Reuse the tested infrastructure, pipelines and manifests built in earlier modules. Scope is one small training application, not a new production software product. Section F includes the final assessment.

Instructional slide copy, lecturer notes, lab instructions, answer keys, grading rubrics and tool-version baseline still require pilot validation and institutional review. Planned briefs do not prove labs have been executed.

**Source:** Beacon Innovation Hub, *Applied DevOps Engineering: Institutional Curriculum, Setup-First Delivery Plan & Technical Audit*, document BIH-CURR-DEVOPS-001, v1.2 dated 17 November 2026, module DVE501. The original names, hours, prerequisites and assessable section outcomes are preserved; the LO numbering and repository presentation are editorial adaptations.

**Ownership clarification:** The source identifies Beacon Innovation Hub as proposed programme owner. Inclusion in the RISA Curricular repository supports curriculum development; it does not establish RISA programme ownership, academic approval, accreditation, NQF level or credit allocation.

---

*RISA Institution of Applied Sciences — Curriculum Development Draft*
