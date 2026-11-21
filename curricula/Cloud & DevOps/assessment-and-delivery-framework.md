# Assessment, Setup-First Teaching and Lab Delivery

**Status:** Proposed / unapproved · **Source:** BIH-CURR-DEVOPS-001 v1.2, pp. 6, 18–19 and 22

## Setup-first instructional sequence

| Stage | Instructor provides | Expected record |
| --- | --- | --- |
| 1. Prepare | Compatible OS/hardware, authorized accounts, safe workspace, software baseline | Approved environment and support route |
| 2. Verify | Versions, tool reachability, permissions, safe negative test | Pass/Retry readiness (not automatically a summative grade) |
| 3. Explain | Short student slides and separate detailed lecturer explanation | Knowledge checkpoint |
| 4. Demonstrate | Instructor-led commands, workflow outputs, risk interpretation | Expected results and variation notes |
| 5. Practise | Isolated learner lab with successful and failing cases | Independently verifiable state/artifacts |
| 6. Assess | Unassisted task, rubric, feedback and moderation | Score, safety gates and remediation path |

Each lesson packet contains (1) concise Canva student slide (heading, 3–6 ideas, a few commands and a takeaway), (2) detailed lecturer notes with examples, common errors and prompts, and (3) a lab/assessment pack specifying prerequisites, setup, inputs, expected states, failure cases, answers and rubric.

## Proposed rubric

| Domain | Weight | Evidence |
| --- | ---: | --- |
| Practical implementation | 40% | Working configuration/code and executed results |
| Troubleshooting and recovery | 25% | Introduced fault, diagnosis, fix and verification |
| Technical understanding | 15% | Clear oral/written explanation |
| Security and operational practice | 10% | Least privilege, secrets safety, change control, cleanup |
| Documentation and teaching | 10% | Runbook, diagrams, reproducible instructions |
| **Total** | **100%** | |

**Pass:** overall at least 70% **and** all required security/safety/recovery gates. Exposed credentials, unauthorized production actions, unsafe destructive changes or failed mandatory recovery require remediation regardless of overall mark.

## Evidence and checkpoints

- **Setup verification:** record approved environment, tools/versions, test commands, accessibility support; Pass/Retry with assistance and retesting.
- **Knowledge checkpoint:** formative by default, unless its weighting is explicitly adopted in the approved assessment plan.
- **Practical laboratory:** provide unique learner lab/repository ID, environment specification, individual artifact, independent test evidence and safety checklist; a self-reported CI badge alone is insufficient.
- **Final module assessment:** time-bounded practical, technical explanation, evidence archive, named assessor/moderator, score, appeal and reassessment route.
- **Every module:** capture an intentionally failing case with expected vs actual results, security/cost reviews when relevant and teardown/recovery evidence.

Assessors must independently reproduce or verify outcomes; published scoring rules, learner-specific submission identity, moderation and an appeal process are required. Isolate student-run code from LMS/assessor credentials.

## Proposed module-hour allocation

| Module | Sections / assessment breakdown | Total |
| --- | --- | ---: |
| DVE101 | A 28 · B 20 · C 18 · D 20 · E 12 · F 22 · G 8 · final assessment 4. | 132 |
| DVE201 | A 22 · B 18 · C 16 · D 24 · E 12 · final assessment 4. | 96 |
| DVE301 | A 14 · B 18 · C 28 · D 22 · E 10 · final assessment 4. | 96 |
| DVE401 | A 16 · B 20 · C 22 · D 20 · E 14 · final assessment 4. | 96 |
| DVE501 | A 8 · B 12 · C 12 · D 12 · E 10 · F (technical defence) 6; no separately added assessment hours. | 60 |
| **Total** | **40 weeks at standard pace** | **480** |

The DVE101-00 onboarding lesson takes 3–4 of Section A's 28 hours. All other setup gates are also **inside** existing section allocations.

## Infrastructure and accessibility

- Avoid excessive local RAM demand: stagger labs, use hosted CI, disposable remote labs or bounded cluster.
- Validate WSL2/systemd/network assumptions; use disposable Fedora VM when conventional Linux boot, SELinux or firewall behavior is needed.
- Require pre-authorized non-production cloud tenants, ownership, budget caps/alerts and teardown confirmation.
- Use least-privilege access, scoped or short-lived credentials and logs sanitized of secrets.
- Pin instructor-validated tool versions and update practical instructions as vendors change.
- Provide equivalent native Linux/remote labs and accommodations; a setup failure alone is not a failed technical competency.

## Institutional decisions still required

Instructor/assessor qualifications, independent moderation, retention and appeal policies, assessment platform controls, cost budget, hardware fallback, safe-use policy and formal award wording. This file is an assessment design, **not a validated learning management or proctoring implementation**.
