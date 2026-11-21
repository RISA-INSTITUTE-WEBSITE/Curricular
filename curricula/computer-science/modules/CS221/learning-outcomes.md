# CS221 — Database

**Institution:** RISA Institution of Applied Sciences  
**Discipline:** Computer Science  
**Module code:** CS221  
**Module title:** Database  
**Level:** Second-year / 200-level  
**Document:** Proposed module learning outcomes  
**Status:** Draft — pending academic review  
**Version:** 0.1  
**Date:** 21 November 2026

## 1. Module purpose

This module develops the ability to design, implement, query and maintain small relational databases. Students connect data modelling and SQL with integrity, transaction handling and introductory performance considerations.

**Curriculum alignment:** The RISA concept overview lists SQL, database design, relational models, transactions and indexing. Entity-relationship models, normalization, security and practical SQL exercises are proposed details to operationalize those areas.

## 2. Proposed module learning outcomes

**Upon successful completion of CS221, students should be able to:**

| Code | Learning outcome |
| --- | --- |
| **LO1** | Explain the purpose of a database management system and distinguish relational databases from files used for ad hoc data storage. |
| **LO2** | Interpret and construct conceptual entity-relationship models from stated data requirements, identifying entities, attributes and relationships. |
| **LO3** | Translate a conceptual model into a relational schema using primary keys, foreign keys, relationships and integrity constraints. |
| **LO4** | Apply functional dependencies and introductory normalization up to third normal form (3NF) to improve schema design. |
| **LO5** | Create and modify database structures using SQL DDL and enforce essential data integrity rules. |
| **LO6** | Insert, update, delete and retrieve data using SQL DML with correct filtering, ordering and aggregate functions. |
| **LO7** | Write multi-table SQL queries using appropriate joins, grouping and subqueries to answer specified questions. |
| **LO8** | Explain transaction properties and use commit and rollback operations to maintain consistent data during updates. |
| **LO9** | Explain the purpose and trade-offs of indexes and inspect simple query plans or observations to compare query performance. |
| **LO10** | Develop, test and document a small relational database solution, including a schema, representative SQL queries, access controls or secure-query practices and evidence of validation. |

## 3. Learning outcomes by teaching section

### Section A — Data Modelling and Relational Design

**Mapped outcomes:** LO1, LO2, LO3, LO4

**Content focus:**
- DBMS purposes and basic terminology
- Entity-relationship models and cardinality
- Relational schemas, keys and constraints
- Functional dependencies and normalization through 3NF

### Section B — SQL, Transactions and Indexing

**Mapped outcomes:** LO5, LO6, LO7, LO8, LO9

**Content focus:**
- CREATE/ALTER and integrity constraints
- INSERT, UPDATE, DELETE and SELECT
- JOIN, GROUP BY, HAVING, subqueries and aggregates
- Transactions, ACID concepts, COMMIT and ROLLBACK
- Indexes and introductory query-performance inspection

### Section C — Integrated Database Practical Project

**Mapped outcomes:** LO10; integrates LO1–LO9

**Content focus:**
- Requirements to ER design to working schema
- Test data and documented query demonstrations
- Validation, backup awareness and basic secure access practices

## 4. Suggested practical learning and assessment activities

These activities are **proposals**, not a finalized assessment specification.

| Practical activity | Outcomes assessed |
| --- | --- |
| Compare spreadsheet/file storage with a DBMS for a small record system. | LO1 |
| Draw an ER model for a lending, enrolment or inventory scenario. | LO2 |
| Map the model into tables with primary and foreign key constraints. | LO3, LO5 |
| Normalize a sample relation to 3NF and justify each step. | LO4 |
| Create tables and perform CRUD queries with sample data. | LO5, LO6 |
| Write reports using joins, filters, grouping and aggregates. | LO7 |
| Demonstrate successful commits and rollbacks inside transactions. | LO8 |
| Compare a selected query with and without a suitable index. | LO9 |
| Submit a documented relational database mini-project with test evidence. | LO10 |

## 5. Recommended teaching boundaries

- **Database model:** Use a relational DBMS and SQL as the main teaching platform. Choose one supported engine before teaching; SQL dialect differences should be made explicit.
- **Progression:** CS102 programming helps with logical reasoning, but the core work should be database design and SQL rather than building a full-stack application.
- **Depth:** Cover normalization through 3NF and introductory indexing/transaction control; reserve distributed databases, advanced tuning and production administration for later study.
- **Integrity and privacy:** Use synthetic test records, parameterized queries where applicable and least-privilege database accounts in labs.

## 6. Curriculum development and approval notes

The curriculum team should determine and approve:

- Select database engine, lab tools and backup/recovery arrangements.
- Define scope of SQL syntax/dialect and required normalization level.
- Set practical datasets, assessment rubrics and integrity/security safeguards.
- Determine credit value, prerequisites and academic approval.
- Assessment weightings, contact hours, prerequisites and institutional approval status.

**Source and development basis:** Original RISA concept overview: SQL, database design, relational models, transactions and indexing. Detailed topics, examples and performance/security activities are newly proposed.

---

*RISA Institution of Applied Sciences — Curriculum Development Draft*
