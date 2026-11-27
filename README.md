# RISA Curricular

**Curriculum development, updates, and change management for RISA Institution of Applied Sciences.**

> *Where real learning starts from hands-on work.*

## Purpose

This repository is the central workspace for **building, refining, reviewing, and tracking changes to RISA curricula**. It records how programmes, modules, syllabi, learning outcomes, and practical learning requirements evolve over time.

It is a **living curriculum development repository**, not simply a collection of finalized course materials. Proposals and revisions should remain traceable so contributors can understand what changed, why it changed, and how the change affects teaching and learning.

## Available curriculum drafts

- [Computer Science](curricula/computer-science/README.md) — eight proposed foundation modules and learning outcomes.
- [Cloud & DevOps](curricula/Cloud%20%26%20DevOps/README.md) — five-module Applied DevOps Engineering programme (BIH source v1.2; pending institutional approval).
- [Ethical Hacking (COMS)](curricula/ethical-hacking/README.md) — five proposed modules (COMS101–COMS105), including **COMS102 — Linux Basics for Cybersecurity**; draft pending academic and safety review.

- [Applied Physics](curricula/physics/README.md) — three-level course family with 21 independent modules and 12 career-oriented pathways; curriculum design pending academic review.

## What belongs here

- **Curriculum design:** programme structures, module lists, prerequisites, learning pathways, and progression.
- **Syllabus development:** topics, learning outcomes, required knowledge, practical activities, and assessment approaches.
- **Curriculum updates:** additions, removals, corrections, restructuring, and modernization of existing content.
- **Change records:** the motivation for each revision, its scope, supporting references, and its approval history.
- **Quality reviews:** checks for academic coherence, applied-science relevance, accessibility, and alignment with industry needs.

## Curriculum development principles

RISA aims to connect foundational scientific understanding with practical application. Curriculum proposals should:

1. **Start with clear outcomes.** Describe what learners should know and be able to do.
2. **Build sound foundations.** Progress logically from prerequisites to advanced topics.
3. **Prioritize hands-on learning.** Include experiments, projects, tools, simulations, or real-world problems where appropriate.
4. **Connect theory and practice.** Explain why concepts matter in scientific, engineering, or industrial contexts.
5. **Support evidence-based updates.** Reference academic benchmarks, technical standards, industry practices, or learner feedback where relevant.
6. **Remain maintainable.** Use consistent formats, clear terminology, and a transparent revision history.

## Suggested repository organization

As the collection grows, curricula may be organized by discipline and supported by shared review documentation:

```text
Curricular/
├── README.md
├── curricula/
│   ├── mathematics/
│   ├── physics/
│   ├── computer-science/
│   ├── ethical-hacking/
│   └── engineering/
├── templates/
└── change-log/
```

*This is a proposed layout; directories will be added as curriculum work begins.*

## Proposing and reviewing changes

To make curriculum decisions transparent and reviewable:

1. **Open an issue** describing the curriculum need, problem, or proposed improvement.
2. **Create a working branch** for the proposal (for example, `curriculum/physics-measurement-update`).
3. **Edit the relevant files** using existing templates and consistent module naming.
4. **Open a pull request** that explains the rationale and expected impact.
5. **Request a review** for academic quality, prerequisite alignment, practical relevance, and consistency with related modules.
6. **Merge after approval** and document significant curriculum decisions or version changes.

For a substantial change, a pull request should answer:

- **What changed?** Programmes, modules, topics, outcomes, or assessments affected.
- **Why?** Evidence, gaps, learner needs, or industry developments motivating the change.
- **What is the impact?** Prerequisites, sequencing, contact time, resources, or other modules affected.
- **How was it checked?** References, comparisons, stakeholder review, or validation performed.

> These are intended working practices. Automated checks and mandatory branch protections should be configured separately as the repository matures.

## Versioning and change history

Git history preserves file-level edits; issues and pull requests provide the discussion and reasoning behind them. For major curriculum revisions, include a readable summary in the relevant programme documentation or a dedicated change log, noting the date, affected modules, decision, and rationale.

Distinguish **draft**, **under review**, and **approved** curriculum material clearly in the documentation. Do not assume a document is institutionally approved simply because it has been merged.

## Scope

This repository focuses on **curriculum planning and change control**. Detailed lesson delivery assets, videos, student submissions, and website application code may be maintained separately and linked when relevant.

---

**RISA Institution of Applied Sciences** — *Where real learning starts from hands-on work.*
