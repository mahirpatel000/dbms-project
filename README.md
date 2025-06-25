# dbms-project

#  Driving License Management System – DBMS Project

This project is a database-backed system designed to manage the entire lifecycle of driving license issuance. Built as part of an academic course, it covers conceptual design, relational schema, DDL creation, normalization, and sample data population.


---

##  Project Features

- **User Registration** (Admin / Applicant)
- **License Application** and multiple license types
- **Vehicle Information Management**
- **Test Scheduling & Results**
- **License Issuance & Renewal**
- **Payment Management**

---

##  Database Design

- **ER Diagram** (not included in repo, but designed in project)
- **9 Tables** designed with proper normalization up to 3NF:
  - `Applicant`
  - `LicenseType`
  - `Vehicle`
  - `License`
  - `Test`
  - `TestSchedule`
  - `User`
  - `Payment`
  - `Renewal`

Each table includes **primary keys**, **foreign keys**, **constraints**, and **referential integrity rules**.

---

##  Project Structure

- `DDL.pdf`: Initial table creation statements  
- `Normalized DDL Statements.pdf`: Final normalized version of DDL  
- `TABLES.pdf`: Sample data (INSERT statements) for all tables  
- ER diagram and functional dependencies (available offline)

---

##  Technologies Used

- **MySQL**
- ER Modeling Tools (e.g., Draw.io)
- SQL (DDL, DML)
- Normalization & Schema Design Principles

---

##  How to Run

1. Import the DDL statements from `Normalized DDL Statements.pdf` in your SQL environment.
2. Insert data using queries from `TABLES.pdf`.
3. You can run `SELECT`, `JOIN`, `UPDATE`, and other queries to test various workflows (like test result updates, renewal date changes, etc.)


