# 📊 Employee Trend Analysis SQL Queries

This repository contains a set of SQL queries used for an initial trend analysis on an employee dataset. The analysis focuses on various demographic, departmental, and satisfaction trends to provide insights into the workforce structure and employee sentiment.

---

## 💾 Database Schema and Code Foundation

The analysis is performed on the `employees_hr` table, which holds detailed information about each employee.

### Table Creation

The following SQL was used to establish the table structure:

```sql
CREATE TABLE employees_hr (
    emp_no              INT PRIMARY KEY,
    gender              TEXT,
    marital_status      TEXT,
    age_band            TEXT,           
    age                 SMALLINT,
    department          TEXT,
    education           TEXT,           
    education_field     TEXT,
    job_role            TEXT,
    business_travel     TEXT,
    employee_count      SMALLINT,
    attrition           TEXT,           
    attrition_label     TEXT,          
    job_satisfaction    SMALLINT,
    active_employee     SMALLINT 
	);
