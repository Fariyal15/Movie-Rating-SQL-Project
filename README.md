# Movie Rating SQL Project

This project contains SQL code for creating and querying a **movie rating database**.  
It includes database creation, table definitions, sample data insertion, and a full set of SQL queries that analyze the data.

---

## Project Structure

### 1. Database Setup
- Creates the database: `movierating`
- Selects the database using: `USE movierating`

### 2. Table Definitions
The following tables are created:

- **movie** — Stores movie information  
- **reviewer** — Contains reviewer names  
- **rating** — Stores movie ratings and dates  

### 3. Sample Data
The project populates the database with sample entries:
- Movies (8 records)
- Reviewers (8 records)
- Ratings (15+ records)

### 4. SQL Queries
The script includes multiple SQL queries demonstrating:

- SELECT with filtering  
- Sorting and grouping  
- JOINs and self JOINs  
- Subqueries  
- Aggregations (AVG, MIN, MAX)  
- Identifying rating trends  
- Updating and deleting records  
- Finding highest/lowest rated movies  
- Movies without ratings  
- Reviewers with NULL rating dates  
- Directors with multiple movies  

---

## How to Use

1. Copy the SQL script into any SQL editor (MySQL recommended).  
2. Run each section in order:
   - Database creation  
   - Table creation  
   - Insert statements  
   - Queries  
3. Some queries are written for MySQL and may behave differently in SQLite.

---

## Concepts Covered

### ### SQL Fundamentals
- CREATE, INSERT, SELECT, UPDATE, DELETE  
- WHERE conditions  
- NULL checks  
- Basic filtering  

### ### Intermediate SQL
- JOIN operations  
- Subqueries  
- GROUP BY + HAVING  
- Aggregate functions  

### ### Advanced SQL Concepts
- Rating spread (difference between highest and lowest ratings)  
- Highest/lowest movie averages  
- Detecting duplicate reviews  
- Reviewer comparisons  
- Conditional updates/deletes  

---

## Notes

- All SQL is formatted for readability.  
- Queries include comments explaining their purpose.  
- This project is ideal for practicing beginner to intermediate SQL.

