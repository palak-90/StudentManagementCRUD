# 🎓 Student Management CRUD Application (Java + JDBC + MySQL)

A **console-based CRUD (Create, Read, Update, Delete) application** built using **Java, JDBC, and MySQL**.  
This project demonstrates database connectivity in Java using JDBC and performs CRUD operations on student records stored in a MySQL database.  

---

## ✨ Features
- ➕ Add Student (Insert into database)  
- 📋 View Students (Fetch records from database)  
- ✏️ Update Student (Modify existing records)  
- ❌ Delete Student (Remove student record by ID)  

---

## 🛠️ Tech Stack
- **Java (Core Java)**  
- **JDBC (Java Database Connectivity)**  
- **MySQL (Database)**  

---

## 🗄️ Database Setup

Run the following SQL commands in MySQL:

```sql
CREATE DATABASE studentdb;

USE studentdb;

CREATE TABLE students (
    id INT PRIMARY KEY,
    name VARCHAR(100),
    age INT,
    course VARCHAR(100)
);
