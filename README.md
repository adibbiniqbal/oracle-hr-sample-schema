# Oracle HR Sample Schema for Oracle Database

Easily set up the official Oracle HR (Human Resources) sample schema in your Oracle database — perfect for learning, testing SQL queries, or demonstrating features.

This repo contains a set of SQL scripts designed to:
- Create the `HR` user and schema
- Set up all required tables
- Populate the tables with sample data
- Add indexes and comments

---

## ✅ Prerequisites

- A running Oracle database (e.g., [set it up using this guide](https://github.com/adibbiniqbal/oracle19c-docker-mac-apple-silicon/))
- A SQL client like [Oracle SQL Developer](https://www.oracle.com/database/sqldeveloper/) or [VS Code](https://code.visualstudio.com/) with the [Oracle SQL Developer Extension for VS Code](https://marketplace.visualstudio.com/items?itemName=Oracle.sql-developer)

---

## 📦 How to Set Up the HR Schema

Follow these steps to create the HR sample schema in your Oracle pluggable database (PDB):


1. Download the SQL files in this repository, using either the Git commands or manually downloading them (view file > raw > save as).
```bash
git clone https://github.com/adibbiniqbal/oracle-hr-sample-schema
```
2. Open an IDE (e.g. Oracle SQL Developer) and connect to your container database.
3. Login as SYS AS SYSDBA and run script 01, which creates the new HR user and grants the necessary privileges.
4. Connect to the database as the new HR user.
5. Run script 02 to create the tables.
6. Run script 03 to populate the tables with sample data.
7. Run script 04 to create indexes and add comments.


The schema is now set up!

## 🔐 Oracle HR User Login Details:

Username: HR  
Password: hr  
Host: localhost  
Port: 1521  
Service Name: orclpdb1

## ERD

Here's the ERD of the HR schema used:
![ERD - Oracle HR Schema](https://user-images.githubusercontent.com/9577031/120085247-c9dd5180-c119-11eb-8d06-d8cfd5a1a60f.png)
