# SQL Practice – Foreign Key Relationships

## Introduction

This section covers the implementation of foreign key relationships using a naval shipping database example. The database contains boat information and details of the crew members assigned to each boat.

## Database Structure

Two tables are used:

- **boats:** Stores boat details.
- **crew_members:** Stores crew member information along with the boat ID.

The relationship between these tables is one-to-many, where a single boat can be associated with multiple crew members.

## Tasks Completed

1. Created the boats table.
2. Added sample boat records.
3. Created the crew_members table.
4. Established a foreign key reference using `boat_id`.
5. Added crew member records.
6. Used a SELECT query with a WHERE condition to retrieve crew members belonging to boat ID 1.

## SQL Topics Covered

- CREATE TABLE
- PRIMARY KEY
- FOREIGN KEY
- REFERENCES
- INSERT INTO
- SELECT
- WHERE

## Tools

- PostgreSQL
- SQL
- GitHub

## Outcome

Practised implementing referential relationships between tables and retrieving associated data using SQL.
