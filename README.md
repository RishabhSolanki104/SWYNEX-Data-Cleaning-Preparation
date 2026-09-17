# SWYNEX - Data Cleaning & Preparation (Task 1)

## Overview
This repository contains the completed Task 1: Data Cleaning & Preparation for the internship at SWYNEX Technologies. An initial dataset containing 500 raw employee records with formatting inconsistencies, duplicates, and missing values was cleaned and prepared using Microsoft Excel.

## Files Included
- `raw_employee_data_500.xlsx`: The raw dataset before cleaning.
- `cleaned_employee_dataset.csv`: The finalized, clean, and analysis-ready dataset.

## Cleaning Steps Performed (Microsoft Excel)
1. **Duplicate Removal:** Removed 30 duplicate entries based on `Emp_ID` using Excel's built-in `Remove Duplicates` feature.
2. **Text Standardization:** Applied `=PROPER(TRIM())` to format names correctly and remove unwanted whitespaces.
3. **Handling Missing Values:** Handled missing and invalid values in `Age` and `Salary` using median and statistical imputation.
4. **Standardizing Dates:** Unified all mixed date formats into the standard `YYYY-MM-DD` structure.
5. **Department Normalization:** Standardized casing and abbreviations (`ops` -> `Operations`, `it` -> `IT`) using Find & Replace.
6. **Data Type Correction:** Cleaned currency signs (`$`, `₹`) and commas from the `Salary` column to ensure numerical formatting.
7. **Email Generation:** Reconstructed missing and broken email addresses using Excel text functions (`LOWER`, `SUBSTITUTE`).

## Tools Used
- Microsoft Excel
