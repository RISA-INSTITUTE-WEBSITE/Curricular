# CS102 — Programming Fundamentals (Python)

**Institution:** RISA Institution of Applied Sciences  
**Discipline:** Computer Science  
**Module code:** CS102  
**Module title:** Programming Fundamentals  
**Primary programming language:** Python 3  
**Level:** First-year (introductory / 100-level)  
**Document:** Proposed module learning outcomes  
**Status:** Draft — pending academic review  
**Version:** 0.1  
**Date:** 21 November 2026

## 1. Module purpose

This introductory module develops students' ability to solve simple computational problems by designing, writing, running, testing and debugging programs in **Python 3**. Students learn fundamental programming concepts, control flow, reusable functions, built-in data collections and basic file processing through hands-on practice.

CS102 builds on the computational foundations established in **CS101 — Computer Architecture & Data Representation** and prepares students for **CS201 — Data Structures & Algorithms**.

The original curriculum concept overview identified *syntax, semantics, compilation and interpretation* as foundational programming-language topics. This proposal retains that foundation while expanding CS102 into a practical Python programming module.

## 2. Proposed module learning outcomes

**Upon successful completion of CS102, students should be able to:**

| Code | Learning outcome |
| --- | --- |
| **LO1** | Explain fundamental programming concepts, including Python syntax and semantics, and describe at an introductory level the roles of source code, compilation and interpretation in program execution. |
| **LO2** | Use a Python 3 development environment to create, run and manage simple programs, and distinguish syntax, runtime and logic errors. |
| **LO3** | Declare and manipulate variables and fundamental Python data types (`int`, `float`, `bool` and `str`), using operators, expressions and appropriate type conversions. |
| **LO4** | Develop interactive Python programs that accept user input and produce correctly formatted output, including basic input validation. |
| **LO5** | Implement decision-making using Boolean expressions and conditional statements (`if`, `elif` and `else`) to solve clearly defined problems. |
| **LO6** | Construct and trace iterative solutions using `for` and `while` loops, and explain loop conditions, iteration and termination. |
| **LO7** | Define, call and test reusable Python functions using parameters, return values and appropriate variable scope. |
| **LO8** | Select and apply Python's built-in collections—lists, tuples, dictionaries and sets—to organize and process small sets of data. |
| **LO9** | Read and write simple text files and apply basic exception handling to manage predictable input and file-processing errors. |
| **LO10** | Design, implement, debug and test a small modular Python program that meets given requirements, using problem decomposition, clear documentation and representative test cases. |

## 3. Learning outcomes by teaching section

### Section A — Python Fundamentals and Development Environment

**Mapped outcomes:** LO1, LO2, LO3, LO4

**Content focus:**
- What a program is; syntax versus semantics
- Source code, execution and introductory compilation/interpreter concepts
- Python 3 installation or access to a preconfigured environment, an editor/IDE, interactive shell and script execution
- Variables, assignment, `int`, `float`, `bool`, `str` and type conversion
- Arithmetic, comparison and logical operators
- Input, output, f-strings and introductory input validation
- Distinguishing syntax, runtime and logic errors

### Section B — Control Flow and Functions

**Mapped outcomes:** LO5, LO6, LO7

**Content focus:**
- Boolean expressions and conditional selection: `if`, `elif`, `else`
- Iteration: `for`, `while`, `range()` and loop termination
- Tracing and checking program flow
- Function definitions, calls, parameters, arguments and return values
- Local and global variable scope at an introductory level
- Simple function documentation and testing

### Section C — Collections, Files and Integrated Practical Work

**Mapped outcomes:** LO8, LO9, LO10, drawing on LO1–LO7

**Content focus:**
- Strings and the built-in collections: lists, tuples, dictionaries and sets
- Indexing, iteration and appropriate collection selection
- Reading and writing plain-text files, including `with` for file handling
- Basic `try`/`except` error handling
- Problem decomposition, simple pseudocode and test-case design
- Debugging, readable code, and a small integrated Python project

## 4. Suggested practical learning and assessment activities

The following are **proposed** activities to demonstrate the outcomes; they do not prescribe a finalized assessment scheme.

| Practical activity | Outcomes assessed |
| --- | --- |
| Run short Python commands in the interactive shell, then create a script; identify and correct example errors. | LO1, LO2 |
| Build a simple measurement or currency-independent calculator using variables, operators and type conversion. | LO3 |
| Create a program that collects input, validates a numeric value and formats a result. | LO3, LO4 |
| Implement a grade classifier or eligibility checker using conditional statements. | LO5 |
| Build and trace a loop-based totals, counting or number-pattern exercise. | LO6 |
| Refactor a small calculator into reusable functions and test different inputs. | LO7, LO10 |
| Maintain a small set of student or inventory records using lists and dictionaries; compare alternative collection types. | LO8 |
| Read and write a small plain-text data file and handle a missing-file or invalid-input condition. | LO9 |
| Complete an integrated mini-project, such as a command-line quiz or expense tracker, with functions, collections, validation and documented test cases. | LO3–LO10 |

## 5. Recommended teaching boundaries

- **Language:** Use **Python 3** consistently for teaching, laboratories and foundational programming assessments. The precise Python 3 minor version and approved development tools should be selected by the institution.
- **Progression from CS101:** Assume conceptual familiarity with computer hardware and binary data representation, but **do not assume prior programming experience**.
- **Preparation for CS201:** Teach built-in collection use and basic problem solving here; reserve formal data-structure implementations, advanced algorithm design and complexity analysis for **CS201 — Data Structures & Algorithms**.
- **Practical emphasis:** Students should write, execute, trace, debug and test their own small programs, not only explain definitions.
- **Depth:** Advanced object-oriented design, GUI or web frameworks, concurrency, external APIs, complex package management and specialized libraries are outside this introductory proposal unless formally added later.
- **Execution terminology:** Avoid the oversimplification that Python is *only* interpreted. For example, common CPython execution involves compilation to bytecode and execution by a virtual machine; internal implementation details need only be introduced conceptually at this level.

## 6. Curriculum development and approval notes

These learning outcomes are **proposals**, not approved module requirements. The curriculum team should still determine:

- Credits, duration, contact hours and weekly teaching sequence
- Prerequisites and any formal relationship between CS101 and CS102
- Assessment instruments, weights, rubrics and integrity controls for programming submissions
- Minimum hardware, offline-capable Python 3 setup, editor/IDE and accessibility support
- Practical lab arrangements, academic support and assessment resit policies
- Expected standards for code readability, documentation, collaboration and independent work
- Academic review and formal approval status

**Source and development basis:** The eight-module RISA Computer Science teaching order and the original introductory Programming Languages topics (syntax, semantics, compilation, interpretation) are already documented in the repository. The additional Python-specific outcomes, practical activities and suggested teaching boundaries above are **new curriculum proposals** developed for CS102 on 21 November 2026.

---

*RISA Institution of Applied Sciences — Curriculum Development Draft*
