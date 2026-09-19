# Task 2: Exploratory Data Analysis (EDA)

## Project Overview
This project involves performing Exploratory Data Analysis (EDA) on an employee dataset (`cleaned_employee_data_500.csv`) using Microsoft Excel. The primary objective is to calculate statistical summaries, identify hiring velocity patterns, assess compensation structures, and detect business anomalies across departments.

---

## Key Business Insights

1. **Hiring Trends Over Time (Peak in 2020):**
   * Recruitment remained steady at 92–93 annual hires in 2018 and 2019, before surging to a peak of 100 new hires in 2020.
   * Following 2020, recruitment velocity stabilized back to ~92–93 intakes per cycle.

2. **Total Payroll & Budget Allocation:**
   * Total organizational salary expenditure stands at **₹48,711,500 (~₹4.87 Cr)**.
   * **Finance (₹82.89L)**, **Sales (₹82.14L)**, and **Operations (₹81.47L)** command the highest cumulative salary expenditure, representing the core payroll weight.

3. **Workforce Distribution Across Departments:**
   * Departmental headcount exhibits structural balance across primary verticals: **Sales (80)**, **Operations (79)**, **Finance (77)**, and **IT / Marketing (76 each)**.
   * **HR (65)** and **Other (17)** function as leaner operational units.

4. **Workforce Demographics:**
   * The overall workforce average age is **39.94 years**.
   * **HR (41.88 years)** and **Other (41.12 years)** skew toward senior profiles, while **Finance (38.51 years)** and **IT (39.34 years)** maintain a younger talent concentration.

5. **Age Bracket vs. Compensation Dynamics:**
   * Overall average salary across records is **₹103,641**.
   * The **32–41 age tier** records the highest average compensation at **₹106,228**, closely followed by the **42–51 tier (₹106,138)**.
   * Early-career professionals (**22–31 bracket**) command a competitive average of **₹98,428**, highlighting skills-based compensation models.

---

## Data Anomalies & Quality Checks
* **Record Variance:** The evaluated pivot tables aggregate **470 active employee records** out of the expected 500-record threshold, identifying an actionable data gap for reconciliation.

---

## Visualizations Included
* **Hiring Trend:** Line Chart (Join Year vs. Count of Employees)
* **Budget Allocation:** Clustered Column Chart (Department vs. Sum of Salary)
* **Workforce Share:** Doughnut Chart (Department vs. Employee Count)
* **Demographics:** Horizontal Bar Chart (Department vs. Average Age)
* **Pay Scaling:** Clustered Column Chart (Age Group vs. Average Salary)

---

## Tools & Techniques
* **Tool:** Microsoft Excel
* **Techniques:** Pivot Tables, Multi-field Aggregations (`SUM`, `AVERAGE`, `COUNT`), Custom Categorical Grouping (10-Year Age Brackets), and Data Visualization.
