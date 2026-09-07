# Data Cleaning — Titanic Dataset

## Objective
Cleaned a messy real-world dataset (Titanic) by handling missing values, 
duplicates, inconsistent formatting, and outliers to produce an 
analysis-ready dataset.

## Dataset
Titanic dataset (Kaggle) — passenger demographics and survival data 
(891 rows, 12 columns).

## Tools Used
Python, pandas, numpy, Jupyter Notebook (VS Code)

## Data Quality Report (Before Cleaning)
- Age: 177 missing values
- Cabin: [confirm exact count] missing values (~77% of rows)
- Embarked: 2 missing values
- Duplicate rows: 0

## Cleaning Steps
- Age: filled with median (robust to outliers)
- Embarked: filled with mode (only 2 missing)
- Cabin: dropped entirely (~77% missing, unreliable to impute)
- Duplicate rows: 0 found, none removed
- Standardized text formatting for Sex and Embarked columns
- Outlier handling: Fare outliers ([confirm count] found) capped using IQR method
- Corrected data types for PassengerId, Survived, Pclass

## Output
Cleaned dataset saved as `data/cleaned_titanic.csv`