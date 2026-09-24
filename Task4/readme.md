# Task 4 – Final Data Analytics Project

# HR Employee Workforce and Salary Analysis

## 📌 Project Overview

This project was developed as part of **Task 4 – Final Data Analytics Project** during my Data Analyst internship at **Swynex Technology**.

The objective of this project is to transform raw HR employee data into a clean, structured, and analytical dataset and use it to identify meaningful insights related to **employee workforce distribution, salary patterns, departmental differences, and hiring trends**.

The project covers the complete data analytics workflow:

**Raw Data → Data Cleaning → EDA → Power BI Dashboard → Business Insights**

---

## 🎯 Problem Statement

Organizations generate large amounts of employee data, but raw HR data may contain missing values, duplicate records, inconsistent department names, invalid values, and non-standard date formats.

These data-quality issues can make it difficult for HR teams to accurately understand:

- Workforce distribution
- Department-wise employee count
- Salary patterns
- Salary differences across departments
- Employee hiring trends

Therefore, the objective of this project is to clean and analyze the raw employee dataset and develop an interactive **Power BI dashboard** that provides clear HR workforce and salary insights.

---

## 📂 Dataset Information

The original dataset contains **500 employee records** and 7 core fields.

| Column | Description |
|---|---|
| Emp_ID | Unique employee identifier |
| Full_Name | Employee full name |
| Age | Employee age |
| Join_Date | Employee joining date |
| Department | Employee department |
| Salary | Employee salary |
| Email | Employee email address |

### Dataset Summary

- **Raw Records:** 500
- **Final Analytical Records:** 470
- **Records Removed:** 30 duplicate records
- **Departments:** Sales, Operations, Finance, IT, Marketing, HR, Other
- **Joining Period:** 2018–2025

> Note: The public repository dataset excludes employee names and email addresses to avoid exposing personal information.

---

## 🧹 Data Cleaning Process

The following data-cleaning steps were performed:

### 1. Duplicate Removal
Identified and removed **30 duplicate records**, reducing the dataset from 500 to 470 records.

### 2. Missing Value Handling
Missing values were identified in:

- Age
- Join_Date
- Department
- Salary
- Email

These issues were resolved during data preprocessing.

### 3. Age Validation
Invalid negative age values were identified and corrected.

The final employee age range is:

**22–58 years**

### 4. Department Standardization
Inconsistent department names and capitalization were standardized into:

- Sales
- Operations
- Finance
- IT
- Marketing
- HR
- Other

### 5. Date Standardization
Joining dates were standardized to enable year-wise hiring analysis.

### 6. Salary Validation
Salary values were converted into a consistent numeric format and validated for minimum and maximum values.

### 7. Final Data Validation
The cleaned dataset was checked for:

- Missing values
- Duplicate records
- Invalid age values
- Department consistency
- Date consistency
- Salary validity

---

## 📊 Exploratory Data Analysis

After cleaning, the dataset contained **470 employees**.

### Key Metrics

| Metric | Value |
|---|---:|
| Total Employees | 470 |
| Total Salary | ₹48.71M |
| Average Salary | ₹103,641.49 |
| Median Salary | ₹102,000 |
| Minimum Salary | ₹25,000 |
| Maximum Salary | ₹180,000 |
| Age Range | 22–58 years |
| Joining Period | 2018–2025 |

---

## 🏢 Department Analysis

| Department | Employees | Average Salary |
|---|---:|---:|
| Sales | 80 | ₹102,675.00 |
| Operations | 79 | ₹103,126.58 |
| Finance | 77 | ₹107,655.84 |
| Marketing | 76 | ₹100,644.74 |
| IT | 76 | ₹103,934.21 |
| HR | 65 | ₹96,753.85 |
| Other | 17 | ₹130,823.53 |

---

## 📈 Hiring Trend Analysis

Employee joining trends were analyzed from **2018 to 2025**.

| Year | Employees Joined |
|---|---:|
| 2018 | 66 |
| 2019 | 65 |
| 2020 | 48 |
| 2021 | 69 |
| 2022 | 55 |
| 2023 | 51 |
| 2024 | 54 |
| 2025 | 62 |

The highest number of employees joined in **2021 with 69 employees**, while the lowest was **2020 with 48 employees**.

---

## 📊 Power BI Dashboard

The project includes an interactive Power BI dashboard titled:

### **HR Employee Workforce and Salary Analysis**

The dashboard provides a consolidated view of HR workforce and compensation data.

### Dashboard Features

- Total Employees KPI
- Total Salary KPI
- Average Salary KPI
- Employees by Department
- Employee Salary Distribution
- Employee Hiring Trend
- Average Salary by Department
- Department Summary Table
- Department Filter
- Year Filter

### Dashboard Preview

![HR Employee Workforce and Salary Analysis Dashboard](dashboard/HR_Employee_Workforce_and_Salary_Analysis.png)

The Power BI `.pbix` file is also included in the `dashboard` folder.

---

## 💡 Key Business Insights

### Workforce Distribution

- **Sales** has the highest employee count with **80 employees**.
- **Operations** follows with **79 employees**.
- **HR** has the lowest employee count among the named departments with **65 employees**.

### Salary Analysis

- **Finance** has the highest average salary among the six named core departments at approximately **₹107.66K**.
- **HR** has the lowest average salary among those departments at approximately **₹96.75K**.
- The overall salary range is **₹25K–₹180K**.
- The **Other** category has an average salary of approximately **₹130.82K**, but contains only 17 employees and should therefore be interpreted separately.

### Hiring Trends

- Hiring was highest in **2021**, with 69 employees joining.
- Hiring was lowest in **2020**, with 48 employees joining.
- The hiring trend provides useful information for workforce planning.

---

## 📌 Business Recommendations

Based on the analysis:

1. Review departmental compensation bands to understand salary differences across roles and experience levels.
2. Investigate the composition of the **Other** department category.
3. Use historical hiring trends to support future workforce planning.
4. Monitor departments with relatively lower employee counts for potential capacity gaps.
5. Maintain a consistent HR data-quality process for duplicates, missing values, categories, dates, and salary fields.
6. Future dashboard versions can incorporate additional HR metrics such as tenure, attrition, promotion, and performance when relevant data becomes available.

---

## 🛠️ Tools & Technologies

- **Power BI**
- **Microsoft Excel**
- **Data Cleaning**
- **Exploratory Data Analysis (EDA)**
- **Data Visualization**
- **Business Analysis**

---

## 📁 Project Structure

```text
HR_Employee_Workforce_and_Salary_Analysis/
│
├── data/
│   ├── raw/
│   └── cleaned/
│
├── dashboard/
│   ├── HR Employee Workforce and Salary Analysis.pbix
│   ├── HR_Employee_Workforce_and_Salary_Analysis.png
│   └── README.md
│
├── report/
│   └── HR_Employee_Workforce_and_Salary_Analysis_Report.pdf
│
├── docs/
│   └── data_dictionary.md
│
├── README.md
└── .gitignore
