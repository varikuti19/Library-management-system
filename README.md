# Library Management System (SQL Internship Task 1)

## 📌 Overview
This project is a simple database schema for a Library Management System.  
It allows storing Authors, Books, Members, and Borrowing Records.

## 📚 Entities
- Authors → Stores details of book authors  
- Books → Stores details of books in the library  
- Members → Stores details of library members  
- Loans → Stores which member borrowed which book  

## 🔗 Relationships
- One Author → Many Books  
- One Book → Many Loans  
- One Member → Many Loans  

## 📂 Files
- `schema.sql` → SQL script to create the schema  
- `er_diagram.png` → ER diagram (visual)  

## 🛠 Tools Used
- MySQL Workbench / SQLite / pgAdmin
