# ElevateLabs_Task2
This task focuses on mastering essential SQL operations for data insertion and cleanup in a relational database. It involves creating a library management schema, inserting sample data, handling missing values using NULL, and performing update/delete operations with proper WHERE clauses.


## 🏁 Objective
Practice inserting, updating, and deleting data.
Handling missing values using NULL.
---

## 🛠 Tools
- MySQL Workbench

---

## 📂 Deliverables

`Task2.sql`: A complete SQL file containing:
  - Table creation with primary and foreign key constraints
  - INSERT statements to populate tables with sample data
  - UPDATE and DELETE operations
  - NULL value handling examples

---

## 🧭 Guide
1. Use `INSERT INTO` to add sample data into each table.
2. Insert `NULL` explicitly where data is missing (e.g., unknown join dates or publication years).
3. Use `UPDATE` with `WHERE` to modify specific rows (e.g., filling in missing dates).
4. Use `DELETE` with `WHERE` to safely remove data without violating foreign key constraints.
5. Ensure referential integrity when deleting data from related tables.

---

## 📑 File Description 

The SQL script includes:

- **Schema setup**:
  - Tables: `Authors`, `Categories`, `Books`, `BookAuthors`, `Members`, `BorrowRecords`
  - Relationships via foreign keys

- **Data insertion**:
  - Populates all tables with example data
  - Includes `NULL` values for fields like `birth_year`, `published_year`, `join_date`, and `return_date`

- **NULL handling**:
  - Queries to find and update missing `join_date` and `published_year`

- **Cleanup operations**:
  - Deletes records with `NULL` `return_date`
  - Removes "Author Unknown" and related records

---

## ✅ Outcome: A populated database with clean and consistent data.
---

