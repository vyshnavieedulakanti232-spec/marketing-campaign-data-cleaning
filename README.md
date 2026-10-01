# Marketing Campaign Data | Cleaning & Preprocessing

### Internship Task 1 — Data Analytics

## Overview

A structured data-cleaning project focused on transforming a raw Marketing Campaign dataset into a reliable and analysis-ready dataset.

The approach followed:

**Understand → Clean → Validate → Document → Prepare**

## Project Objectives

- Identify data-quality issues
- Handle missing and invalid values
- Validate data types and formats
- Check duplicate records
- Standardize dates and text fields
- Review potential outliers
- Prepare the dataset for further analysis

## Data Quality & Cleaning

| Check | Result |
|---|---:|
| Records | 2,240 |
| Original Columns | 29 |
| Missing Income Values | 24 |
| Invalid Birth-Year Values | 2 |
| Duplicate Records | 0 |
| Duplicate Customer IDs | 0 |

### Key Actions

- Missing `Income` values were handled using median imputation.
- Invalid birth-year values were identified and corrected.
- Duplicate records and customer IDs were checked.
- Customer registration dates were standardized.
- Text formatting was cleaned for consistency.
- An IQR-based outlier review was performed on `Income`.
- Important cleaning decisions were documented for traceability.

## Analytical Enhancements

The cleaned dataset was extended with useful analytical fields:

- `Total_Spend`
- `Total_Purchases`
- `Campaign_Acceptance_Count`
- `Customer_Value_Segment`

These fields support future customer segmentation, campaign analysis and business insights.

## Tools & Techniques

**Tools:** Microsoft Excel, GitHub

**Techniques:** Data validation, missing-value handling, duplicate detection, standardization, outlier analysis and feature engineering.

## Repository Contents

- `README.md` — Project documentation
- `Marketing_Campaign_Data_Cleaning_Report.pdf` — Original data, cleaned data and cleaning summary

## Outcome

The final dataset is structured, validated and prepared for **Exploratory Data Analysis (EDA), visualization and further business analysis**.

---

**Internship Task 1 | Data Cleaning & Preprocessing | Completed**
