# 📊 Data Cleaning & Preparation Project

## 📌 Overview
This project focuses on cleaning and preparing an employee dataset to ensure data quality and usability for analysis. The dataset contains HR-related information such as employee details, salaries, departments, and employment status.

The project uses both Excel and Python (Pandas) to explore, clean, and analyze the dataset.

---

## 🎯 Objectives
- Identify and handle missing values, duplicates, and outliers
- Perform data transformations and standardization
- Ensure data quality and consistency
- Generate workforce insights using Excel
- Calculate HR KPIs using Python

---

## 📂 Dataset
- File: `Week-3-Employee-Data.csv`
- Type: Structured data (tabular format)
- Fields include:
  - employee_id (unique identifier)
  - first_name, last_name
  - email
  - gender
  - department
  - job_title
  - hire_date, exit_date
  - is_active
  - salary, currency
  - location (country, state, city)
  - manager_id
  - performance_score

---

## 🛠️ Tools & Technologies
- Microsoft Excel (Pivot Tables, Charts, Data Formatting)
- Python (Pandas, Jupyter Notebook)
- CSV file format

---

## 📊 Project Tasks

### 🔹 Part A: Excel Analysis
- Imported and explored dataset
- Identified column purposes
- Created insights using Pivot Tables:
  - Headcount by Department
  - Active vs Inactive Employees
  - Hires by Year
  - Average Salary by Department and Currency
- Created chart:
  - Headcount by Department (Bar/Column chart)

---

### 🔹 Part B: Data Cleaning (Python)
Performed data cleaning using Pandas:
- Converted data types (dates, numeric fields)
- Trimmed whitespace and standardized text formatting
- Normalized categories (departments, currency codes)
- Handled missing values appropriately
- Removed duplicate records
- Validated:
  - Email format
  - Salary values (no negatives)
  - Date consistency (exit_date ≥ hire_date)

- Saved cleaned dataset:
  `Week-3-Employee-Data_CLEANED.csv`

---

### 🔹 Part C: HR KPI Analysis (Python)
Calculated key HR metrics:
- Current headcount
- Hires by year
- Average salary by department and currency
- Median tenure (days)
- Employee turnover rate

Optional analysis:
- Top 5 managers by team size
- Percentage of invalid emails

---

## 📁 Project Structure
