## Oracle SQL Learning Journey

This is part of my ongoing Oracle SQL learning journey through IBCS-PRIMAX. I will upload my practice files and query outputs to GitHub as I continue learning.

All the files will contains the output generated using Oracle SQL*Plus while exploring the built-in HR (Human Resources) schema.

## File 01: Schema Tables and Data

**File:** `Schema_tables_data.LST`

This file contains Oracle SQL*Plus output exploring the built-in HR (Human Resources) schema, including the schema overview, table descriptions, and data retrieved from all tables using SELECT queries.

## File 02: SELECT Queries and SQL Expressions

**File:** `02_SELECT_Queries_and_Arithmetic_Operations.LST`

Topics covered:
- SELECT Queries
- Column Selection
- Arithmetic Expressions
- Column Aliases
- String concatenation (`||`)
- DISTINCT for Duplicate row 
- Column Formatting
- NULL Values
- UPDATE Statements

**All the practice commands are collected together at the end of the file for easy reference.**

## File 03: WHERE Conditions and Sorting

**File:** `03_WHERE_Conditions_and_Sorting.LST`

**Topics covered:**
- WHERE Clause
- Comparison Operators
- Logical Operators
- Equality and Inequality Conditions
- BETWEEN Operator
- LIKE Operator
- IN and NOT IN Operators
- ORDER BY Clause
- Ascending and Descending Order
- Sorting by Multiple Columns
- Filtering Records
- Substitution Variables
- Single Ampersand (`&`) Substitution Variables
- Double Ampersand (`&&`) Substitution Variables
- Row Limiting Clause

**All the practice commands are collected together at the end of the file for easy reference.**

## File 04: Oracle SQL Functions and Grouping

**File:** `04_Oracle_SQL_Functions_and_Grouping.LST`

**Topics covered:**
- Aggregate Functions (`SUM`, `COUNT`)
- Character Functions (`UPPER`, `LOWER`, `INITCAP`)
- String Functions (`CONCAT`, `SUBSTR`, `INSTR`, `LENGTH`)
- String Formatting (`LPAD`, `RPAD`)
- String Manipulation (`REPLACE`, `TRIM`)
- Numeric Functions (`ROUND`, `TRUNC`, `MOD`)
- Date Arithmetic
- Date Functions (`SYSDATE`, `CURRENT_DATE`, `MONTHS_BETWEEN`, `NEXT_DAY`)
- Date Formatting with `TO_CHAR`
- Grouping with `GROUP BY`
- Sorting Grouped Results with `ORDER BY`
- Oracle `DUAL` Table
- `USER` Function

**All the practice commands are collected together at the end of the file for easy reference.**

## File 05: Aggregate Functions, Grouping and Joins

**File:** `05_Aggregate_Functions_Grouping_and_Joins.LST`

**Topics covered:**
- Aggregate Functions (`SUM`,` AVG`, `COUNT`, `MAX`, `MIN`)
- DISTINCT with `Aggregate Functions`
- Handling NULL Values with `NVL`
- GROUP BY Clause
- Grouping by Multiple Columns
- `HAVING` Clause
- WHERE vs. HAVING
- Oracle Joins (Traditional Join Syntax)
- ANSI JOIN Syntax (`JOIN`, `ON`)
- Table Aliases
- Joining Multiple Tables
- Self Join
- Inner Join
- Left Outer Join
- Right Outer Join
- Full Outer Join
- Cross Join

**All the practice commands are collected together at the end of the file for easy reference.**

## File 06: Subqueries, Set Operators, DML and Transactions

**File:** `06_Subqueries_Set_Operators_DML_and_Transactions.LST`

**Topics covered:**

- Single-Row Subqueries
- Multiple-Row Subqueries
- Nested Subqueries
- Subqueries with Multiple Conditions
- Subqueries with Aggregate Functions (`MAX`, `SUM`)
- Subqueries in `HAVING` Clause
- `ANY` and `ALL` Operators
- Set Operators (`UNION`, `UNION ALL`, `INTERSECT`, `MINUS`)
- `DROP TABLE` Statement
- `CREATE TABLE` Statement
- `DESCRIBE` (`DESC`) Command
- `INSERT` Statement
- `INSERT` with Subquery
- Substitution Variables (`&`)
- `UPDATE` Statement
- `UPDATE` with Subqueries
- `DELETE` Statement
- `DELETE` with Subquery
- `CREATE TABLE AS SELECT` (`CTAS`)
- Transaction Control (`SAVEPOINT`, `ROLLBACK TO SAVEPOINT`)

**All the practice commands are collected together at the end of the file for easy reference.**

## File 07: Oracle DDL, Constraints, Data Dictionary and Views

**File:** `07_Oracle_DDL_Constraints_Data_Dictionary_and_Views.LST`

**Topics covered:**

