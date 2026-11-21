# Curriculum Review, Open Issues and Approval Gates

**Source:** Beacon Innovation Hub, BIH-CURR-DEVOPS-001 v1.2 (17 November 2026), pp. 19–23.  
**Repository status:** Draft planning material; no RISA/BIH institutional approval claimed.

## Source document register

- Programme name: *Applied DevOps Engineering Programme*
- Source title: *Institutional Curriculum, Setup-First Delivery Plan & Technical Audit*
- Document code: BIH-CURR-DEVOPS-001
- Version: **1.2**, dated **17 November 2026**
- Proposed ownership in source: Beacon Innovation Hub
- Scope: 5 modules, 28 sections, 40 weeks, 480 proposed hours
- Academic credits, NQF level, accreditation, award approval: **not assigned**
- Version history: v1.0 (07 November 2026), v1.1 (08 November 2026), v1.2 (17 November 2026)

## Outstanding technical and instructional actions

| ID (source) | Required review or evidence |
| --- | --- |
| F01/F08 | Pilot and formally approve pacing; do not convert proposed hours to credits or award claims. |
| F02/A05/A14 | Finalize, execute and moderate DVE101 Sections C–G lab manuals; verify earlier A/B designs. |
| F03/A15 | Maintain one test application and a short CI build/test bridge for DVE201. |
| F04 | Keep Jenkins teaching focused on declarative pipeline, agents, credentials, artifacts and recovery. |
| F05/A16 | Test cloud/cluster cost, security and low-memory fallbacks. |
| F06 | Keep capstone to a single small reusable non-production application. |
| F07/A06/A07/A23 | Convert lab briefs to executable instructions, negative cases, model answers and independently moderated rubrics. |
| F09/A12 | Pin software versions, verify technical commands and review vendor references. |
| F10/A18/A19 | Pilot DVE101-00 (all eight parts) and the A1–A8 sequence, checking the 3–4-hour onboarding allowance. |
| F11/A20/A21 | Publish approved setup and Pass/Retry readiness checks for every module section. |
| F12 | Separate student slide copy, lecturer notes, checkpoints and practical packs. |
| A03 | Approve prerequisite equivalence/challenge assessment procedure. |
| A09/A10 | Adopt lab safety, credential, use, hardware and cloud-budget policies. |
| A11/A22 | Approve moderation, appeals, accessibility and non-summative setup rules. |
| A24 | Confirm all setup activities fit inside the existing 480-hour proposed programme. |

The audit in the source describes internal consistency and pilot feasibility, **not** completed classroom validation or accreditation.

## Suggested approval workflow (from source)

1. Technical reviewers verify topic coverage and feasibility of assessment.
2. Curriculum owner accepts/revises module codes, prerequisites and outcomes.
3. Quality lead authorizes rubrics, lab safety, moderation and evidence-retention.
4. Programme owner authorizes resources, budget and award wording.
5. Pilot cohort executes labs; the results inform a new documented release.

**Reviewer signatures in the source are intentionally blank**. Repository merge is not one of these approvals.

## Vendor reference set identified by the source

- GitHub Actions Concepts: https://docs.github.com/en/actions/concepts
- Docker: https://docs.docker.com/
- Jenkins Pipeline: https://www.jenkins.io/doc/book/pipeline/
- Terraform language and state: https://developer.hashicorp.com/terraform/language
- Ansible playbooks: https://docs.ansible.com/ansible/latest/playbook_guide/playbooks_intro.html
- Kubernetes concepts: https://kubernetes.io/docs/concepts/
- Prometheus: https://prometheus.io/docs/
- Windows WSL: https://learn.microsoft.com/windows/wsl/install
- VS Code WSL: https://code.visualstudio.com/docs/remote/wsl
- Fedora: https://docs.fedoraproject.org/
- systemd: https://systemd.io/

References are a starting point for tool scope and terminology; tested lab version baselines and local institutional validation remain outstanding.
