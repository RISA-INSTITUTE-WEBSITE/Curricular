# CS201 — Data Structures & Algorithms

**Institution:** RISA Institution of Applied Sciences  
**Discipline:** Computer Science  
**Module code:** CS201  
**Module title:** Data Structures & Algorithms  
**Level:** Second-year / 200-level  
**Document:** Proposed module learning outcomes  
**Status:** Draft — pending academic review  
**Version:** 0.1  
**Date:** 21 November 2026

## 1. Module purpose

This module develops students’ ability to model computational problems, choose suitable data structures, design and implement correct algorithms, and evaluate their time and space efficiency. Python 3 is the suggested implementation language to build on CS102.

**Curriculum alignment:** The original concept overview specifies searching, sorting, graph algorithms, dynamic programming and complexity analysis. The revised module title adds data structures; the data-structure topics below are proposed extensions, not claims about the original handwritten notes.

## 2. Proposed module learning outcomes

**Upon successful completion of CS201, students should be able to:**

| Code | Learning outcome |
| --- | --- |
| **LO1** | Explain abstract data types, common data-structure operations and algorithm correctness, and distinguish an interface from an implementation. |
| **LO2** | Use asymptotic notation (Big O, and introductory Θ and Ω) to estimate the time and auxiliary-space complexity of simple algorithms. |
| **LO3** | Implement, test and compare linear collections, including arrays or Python lists, linked lists, stacks and queues, for appropriate problems. |
| **LO4** | Explain and implement introductory tree and hash-table operations, and select suitable structures using performance and storage considerations. |
| **LO5** | Implement and compare fundamental searching techniques, including linear search and binary search, stating their assumptions and complexity. |
| **LO6** | Implement, trace and compare representative sorting algorithms and reason about time complexity and stability. |
| **LO7** | Model problems with graphs and implement introductory traversal algorithms such as breadth-first and depth-first search. |
| **LO8** | Apply recursion and introductory dynamic programming to solve well-scoped problems, explaining overlapping subproblems where relevant. |
| **LO9** | Select and justify suitable combinations of data structures and algorithms for small realistic problems, considering input size and constraints. |
| **LO10** | Develop, test and document a Python solution that demonstrates correctness on representative and edge cases and reports basic performance findings. |

## 3. Learning outcomes by teaching section

### Section A — Data Structures and Complexity Foundations

**Mapped outcomes:** LO1, LO2, LO3, LO4

**Content focus:**
- Abstract data types, operations and invariants
- Runtime and memory growth; Big O and introductory Θ/Ω
- Lists or arrays, linked lists, stacks and queues
- Trees, hash tables and trade-offs between structures

### Section B — Algorithmic Techniques

**Mapped outcomes:** LO5, LO6, LO7, LO8

**Content focus:**
- Linear and binary search with preconditions
- Sorting, correctness, complexity and stability
- Graph representation and BFS/DFS traversal
- Recursion and introductory memoization/tabulation

### Section C — Selection, Analysis and Integrated Practical Work

**Mapped outcomes:** LO9, LO10; integrates LO1–LO8

**Content focus:**
- Problem decomposition and structure selection
- Edge-case tests and simple timing measurements
- Documented Python implementation and performance comparison

## 4. Suggested practical learning and assessment activities

These activities are **proposals**, not a finalized assessment specification.

| Practical activity | Outcomes assessed |
| --- | --- |
| Implement a stack and a queue and use them to solve simple tasks. | LO1, LO3 |
| Count basic operations and estimate complexity for small pseudocode examples. | LO2 |
| Compare a linked list with a Python list for a defined access or insertion task. | LO3, LO9 |
| Build a simple search index using a dictionary and explain hash-based lookup. | LO4, LO9 |
| Trace binary search and implement it with input-condition checks. | LO5, LO10 |
| Compare insertion sort and merge sort on supplied datasets. | LO2, LO6, LO10 |
| Represent a graph and use BFS/DFS to find reachable nodes. | LO7 |
| Solve a small problem recursively and with memoization; discuss repeated work. | LO8 |
| Complete a tested Python mini-project, such as a route explorer or task scheduler. | LO9, LO10 |

## 5. Recommended teaching boundaries

- **Relationship with CS102:** Students should already be comfortable with Python control flow, functions and built-in collections; this module develops implementation and analysis rather than reteaching Python basics.
- **Formal analysis:** Require clear reasoning about simple asymptotic bounds, but leave advanced proof techniques and in-depth algorithmic theory to later study.
- **Graph and dynamic programming scope:** Start with small graphs and straightforward recurrences before introducing specialized optimization algorithms.
- **Practical emphasis:** Assess correctness, data-structure choice, time/space trade-offs and thoughtful tests, not code memorization.

## 6. Curriculum development and approval notes

The curriculum team should determine and approve:

- Select an implementation language and development environment (Python 3 proposed).
- Determine prerequisites, credits, contact hours and mathematical preparation.
- Define required algorithm set, performance-testing scale and grading rubrics.
- Approve practical/project requirements and academic integrity measures.
- Assessment weightings, contact hours, prerequisites and institutional approval status.

**Source and development basis:** Original RISA concept overview: searching, sorting, graph algorithms, dynamic programming and complexity analysis. Data structures, concrete implementations, sample activities and outcome wording are new proposals.

---

*RISA Institution of Applied Sciences — Curriculum Development Draft*
