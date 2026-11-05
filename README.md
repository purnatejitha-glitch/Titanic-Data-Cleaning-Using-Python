# Titanic Dataset – Data Cleaning Using Python

## 📌 Project Overview

This project demonstrates a systematic data-cleaning process using Python, Pandas, and NumPy. The Titanic dataset was used to identify and handle missing values, duplicate records, inconsistent formatting, outliers, and incorrect data types.

The main goal is to transform a raw dataset into a clean, consistent, and analysis-ready dataset.

## 🎯 Project Objective

To demonstrate professional data-cleaning techniques and document every cleaning decision to improve data quality and reliability.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## 📂 Dataset Information

**Dataset:** Titanic Dataset

The dataset contains passenger information, including:

- Passenger ID
- Passenger Name
- Age
- Gender
- Passenger Class
- Ticket Information
- Fare
- Embarked Location
- Survival Status

## 🔍 Project Workflow

### 1. Data Loading and Inspection
- Imported the Titanic dataset using Pandas.
- Examined dataset shape, columns, and data types.
- Inspected the first few records.

### 2. Data Quality Report
- Identified missing values in each column.
- Calculated missing-value percentages.
- Checked duplicate records.
- Examined unique values and data types.

### 3. Missing Data Handling
- Used median imputation for missing Age values.
- Used mode imputation for missing Embarked values.
- Removed the Cabin column due to a high percentage of missing values.

### 4. Duplicate Removal
- Identified duplicate records using `duplicated()`.
- Removed exact duplicate rows using `drop_duplicates()`.

### 5. Data Standardisation
- Standardized gender values.
- Removed unnecessary leading and trailing spaces.
- Standardized Embarked categories into uppercase codes.

### 6. Outlier Detection
- Applied the Interquartile Range (IQR) method.
- Identified potential outliers in numerical columns.
- Used boxplots for outlier visualization.
- Retained valid extreme values rather than automatically deleting them.

### 7. Data Type Correction
- Converted PassengerId into string format.
- Corrected numerical columns into integer and float formats.
- Converted text and categorical columns into string formats.

### 8. Before vs. After Comparison
- Compared the original and cleaned datasets.
- Checked row counts and column counts.
- Compared missing values and duplicate records.
- Verified data types.

### 9. Export Cleaned Dataset
- Exported the cleaned dataset into a new CSV file.

## 📊 Key Data Cleaning Techniques

| Technique | Purpose |
|---|---|
| `isnull()` | Identify missing values |
| `fillna()` | Handle missing values |
| `duplicated()` | Identify duplicate records |
| `drop_duplicates()` | Remove duplicate rows |
| `astype()` | Correct data types |
| `replace()` | Standardize inconsistent values |
| `pd.to_numeric()` | Convert numerical values |
| IQR Method | Detect potential outliers |
| `to_csv()` | Export cleaned dataset |

## 📁 Project Structure

```text
Titanic-Data-Cleaning-Using-Python/
│
├── Titanic_Data_Cleaning.ipynb
├── Titanic_Cleaned_Dataset.csv
└── README.md
```

## 💡 Key Learnings

- Understanding real-world data quality issues.
- Handling missing values using appropriate imputation techniques.
- Identifying and removing duplicate records.
- Standardizing inconsistent categorical data.
- Detecting outliers using the IQR method.
- Correcting data types.
- Comparing data quality before and after cleaning.
- Exporting clean datasets for further analysis.

## 🚀 Project Outcome

Successfully performed data cleaning and preprocessing on the Titanic dataset using Python.

The project transformed the original dataset into a more consistent and analysis-ready format, demonstrating practical data preprocessing skills.

## 👩‍💻 Author

**Puli Purnatejitha**

**Domain:** Data Analytics

**Skills:** Python | Pandas | NumPy | Data Cleaning | Data Preprocessing | Jupyter Notebook
