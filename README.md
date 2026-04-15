# Messy Data Cleaning with Python (Pandas)

## Overview

This project demonstrates a real-world data cleaning workflow using Python and Pandas.  
The dataset used is a synthetic employee dataset containing intentional data quality issues.

---

## Problem

Raw datasets are often messy.  
This dataset included:

- Missing values
- Inconsistent text formatting
- Invalid dates
- Mixed data types
- Duplicate rows
- Outliers in salary
- Invalid and corrupted entries

---

## Objective

To transform a messy dataset into a clean, structured dataset ready for analysis.

---

## Tools Used

- Python
- Pandas
- NumPy
- Jupyter Notebook

---

## Data Cleaning Steps

1. Loaded raw CSV file
2. Explored dataset structure using `head()`, `info()`, `describe()`
3. Cleaned column names
4. Handled missing values
5. Converted data types (numeric and datetime)
6. Removed duplicate records
7. Standardized categorical text values
8. Detected and removed outliers using IQR method
9. Validated cleaned dataset
10. Exported final cleaned dataset

---

## Key Techniques Used

- `pd.to_numeric(errors='coerce')`
- `pd.to_datetime(errors='coerce')`
- `fillna()` with median and mode
- `drop_duplicates()`
- String normalization using `.str.strip()` and `.str.title()`
- IQR method for outlier detection

---

## Key Insights

- Real-world data is inconsistent and incomplete
- Data cleaning takes more time than analysis
- Outliers can heavily distort analysis results
- Standardization is critical before analysis
- Missing values often require context-based decisions

---

## How to Run

1. Clone repository
