# Library_schema_task1
# 📚 Library Management System - SQL Schema Design

## 🧩 Task Overview

This project is part of **Task 1: Database Setup and Schema Design** for the SQL Developer Internship.  
It involves designing a well-structured and normalized relational database schema using MySQL Workbench.

---

## 💻 Domain Chosen: Library Management System

### Key Features:
- Tracks books, authors, categories, members, and loans.
- Demonstrates one-to-many and many-to-many relationships.
- Enforces data integrity using foreign keys and constraints.

---

## 🔧 Database Tables & Relationships

### Tables Created:
- `Authors`
- `Categories`
- `Books`
- `BookAuthors` (join table)
- `Members`
- `Loans`

### Relationships:
- One book can have many authors (Many-to-Many via BookAuthors).
- Each book belongs to one category (One-to-Many).
- Members can borrow many books (One-to-Many).
- Each loan links one member to one book.

---

## 🗂️ Files Included
- `schema.sql` – SQL script to create all tables and relationships.
- `README.md` – This file.

---

## 🛠️ Tools Used
- MySQL Workbench
- GitHub
  



