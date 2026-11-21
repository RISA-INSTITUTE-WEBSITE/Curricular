# Applied DevOps Engineering Programme — Concept and Delivery Overview

**Discipline:** Cloud & DevOps  
**Location:** RISA Institution of Applied Sciences — Curricular repository  
**Source:** Beacon Innovation Hub (BIH), BIH-CURR-DEVOPS-001, v1.2 (17 November 2026)  
**Status:** Draft / internal technical and pilot review; not an approved programme or accredited qualification  
**Repository adaptation:** 21 November 2026

## Programme concept

A five-module applied pathway from Linux and collaborative computing through CI/CD, Docker, cloud infrastructure, Terraform, Ansible, Kubernetes and an integrated non-production engineering capstone. The source's intended audience is entry-level and developing practitioners with basic computer literacy.

**Source provenance:** BIH is the proposed programme owner in the PDF; RISA is the repository in which the draft is now catalogued. Transferring, authorizing or awarding the programme at RISA remains an institutional decision, not an assumption of this repository change.

## Proposed teaching order

| Order | Module | Title | Sections | Weeks | Programme weeks | Hours |
| --- | --- | --- | --- | ---: | --- | ---: |
| 1 | [DVE101](modules/DVE101/learning-outcomes.md) | DevOps Systems and Collaborative Computing Foundations | 7 | 11 | 1–11 | 132 |
| 2 | [DVE201](modules/DVE201/learning-outcomes.md) | Continuous Delivery and Container Systems Engineering | 5 | 8 | 12–19 | 96 |
| 3 | [DVE301](modules/DVE301/learning-outcomes.md) | Cloud Infrastructure and Configuration Automation | 5 | 8 | 20–27 | 96 |
| 4 | [DVE401](modules/DVE401/learning-outcomes.md) | Container Orchestration and Reliability Engineering | 5 | 8 | 28–35 | 96 |
| 5 | [DVE501](modules/DVE501/learning-outcomes.md) | Integrated DevOps Engineering Capstone | 6 | 5 | 36–40 | 60 |
| **Total** | | | **28** | **40** | | **480** |

The standard teaching plan is **40 teaching weeks × 12 hours/week = 480 proposed notional learning hours**. An indicative standard week includes 3 hours guided explanation, 6 supervised practical hours and 3 independent evidence hours. Alternative schedules (30 weeks × 16 hours; 24 weeks × 20 hours) require screening and pilot verification. Holidays, outages and retakes are excluded.

**This time allocation is NOT an assignment of South African academic credits or NQF level.**

## Programme-level learning outcomes

1. Administer Linux environments and troubleshoot filesystem, identity, process, package and service problems.
2. Use networking, shell automation, Git workflows and configuration formats to support reproducible operations.
3. Design CI/CD workflows and create, test and operate containerized applications.
4. Provision and configure infrastructure using cloud services, Terraform and Ansible under security and cost controls.
5. Deploy and troubleshoot workloads on Kubernetes and collect actionable operational telemetry.
6. Demonstrate incident response, safe recovery, documented architecture choices and end-to-end integration.

## Dependency logic

- **DVE101:** basic computing literacy, ability to use a terminal and files.
- **DVE201:** DVE101 or independently assessed equivalent foundations.
- **DVE301:** DVE101 or equivalent Linux/network/SSH/IAM/Git/Bash and application validation; DVE201 is recommended, not mandatory.
- **DVE401:** DVE101 + DVE201 (or equivalent Docker/CI/CD foundations); DVE301 recommended for cloud-hosted clusters, not mandatory for local Kubernetes.
- **DVE501:** verified DVE101–DVE401 outcomes or documented equivalence challenge.

Prior-learning equivalence must include learner identity, repository/lab evidence, a supervised practical challenge, assessor comments, score and mandatory security gates.

## Setup-first teaching

Every technical section includes **Prepare → Verify → Explain → Demonstrate → Practise → Assess**. Environment checks are Pass/Retry, supported by instructor remediation, not automatically graded failures. Setup consumes existing planned teaching hours rather than adding weeks. Learner slides, lecturer notes and lab/assessment packs remain separate teaching artifacts.

## Programme completion conditions (proposed)

At least **70% per module** PLUS all mandatory safety/security/recovery gates, with independent verification of actual practical evidence. Completion recognition is internal and conditional on institutional approval, not accredited qualification status.

## Delivery boundaries

- Teach introductory-to-intermediate applied competence, not autonomous production-level mastery of every tool.
- Supply a small maintained training application and build/test bridge ahead of DVE201.
- Require cloud sandbox ownership, cost ceiling, cost alerts and teardown policy before DVE301 labs.
- Use disposable/hosted or staged environments where 8 GB learner devices cannot run Kubernetes, Jenkins and monitoring simultaneously.
- Scope DVE501 to one non-production application and reuse previous tested work.

See [Assessment and delivery framework](assessment-and-delivery-framework.md) and [Curriculum audit and approval gates](curriculum-review-and-audit.md).

**Source:** PDF pp. 1–6 and 17–19; the source's internal programme owner and review status are intentionally retained.
