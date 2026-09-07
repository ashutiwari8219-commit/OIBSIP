# Data Cleaning — Titanic Dataset

## Objective
Cleaned a messy real-world dataset (Titanic) by handling missing values, 
duplicates, inconsistent formatting, and outliers to produce an 
analysis-ready dataset.

## Dataset
Titanic dataset (Kaggle) — passenger demographics and survival data.

## Tools Used
Python, pandas, numpy, Jupyter Notebook (VS Code)

## Cleaning Steps
- Missing values: Age (median), Embarked (mode), Cabin (dropped — ~77% missing)
- Removed [X] duplicate rows
- Standardized text formatting for Sex and Embarked columns
- Outlier handling: Fare outliers capped using IQR method
- Corrected data types for PassengerId, Survived, Pclass

## Output
Cleaned dataset saved as `data/cleaned_titanic.csv`