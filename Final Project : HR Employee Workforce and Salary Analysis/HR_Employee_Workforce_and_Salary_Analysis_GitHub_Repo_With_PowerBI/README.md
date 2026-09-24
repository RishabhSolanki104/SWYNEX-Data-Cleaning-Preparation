# HR Employee Workforce and Salary Analysis

## Project Overview

**HR Employee Workforce and Salary Analysis** is an end-to-end Data Analytics project completed during an internship at **Swynex Technology**.

The project transforms raw HR employee data into a clean analytical dataset and an interactive Power BI dashboard focused on:

- Workforce distribution
- Department-wise employee analysis
- Salary distribution and compensation patterns
- Hiring trends from 2018–2025
- Department-wise average salary
- HR-focused business insights and recommendations

## Project Objectives

1. Identify and resolve data-quality issues in raw employee data.
2. Prepare a clean and consistent dataset for analysis.
3. Analyze workforce distribution across departments.
4. Analyze salary levels and salary differences across departments.
5. Identify employee hiring trends over time.
6. Build an interactive Power BI dashboard.
7. Generate business insights for HR reporting and workforce planning.

## Dataset

The original dataset contained **500 employee records and 7 fields**:

| Field | Description |
|---|---|
| Emp_ID | Unique employee identifier |
| Full_Name | Employee full name |
| Age | Employee age |
| Join_Date | Employee joining date |
| Department | Employee department |
| Salary | Employee salary |
| Email | Employee email address |

After data cleaning, the final analytical dataset contained **470 employee records**.

> **Privacy note:** The public GitHub version intentionally excludes employee names and email addresses. The included CSV files contain only analytical fields required to reproduce the analysis.

## Data Cleaning

The project addressed:

- 30 duplicate records
- Missing Age values
- Missing Join_Date values
- Missing Department values
- Missing Salary values
- Missing Email values in the original working dataset
- 7 invalid negative age values
- Inconsistent department naming/capitalization
- Date-format standardization
- Salary validation

Departments were standardized into:

**Sales, Operations, Finance, IT, Marketing, HR, and Other**

## Key Metrics

- **Total Employees:** 470
- **Total Salary:** ₹48.71M
- **Average Salary:** ₹103,641.49
- **Median Salary:** ₹102,000
- **Salary Range:** ₹25,000–₹180,000
- **Employee Age Range:** 22–58 years
- **Joining Period:** 2018–2025

## Key Insights

- Sales has the largest employee count with **80 employees**.
- Operations follows with **79 employees**.
- HR has **65 employees** among the named departments.
- Finance has the highest average salary among the six named core departments at approximately **₹107.66K**.
- HR has the lowest average salary among the named core departments at approximately **₹96.75K**.
- The `Other` category has an average salary of approximately **₹130.82K**, but contains only 17 employees and should be interpreted separately.
- Hiring was highest in **2021 with 69 employees** and lowest in **2020 with 48 employees**.

## Power BI Dashboard

The dashboard includes:

- Total Employees KPI
- Total Salary KPI
- Average Salary KPI
- Employees by Department
- Employee Salary Distribution
- Employee Hiring Trend
- Average Salary by Department
- Department Summary Table
- Department and Year filters

### Dashboard Preview

![HR Employee Workforce and Salary Analysis Dashboard](dashboard/HR_Employee_Workforce_and_Salary_Analysis.png)

## Tools & Technologies

- **Power BI**
- **Microsoft Excel**
- **Data Cleaning & Preprocessing**
- **Exploratory Data Analysis (EDA)**
- **Data Visualization**
- **Business Analysis**

## Repository Structure

```text
HR_Employee_Workforce_and_Salary_Analysis/
│
├── data/
│   ├── raw/
│   │   └── raw_employee_data_500_public.csv
│   └── cleaned/
│       └── cleaned_employee_data_public.csv
│
├── dashboard/
│   ├── HR_Employee_Workforce_and_Salary_Analysis.png
│   ├── HR Employee Workforce and Salary Analysis.pbix
│
├── report/
│   └── HR_Employee_Workforce_and_Salary_Analysis_Report.pdf
│
├── docs/
│   └── data_dictionary.md
│
├── README.md
└── .gitignore
```

## Business Value

The project demonstrates how raw HR data can be converted into management-friendly insights for:

- Workforce planning
- Compensation review
- Department-level workforce analysis
- Hiring trend monitoring
- HR reporting
- Data-driven decision-making

## Project Report

The complete project report is available in the `report/` folder.

## Author

**Rishabh Solanki**

Data Analyst | Power BI | SQL | Excel | Python
