# final-sql
Complete Database Management System – Library Management System 📚
Project Overview
This project is a relational database system designed to manage a library’s books, members, and loans using MySQL. It ensures organized record-keeping, tracking book availability, and enforcing borrowing rules.

Objectives ✅
Design a structured relational database

Implement tables with constraints (PK, FK, NOT NULL, UNIQUE)

Establish relationships (1-1, 1-M, M-M) between entities

Ensure data integrity and efficient retrieval

Database Schema 🗂️
Tables & Relationships
Books (book_id, title, author, isbn, published_year)

Members (member_id, name, email, phone)

Loans (loan_id, member_id, book_id, loan_date, return_date)

Relationships:

Books ↔ Loans (1-M: A book can have multiple loans)

Members ↔ Loans (1-M: A member can borrow multiple books)

How to Run/Setup the Database ⚙️
1️⃣ Install MySQL and open the terminal. 2️⃣ Import the database script:

sql
SOURCE library_db.sql;
3️⃣ Verify the tables are created:

sql
SHOW TABLES;
4️⃣ Run queries to test relationships (e.g., checking borrowed books).

ERD Screenshot 📌
The Entity-Relationship Diagram (ERD) for this database system illustrates the connections between members, books, and loans. It includes:

Primary Keys (PK) in each table.

Foreign Keys (FK) linking Loans to Members and Books.

Relationships between entities.

![image](https://github.com/user-attachments/assets/da526938-a58b-49a3-938f-ccc854fd3879)
