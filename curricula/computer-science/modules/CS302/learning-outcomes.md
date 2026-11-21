# CS302 — Artificial Intelligence

**Institution:** RISA Institution of Applied Sciences  
**Discipline:** Computer Science  
**Module code:** CS302  
**Module title:** Artificial Intelligence  
**Level:** Third-year / 300-level  
**Document:** Proposed module learning outcomes  
**Status:** Draft — pending academic review  
**Version:** 0.1  
**Date:** 21 November 2026

## 1. Module purpose

This module introduces students to major approaches for building systems that perform intelligent tasks, including state-space search, knowledge representation and machine learning. Students implement and evaluate small AI solutions while recognising data limitations, ethical risks and appropriate human oversight.

**Curriculum alignment:** The RISA concept overview explicitly identifies search, knowledge representation, machine learning and neural networks. The dataset, evaluation, ethics and practical development details below are proposed extensions.

## 2. Proposed module learning outcomes

**Upon successful completion of CS302, students should be able to:**

| Code | Learning outcome |
| --- | --- |
| **LO1** | Explain key concepts, application areas and limitations of artificial intelligence, distinguishing rule-based approaches from data-driven learning. |
| **LO2** | Formulate small problems as state spaces and implement introductory uninformed search methods such as breadth-first and depth-first search. |
| **LO3** | Explain and apply introductory heuristic search, including a well-scoped example of best-first or A* search. |
| **LO4** | Represent simple knowledge using facts, rules or propositional logic and perform elementary inference. |
| **LO5** | Distinguish supervised, unsupervised and reinforcement learning, and identify suitable approaches for clearly defined tasks. |
| **LO6** | Prepare small datasets using basic cleaning, feature selection or encoding, and describe training, validation and test splits and the risk of data leakage. |
| **LO7** | Train and evaluate an introductory supervised classification or regression model using appropriate baseline measures and evaluation metrics. |
| **LO8** | Explain the structure and operation of a basic artificial neural network, including inputs, weights, activation and learning at a conceptual level. |
| **LO9** | Identify bias, privacy, explainability, robustness and societal risks in an AI use case and propose appropriate mitigation or oversight measures. |
| **LO10** | Implement, document and critically evaluate a small reproducible AI project, comparing results against a simple baseline and explaining its limitations. |

## 3. Learning outcomes by teaching section

### Section A — AI Foundations, Search and Knowledge Representation

**Mapped outcomes:** LO1, LO2, LO3, LO4

**Content focus:**
- AI definitions, symbolic and statistical approaches
- State-space representations, BFS/DFS
- Heuristics and introductory A* or best-first search
- Facts, propositional rules and elementary inference

### Section B — Machine Learning and Neural Networks

**Mapped outcomes:** LO5, LO6, LO7, LO8

**Content focus:**
- Learning paradigms and problem suitability
- Dataset quality, preprocessing, splitting and leakage
- Supervised baselines, classification/regression and evaluation
- Neural-network inputs, weights, activations and conceptual training

### Section C — Responsible AI and Integrated Practical Work

**Mapped outcomes:** LO9, LO10; integrates LO1–LO8

**Content focus:**
- Bias, explainability, security/privacy and human oversight
- Reproducible experiments and baseline comparison
- Documented limitations, findings and responsible-use review

## 4. Suggested practical learning and assessment activities

These activities are **proposals**, not a finalized assessment specification.

| Practical activity | Outcomes assessed |
| --- | --- |
| Classify example problems by AI approach and identify important limitations. | LO1 |
| Model a small maze or route graph and compare breadth-first and depth-first search. | LO2 |
| Use an elementary admissible heuristic in an A* search demonstration. | LO3 |
| Represent a small rule set and demonstrate a logical inference. | LO4 |
| Match example tasks to supervised, unsupervised or reinforcement learning. | LO5 |
| Prepare a small public or synthetic dataset and document split decisions. | LO6 |
| Train and assess a simple classifier or regressor against a baseline. | LO7 |
| Diagram a basic neural network and trace an illustrative forward computation. | LO8 |
| Evaluate an AI scenario for fairness, privacy and oversight concerns. | LO9 |
| Deliver a reproducible mini-project with metrics, limitations and an ethical review. | LO6–LO10 |

## 5. Recommended teaching boundaries

- **Preparation:** Students should have programming experience and basic mathematical foundations (including discrete mathematics and elementary probability/statistics); formal prerequisites remain to be decided.
- **Tools:** Python 3 and accessible educational libraries may be used, but specific libraries and version requirements must be selected by the curriculum team.
- **Scope:** Build small, interpretable examples before large neural models. Avoid requiring cloud expenditure, expensive GPUs or massive datasets.
- **Evaluation:** Separate training from held-out evaluation; prefer transparent baselines and careful reporting over unsupported performance claims.
- **Responsible AI:** Require documentation of data sources, limitations, privacy and potential harms in the project.

## 6. Curriculum development and approval notes

The curriculum team should determine and approve:

- Set expected mathematics/statistics preparation and baseline coding skills.
- Choose supported Python tools, offline datasets and compute requirements.
- Define assessment rubrics for search, reasoning, modelling and ethical analysis.
- Confirm credits, academic level, contact hours and institutional approval.
- Assessment weightings, contact hours, prerequisites and institutional approval status.

**Source and development basis:** The RISA overview lists search, knowledge representation, machine learning and neural networks. The proposed pedagogic sequence, evaluation methods and responsible-AI activities extend that outline.

---

*RISA Institution of Applied Sciences — Curriculum Development Draft*
