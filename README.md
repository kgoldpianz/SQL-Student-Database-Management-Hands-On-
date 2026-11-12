# SQL-Student-Database-Management
SQL Server database script creating a student database and populating student records with basic demographic and course details.

## Project Overview
This project sets up a lightweight educational database (`Techcrush1`) to track student profiles, including unique IDs, names, ages, and course identifiers. It is also a beginner-friendly SQL Server script designed to create a custom database, define a student table schema, and insert sample student records.

## Database Schema Structure
* **`Student1`:** Stores individual student records with the following attributes:
  * `StudentID` (Primary Key, Integer)
  * `Name` (Student's first/display name, Varchar)
  * `Age` (Integer)
  * `CourseID` (Integer representing enrolled course)

## Key SQL Operations Included
* **Database Creation:** Utilizes `CREATE DATABASE` to initialize a fresh environment (`Techcrush1`).
* **Table Definition:** Establishes relational table structure with `PRIMARY KEY` constraints.
* **Data Population:** Inserts multiple student records using `INSERT INTO`.

## Tools & Skills Used
* **SQL Server (T-SQL):** Database initialization, table structuring, primary key constraints, and bulk data insertion.

## Conclusion
This script provides a clean foundational template for managing student records within SQL Server. By utilizing core Data Definition Language (DDL) and Data Manipulation Language (DML) commands, it establishes a reliable starting point for tracking student enrollments and demographics.
