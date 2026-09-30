# Object Relational Database Systems (ORDBMS) — Seminar Presentation

An 18-slide seminar presentation on **Object Relational Database Systems (ORDBMS)** — how the relational model was extended with object-oriented concepts to handle complex, real-world data, with SQL examples throughout.

# Overview

Traditional relational databases (RDBMS) store data as simple rows and columns, which works well for business data but struggles with complex applications (CAD, multimedia, spatial data, etc.). This presentation walks through **why** and **how** the relational model was enhanced with object-oriented features to solve this — resulting in the Object Relational Database System (ORDBMS).

#  Slide-by-Slide Contents

| # | Slide |
|---|---|
| 1 | Title — Object Relational Database Systems |
| 2 | Roadmap — what the seminar covers |
| 3 | Why Plain RDBMS Falls Short (complex apps, multi-valued attributes, no custom types, unnatural inheritance) |
| 4 | What is an ORDBMS? — definition, OODBMS vs. ORDBMS build paths |
| 5 | ORDBMS Products You'll Recognise (Oracle 8, DB2 UDB, Informix, Ingres II, Sybase, UniSQL) |
| 6 | Why Did ORDBMS Emerge? — with real examples (medical imaging systems, digital libraries) |
| 7 | Advantages of ORDBMS (reuse, sharing, easy migration, SQL's strength) |
| 8 | Disadvantages of ORDBMS |
| 9 | Characteristics of ORDBMS (nested relations, complex types, querying, complex object creation) |
| 10 | Representing a Complex Type: **Address** — side-by-side RDBMS vs. ORDBMS comparison with SQL, sample data tables, and tree diagrams |
| 11 | Querying a Composite Attribute — using the whole type vs. dot notation |
| 12 | Structured Types in ORDBMS — methods, `FINAL` / `NOT FINAL`, worked `Date.difference()` example |
| 13 | Type Inheritance (`UNDER`) & Table Inheritance (`OF ... UNDER`) — University-person → Student/Staff example |
| 14 | Collection Data Types — `ARRAY` vs. `MULTISET`, with a `Book`/library example and `UNNEST` queries |
| 15 | Object Identity — Referencing Objects with `REF ... SCOPE` (system-generated vs. user-generated) |
| 16 | ORDBMS vs. OODBMS — quick comparison table |
| 17 | Summary & Key Terms — takeaways and glossary (ADT, UDT, BLOB/CLOB, REF, SCOPE) |
| 18 | Thank You |

#  Audience

Designed for a database management systems (DBMS) course seminar — suitable for both a classroom presentation and self-study/exam revision.

# Files

| File | Description |
|---|---|
| `ORDBMS.pptx` | Full slide deck (PowerPoint) |

# Built With

- SQL code examples (standard SQL-99 / object-relational extensions: `CREATE TYPE`, `CREATE TABLE ... OF ... UNDER`, `ARRAY`, `MULTISET`, `REF ... SCOPE`)
- Diagrams: type hierarchies, tree structures for nested attributes (e.g. the `Address` example)

#  Sources

Compiled and adapted from DBMS coursework on Object Relational and Extended Relational Databases, with additional real-world examples (medical imaging, digital libraries).
