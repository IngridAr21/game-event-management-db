# Game Event Management System
### MySQL · SQLAlchemy · Neo4j · Python

An end-to-end database system for managing an MMORPG game world, covering the full data engineering lifecycle — from schema design and data wrangling to advanced analytics and graph databases.

Built as a 5-week project at Maastricht University (2023).

---

## What this project covers

**Database Design** — Designed a normalized relational schema from scratch with 13 interconnected tables (players, guilds, quests, items, combat, economy, chat...), including primary keys, foreign keys, and composite constraints.

**Data Wrangling & Loading** — Built a Python ingestion pipeline to parse messy, semi-structured JSON data: handled null values, type mismatches, duplicates, and referential integrity violations using SQLAlchemy ORM.

**Real-Time Chat** — Extended the schema with a chat system (one-on-one and group), implemented using SQL triggers and stored procedures, with a socket-based server/client interface in Python.

**Advanced SQL Analytics** — Wrote 15+ complex queries using CTEs, window functions, and subqueries covering fraud detection, economy analysis, player retention, and quest performance.

**Graph Database (Neo4j)** — Migrated relationship-heavy data to Neo4j and wrote Cypher queries for social graph analysis: shortest friendship paths, mutual connections, and quest participation networks.

---

## Tech Stack

- **Databases**: MySQL, Neo4j
- **ORM**: SQLAlchemy
- **Language**: Python (pandas, json, uuid, sockets)
- **Concepts**: ERD design, ETL pipelines, data cleaning, stored procedures, triggers, graph queries

---
