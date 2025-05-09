# YMCA Database Management System

This project models a comprehensive database system for a community organization like the YMCA, capturing its operations across camps, classes, volunteers, facilities, and participant management.

Developed as part of a group project for a Database Management Systems course, I led the design and implementation— creating the ER diagram and writing the majority of the SQL schema, data population, and queries.

---

## Features

- Models summer camps, holiday camps, classes (group, private, certification), and participants
- Tracks volunteers, instructors, staff, and facilities
- Includes guardian info, payment methods, medical history, and more
- Designed with normalized relational schema and clear entity relationships

---

## Repository Structure

| File | Description |
|------|-------------|
| `er-diagram.png` | Visual entity-relationship diagram of the full schema |
| `create.sql`     | SQL statements to create all tables and relationships |
| `insert.sql`     | Example data to populate the tables |
| `query.sql`      | Sample SQL queries to demonstrate joins, filters, and relationships |

---

## How to Use

To recreate the database from scratch:

```bash
mysql -u your_username -p your_database_name < create.sql
mysql -u your_username -p your_database_name < insert.sql
mysql -u your_username -p your_database_name < query.sql
