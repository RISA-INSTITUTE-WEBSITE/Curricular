# DVE301 — Cloud Infrastructure and Configuration Automation

**Repository:** RISA Institution of Applied Sciences — Curricular
**Discipline:** Cloud & DevOps
**Module code:** DVE301
**Module title:** Cloud Infrastructure and Configuration Automation
**Proposed duration:** 8 teaching weeks · 96 notional learning hours · programme weeks 20–27
**Document:** Draft module learning outcomes, syllabus and practical requirements
**Status:** Draft — pending technical pilot and institutional academic approval
**Version:** 0.1 (adapted from BIH source curriculum v1.2)
**Date:** 21 November 2026

## 1. Module purpose

Provision isolated infrastructure through declarative code, configure hosts with automation and verify repeatability, change control, security and cost safeguards.

## 2. Entry requirements and progression

**Mandatory:** DVE101 or equivalent Linux, networking, SSH, IAM basics, Git and Bash competency, plus ability to test an application or host configuration.

**Recommended/corequisites:** DVE201 recommended for integrating build artifacts and pipelines; previous cloud, Terraform or Ansible expertise is not required.

Approved, documented practical equivalence may substitute for prerequisites where indicated by the programme policy; attendance alone does not prove competence.

## 3. Proposed module learning outcomes

**Upon successful completion of DVE301, learners should be able to:**

| Code | Outcome | Source section |
| --- | --- | --- |
| **LO1** | Explain and select a bounded lab architecture. | A |
| **LO2** | Design and justify minimum required access. | B |
| **LO3** | Provision infrastructure from reviewed code. | C |
| **LO4** | Configure a Linux host repeatably. | D |
| **LO5** | Demonstrate reproducibility and safe removal. | E |

These outcomes reproduce the assessable section outcomes in the source curriculum. The competency assessment must demonstrate them through independent evidence.

## 4. Teaching-section alignment and proposed hours

| Section | Syllabus focus | Core content | Hours |
| --- | --- | --- | ---: |
| **A — Cloud Platform Concepts** | Explain and select a bounded lab architecture. | Service models, regions, availability, compute, storage, billing and resilient infrastructure basics. | 14 |
| **B — Cloud Networking, Identity and Security** | Design and justify minimum required access. | VPC/VNet, subnets, routing, security groups, IAM, keys and cost controls. | 18 |
| **C — Terraform Infrastructure as Code** | Provision infrastructure from reviewed code. | HCL, providers, resources, variables, outputs, state, plans, modules and destroy. | 28 |
| **D — Ansible Configuration Management** | Configure a Linux host repeatably. | Inventories, SSH, modules, playbooks, handlers, roles, templates and idempotence. | 22 |
| **E — Infrastructure Delivery and Recovery** | Demonstrate reproducibility and safe removal. | Integration, plans, drift checks, secrets, changes, validation, teardown and documentation. | 10 |

**Proposed workload allocation:** A 14 · B 18 · C 28 · D 22 · E 10 · final assessment 4.

## 5. Setup-first laboratory readiness

The source prescribes Prepare → Verify → Explain → Demonstrate → Practise → Assess. Setup readiness is **Pass/Retry**, with support/retesting, and is distinct from summative marks. Setup time fits within the section hours above.

| Section | Environment setup | Pass/Retry readiness evidence |
| --- | --- | --- |
| A | Provide approved cloud sandbox/local simulator with billing, resource ownership and teardown briefing. | Identify project/tenant, region, budget owner and teardown plan. |
| B | Provision scoped IAM identity, controlled network and access policy. | Prove least privilege and denied unauthorized action. |
| C | Install pinned Terraform CLI/provider with secure state and isolated backend. | terraform fmt/validate/plan passes; approval precedes apply. |
| D | Prepare inventory, authorized SSH, target Python compatibility and disposable hosts. | Check Ansible version and authorized connectivity/commands. |
| E | Link approved IaC and configuration; set health-check and cleanup evidence. | Repeat plan/apply safely, restore or destroy without orphaned resources. |

## 6. Practical activities and assessment evidence

| Reference | Planned practical / deliverable |
| --- | --- |
| M3-L01 | Cloud sandbox with scoped identity, budget alert and teardown plan. |
| M3-L02 | Isolated networking and security rules, provisioned and validated. |
| M3-L03 | Terraform init, validate, plan, apply and secure state handling. |
| M3-L04 | Ansible playbook and second-run idempotence evidence. |
| M3-L05 | Integrated provisioning, configuration, health verification and safe destroy. |

## 7. Module exit assessment

Deliver isolated server infrastructure with Terraform and Ansible, show application availability, justify IAM/cost choices, capture state and idempotence evidence, and remove resources safely.

**Evidence required:** Terraform code and approved plan, state-management design, Ansible playbooks/logs, access evidence, diagram, usage budget and destroy confirmation.

**Assessment standard (proposed):** overall mark at least 70% AND every mandatory safety/security gate passed. Rubrics require independently verifiable evidence and a recoverable failed-case demonstration.

## 8. Teaching boundaries, outstanding work and approval notes

Cloud labs require named ownership, approved cost ceiling, cost alerts and teardown checklist *before* any provisioning. DVE201 is recommended but is not a mandatory prerequisite for this module.

Instructional slide copy, lecturer notes, lab instructions, answer keys, grading rubrics and tool-version baseline still require pilot validation and institutional review. Planned briefs do not prove labs have been executed.

**Source:** Beacon Innovation Hub, *Applied DevOps Engineering: Institutional Curriculum, Setup-First Delivery Plan & Technical Audit*, document BIH-CURR-DEVOPS-001, v1.2 dated 17 November 2026, module DVE301. The original names, hours, prerequisites and assessable section outcomes are preserved; the LO numbering and repository presentation are editorial adaptations.

**Ownership clarification:** The source identifies Beacon Innovation Hub as proposed programme owner. Inclusion in the RISA Curricular repository supports curriculum development; it does not establish RISA programme ownership, academic approval, accreditation, NQF level or credit allocation.

---

*RISA Institution of Applied Sciences — Curriculum Development Draft*
