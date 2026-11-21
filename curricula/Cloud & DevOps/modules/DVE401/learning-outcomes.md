# DVE401 — Container Orchestration and Reliability Engineering

**Repository:** RISA Institution of Applied Sciences — Curricular
**Discipline:** Cloud & DevOps
**Module code:** DVE401
**Module title:** Container Orchestration and Reliability Engineering
**Proposed duration:** 8 teaching weeks · 96 notional learning hours · programme weeks 28–35
**Document:** Draft module learning outcomes, syllabus and practical requirements
**Status:** Draft — pending technical pilot and institutional academic approval
**Version:** 0.1 (adapted from BIH source curriculum v1.2)
**Date:** 21 November 2026

## 1. Module purpose

Deploy and maintain Kubernetes workloads, collect actionable operational telemetry and demonstrate secure failure diagnosis, rollback and recovery.

## 2. Entry requirements and progression

**Mandatory:** DVE101 and DVE201 passed or approved equivalent: Linux/networking, Docker image/container operation, YAML, Git and functional CI/CD foundations.

**Recommended/corequisites:** DVE301 is useful for cloud-hosted clusters but not mandatory for local Kubernetes. Monitoring concepts are taught in the module.

Approved, documented practical equivalence may substitute for prerequisites where indicated by the programme policy; attendance alone does not prove competence.

## 3. Proposed module learning outcomes

**Upon successful completion of DVE401, learners should be able to:**

| Code | Outcome | Source section |
| --- | --- | --- |
| **LO1** | Inspect cluster health and explain core components. | A |
| **LO2** | Maintain desired workload state. | B |
| **LO3** | Publish, update and roll back an application. | C |
| **LO4** | Collect and interpret operational evidence. | D |
| **LO5** | Diagnose and recover a controlled service incident. | E |

These outcomes reproduce the assessable section outcomes in the source curriculum. The competency assessment must demonstrate them through independent evidence.

## 4. Teaching-section alignment and proposed hours

| Section | Syllabus focus | Core content | Hours |
| --- | --- | --- | ---: |
| **A — Kubernetes Architecture** | Inspect cluster health and explain core components. | Control plane, nodes, cluster API, scheduler, etcd, kubectl and namespaces. | 16 |
| **B — Workload Management** | Maintain desired workload state. | Pods, Deployments, ReplicaSets, resource requests/limits, ConfigMaps, Secrets and security contexts. | 20 |
| **C — Networking, Storage and Rollouts** | Publish, update and roll back an application. | Services, DNS, Ingress, persistent volumes, probes, scaling and rollout history. | 22 |
| **D — Monitoring and Observability** | Collect and interpret operational evidence. | Metrics, logs, traces, Prometheus, Grafana, alerts and SLI/SLO fundamentals. | 20 |
| **E — Reliability, Security and Incident Response** | Diagnose and recover a controlled service incident. | RBAC, failures, capacity, backups, rollback, root cause and recovery tests. | 14 |

**Proposed workload allocation:** A 16 · B 20 · C 22 · D 20 · E 14 · final assessment 4.

## 5. Setup-first laboratory readiness

The source prescribes Prepare → Verify → Explain → Demonstrate → Practise → Assess. Setup readiness is **Pass/Retry**, with support/retesting, and is distinct from summative marks. Setup time fits within the section hours above.

| Section | Environment setup | Pass/Retry readiness evidence |
| --- | --- | --- |
| A | Install kubectl and approved bounded local/hosted cluster; configure contexts and access. | Verify cluster-info and current context. |
| B | Provide namespace, limited permissions, image registry and quotas. | Deploy bounded workload; verify Pod state and limits. |
| C | Verify cluster network, storage class, probes and rollout history. | Access test Service and restore earlier Deployment revision. |
| D | Provide metrics/log access and safe monitoring stack or hosted alternative. | Query a metric and view a representative dashboard. |
| E | Inject only approved namespace-scoped faults and define recovery/cleanup. | Demonstrate alert, diagnosis, recovery and retained evidence. |

## 6. Practical activities and assessment evidence

| Reference | Planned practical / deliverable |
| --- | --- |
| M4-L01 | Inspect a resource-bounded Kubernetes cluster. |
| M4-L02 | Deploy, update, scale and roll back a workload. |
| M4-L03 | Configure Service, probes, configuration and persistent storage. |
| M4-L04 | Build an operational dashboard and alert using representative data. |
| M4-L05 | Investigate broken workload, restore operation and publish incident report. |

## 7. Module exit assessment

Operate a non-production Kubernetes workload with tested probes, a monitoring signal and verified failure recovery. Distinguish application readiness from mere process running.

**Evidence required:** Kubernetes manifests, kubectl output, image identifiers, dashboard capture/export, incident timeline, cause, mitigation and recovery verification.

**Assessment standard (proposed):** overall mark at least 70% AND every mandatory safety/security gate passed. Rubrics require independently verifiable evidence and a recoverable failed-case demonstration.

## 8. Teaching boundaries, outstanding work and approval notes

For constrained 8 GB laptops use a resource-limited cluster or staged/hosted observability. Do not require simultaneous local Kubernetes, Jenkins and full monitoring stacks.

Instructional slide copy, lecturer notes, lab instructions, answer keys, grading rubrics and tool-version baseline still require pilot validation and institutional review. Planned briefs do not prove labs have been executed.

**Source:** Beacon Innovation Hub, *Applied DevOps Engineering: Institutional Curriculum, Setup-First Delivery Plan & Technical Audit*, document BIH-CURR-DEVOPS-001, v1.2 dated 17 November 2026, module DVE401. The original names, hours, prerequisites and assessable section outcomes are preserved; the LO numbering and repository presentation are editorial adaptations.

**Ownership clarification:** The source identifies Beacon Innovation Hub as proposed programme owner. Inclusion in the RISA Curricular repository supports curriculum development; it does not establish RISA programme ownership, academic approval, accreditation, NQF level or credit allocation.

---

*RISA Institution of Applied Sciences — Curriculum Development Draft*
