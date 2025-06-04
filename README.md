# Employee Analytics Project

## Overview

This project analyzes employee data to uncover insights on workforce demographics, salary trends, department transfers, and gender pay gaps. The dataset is sourced from a publicly available dataset hosted on GitHub.

SQL queries were developed to extract key metrics and relationships, and Power BI was used to create interactive dashboards for data visualization.

---

-  Sample employee database 
--  See changelog table for details
--  Copyright (C) 2007,2008, MySQL AB
--  
--  Original data created by Fusheng Wang and Carlo Zaniolo
--  http://www.cs.aau.dk/TimeCenter/software.htm
--  http://www.cs.aau.dk/TimeCenter/Data/employeeTemporalDataSet.zip
-- 
--  Current schema by Giuseppe Maxia 
--  Data conversion from XML to relational by Patrick Crews
-- 
-- This work is licensed under the 
-- Creative Commons Attribution-Share Alike 3.0 Unported License. 
-- To view a copy of this license, visit 
-- http://creativecommons.org/licenses/by-sa/3.0/ or send a letter to 
-- Creative Commons, 171 Second Street, Suite 300, San Francisco, 
-- California, 94105, USA.
-- 
--  DISCLAIMER
--  To the best of our knowledge, this data is fabricated, and
--  it does not correspond to real people. 
--  Any similarity to existing people is purely coincidental.

- The dataset includes tables such as:
  - `employees` — employee personal details
  - `salaries` — salary history records
  - `departments` — department information
  - `dept_emp` — employee department assignments
  - `dept_manager` — department managers
  - `titles` — job titles held by employees

- The data is modeled on a real-world company employee database and uses `to_date = '9999-01-01'` to indicate active records.

---

## SQL Queries

The project contains the following key SQL queries:

- **Active Managers**: Lists current managers with age, tenure, and department.
- **Gender Contributions**: Gender distribution in each department.
- **Top 10 Highest Salaries**: Employees with highest current salaries.
- **Top 3 Salaries per Department**: Ranking salaries department-wise.
- **Salary Growth Trends**: Employees with significant salary increases.
- **Gender Pay Gap Analysis**: Salary differences by gender for each role.
- **Highest Entry Salaries Post-1980**: Entry salary stats by job and department.
- **Employee Transfer Frequency**: Employees who transferred departments.
- **Department Salary and Employee Counts**: Summary of headcount and salary distribution by department.

*(For full SQL query scripts, see the `queries` folder or `sql_queries.sql` file in this repository.)*

---

## Using the SQL Queries in Power BI

- Connect Power BI Desktop to your SQL database.
- Import and execute the provided queries to load cleaned data tables.
- Use Power BI visuals (charts, tables, slicers) to build dashboards around the insights.
- Set up data refresh schedules for up-to-date reporting.

---

## How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/<username>/<repository>.git
