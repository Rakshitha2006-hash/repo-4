# Task 1 – Data Cleaning and Preprocessing

## 📌 Internship Task

**Task:** Task 1 – Data Cleaning and Preprocessing  
**Tools Used:** Microsoft Excel  
**Dataset:** Sales Data  
**Domain:** Data Analytics

## 🎯 Objective

The objective of this task was to clean and preprocess a raw dataset so that it becomes structured, consistent, and ready for further data analysis and visualization.

The task focused on identifying and handling common data-quality problems such as missing values, duplicate records, inconsistent text formats, date/format inconsistencies, incorrect column names, and data-type issues.

## 📊 Dataset Overview

The dataset used for this task contains **199 records and 12 columns**.

The dataset includes information related to sales, products, regions, categories, customers, months, years, and other sales attributes.

## 🧹 Data Cleaning Process

### 1. Missing Value Check

The dataset was checked for missing or null values.

**Result:** No missing values were found in the dataset.

### 2. Duplicate Check

The dataset was checked for duplicate records.

**Result:** No duplicate records were found.

### 3. Column Name Standardization

Column headers were cleaned and standardized to make them consistent and easier to work with.

- Spaces were replaced with underscores.
- Column names were converted into a consistent lowercase format.
- Unnecessary formatting inconsistencies were removed.

### 4. Text Standardization

Text-based fields were reviewed to identify inconsistent values and formatting. The values were standardized wherever required.

### 5. Data Type Validation

The data types of the columns were checked to ensure that numerical and categorical fields were stored appropriately.

Numeric fields such as **Sales** and **Year** were checked and maintained as numeric values.

### 6. Postal Code Formatting

Postal Code values were checked and formatted consistently as **5-digit identifiers**.

### 7. Month Data Cleaning

The `month` column contained one inconsistent value, **"Order Date"**, which did not represent a valid month.

Instead of assuming or guessing the correct month, this value was changed to **"Unknown"**.

## 📋 Data Quality Results

| Data Quality Check | Result |
|---|---|
| Total Records | 199 |
| Total Columns | 12 |
| Missing Values | 0 |
| Duplicate Records | 0 |
| Inconsistent Month Value | 1 |
| Standardized Column Names | Yes |
| Data Types Checked | Yes |
| Postal Code Formatting | Standardized |

## 📁 Files Included

- `Task_1_Data_Cleaning_Completed.xlsx` – Completed Excel workbook
- `README.md` – Task description and documentation

## 📑 Excel Workbook Structure

The completed Excel workbook contains:

- **Task 1 Overview** – objective and task details
- **Raw Data** – original dataset
- **Cleaned Data** – processed and standardized dataset
- **Cleaning Summary** – summary of the cleaning operations
- **Data Quality Check** – validation results

## ✅ Final Outcome

After completing the preprocessing steps, the dataset was converted into a cleaner and more structured format suitable for further analysis, visualization, and modelling.

This task provided practical experience in identifying data-quality issues and preparing real-world data for analysis using Excel.

## 💡 Key Learning

Through this task, I learned how to:

- Identify missing values
- Detect duplicate records
- Standardize column names
- Handle inconsistent data
- Validate data types
- Format data consistently
- Perform basic data-quality checks
- Prepare a dataset for further analysis

## 🛠️ Tools

- Microsoft Excel
- GitHub

## 📌 Task Status

**Task 1 – Completed ✅**