- Table Creation (`CREATE TABLE`)
- Default Values (`DEFAULT`, `USER`, `SYSDATE`)
- Table Structure (`DESC`, `DESCRIBE`)
- Data Insertion (`INSERT INTO`, `VALUES`)
- Integrity Constraints
- Primary Key Constraint (`PRIMARY KEY`)
- Foreign Key Constraint (`FOREIGN KEY`, `REFERENCES`)
- Unique Constraint (`UNIQUE`)
- Not Null Constraint (`NOT NULL`)
- Check Constraint (`CHECK`, `BETWEEN`)
- Constraint Naming
- Constraint Modification (`ALTER TABLE`, `ADD CONSTRAINT`)
- Table Modification (`ADD`, `MODIFY`, `DROP COLUMN`)
- Constraint and Column Metadata (`USER_CONS_COLUMNS`)
- Table Metadata (`USER_TABLES`, `USER_TAB_COLUMNS`)
- Database Object Metadata (`USER_OBJECTS`, `ALL_OBJECTS`)
- Data Dictionary (`DICTIONARY`)
- Table Joins (Traditional Oracle Join Syntax)
- Create Table As Select (`CTAS`)
- Oracle Recycle Bin (`RECYCLEBIN`)
- Purge Operations (`PURGE`, `PURGE RECYCLEBIN`)
- Flashback Table (`FLASHBACK TABLE`, `TO BEFORE DROP`)
- View Creation (`CREATE OR REPLACE VIEW`)
- View Metadata (`USER_VIEWS`)
- Index Creation (`CREATE INDEX`)
- Sequence Management (`CREATE SEQUENCE`, `DROP SEQUENCE`, `NEXTVAL`, `CURRVAL`)
- Sequence Metadata (`USER_SEQUENCES`)
- Synonym Creation (`CREATE SYNONYM`)
- Synonym Metadata (`USER_SYNONYMS`)
- Querying View Definitions (`SELECT`, `TEXT`)

**All the practice commands are collected together at the end of the file for easy reference.**

## File 08: Oracle Advanced SQL, User Management and Data Integration

**File:** `08_Oracle_Advanced_SQL_User_Management_and_Data_Integration.LST`

**Topics covered:**

- External Tables (`ORGANIZATION EXTERNAL`, `ORACLE_LOADER`)
- Advanced Subqueries
- Multiple-Column Subqueries
- Correlated Subqueries
- Subqueries with Aggregate Functions (`AVG`, `COUNT`)
- EXISTS and NOT EXISTS Conditions
- Subqueries in ORDER BY
- CASE Expressions (`CASE`, `WHEN`, `THEN`, `ELSE`)
- Advanced Joins (`NATURAL JOIN`, `JOIN`, `USING`, `ON`)
- DML Operations on Join Views (`INSERT INTO`)
- User Management (`CREATE USER`, `ALTER USER`, `DROP USER`)
- User Account Management (`ACCOUNT LOCK`, `ACCOUNT UNLOCK`)
- System Privileges (`CREATE SESSION`, `CREATE TABLE`, `CREATE VIEW`, `CREATE SEQUENCE`)
- Object Privileges (`SELECT`, `INSERT`, `UPDATE`, `DELETE`)
- Role Management (`CREATE ROLE`, `GRANT`)
- Privilege Management (`GRANT`, `WITH GRANT OPTION`)
- User Privilege Metadata (`USER_SYS_PRIVS`, `USER_ROLE_PRIVS`, `DBA_USERS`)
- Multi-Table Insert (`INSERT ALL`, `INSERT FIRST`)
- Conditional Multi-Table Insert (`WHEN`, `THEN`, `ELSE`)
- Data Transformation Using Multi-Table Inserts
- MERGE Statement (`MERGE INTO`, `WHEN MATCHED`, `WHEN NOT MATCHED`)
- Table Creation and Data Manipulation (`CREATE TABLE`, `CTAS`, `UPDATE`, `DROP TABLE`)
- Transaction Management (`COMMIT`)
- Flashback Version Query (`VERSIONS BETWEEN SCN MINVALUE AND MAXVALUE`)
- Historical Data Tracking (`VERSIONS_STARTTIME`, `VERSIONS_ENDTIME`)

**All the practice commands are collected together at the end of the file for easy reference.**

---

## Oracle SQL Learning Journey — Completed

This file marks the completion of my current Oracle SQL learning series through IBCS-PRIMAX.

Throughout this journey, I practiced SQL fundamentals, data filtering, functions, aggregate operations, grouping, joins, subqueries, set operators, DDL, DML, constraints, indexes, sequences, synonyms, views, data dictionary queries, transaction management, advanced SQL techniques, and database user and privilege management.

I gained practical experience working with Oracle's built-in HR schema, creating and modifying database objects, querying data, managing transactions, and exploring advanced database operations.


## A Note to Visitors

Welcome to my repository!

This repository contains my personal Oracle SQL practice. I am sharing the SQL commands I have practiced along with their outputs so that anyone interested can explore them, learn from the examples, and practice on their own.

Please note: *I am not providing tutorials or teaching anyone through this repository. These are simply my personal learning records, so there may be mistakes, incomplete solutions, or incorrect outputs. Please use them as practice references rather than as a source of guaranteed or error-free information.*

MD. IMTAZ KAOSAR
