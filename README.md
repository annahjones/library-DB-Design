# 📘 Library Management System & 🧾 Task Manager CRUD API

This repository contains two parts:

1. **Question 1:** A fully-featured MySQL relational database system for a Library Management System.
2. **Question 2:** A Task Manager CRUD API built with Node.js and Express, connected to a MySQL database.

---

## 📚 Question 1: Library Management System (MySQL)

### 📄 Description

This is a structured relational database designed for managing a library's operations. It contains tables for:

- Books
- Authors
- Members
- Loans
- Categories
- Publishers

The schema uses appropriate constraints such as `PRIMARY KEY`, `FOREIGN KEY`, `UNIQUE`, and `NOT NULL`. It also demonstrates different relationship types (1-to-1, 1-to-many, many-to-many where applicable).

---

### ⚙️ How to Run

1. Open MySQL Workbench or your preferred MySQL tool.
2. Run the script:

```sql
SOURCE Question1_LibraryDB.sql;

