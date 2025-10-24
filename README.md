# diabetes_prediction_project

This project builds a machine learning model to predict diabetes status using health-related features. It demonstrates clean data handling, ethical preprocessing, and modeling steps.

# Contents
- diabetes_prediction_pipeline.ipynb`: Main notebook with all steps from data cleaning to modeling
- README.md: Project overview and documentation

# Dataset Overview

This project uses two publicly available health datasets:

- Iraq dataset: Contains anonymized patient records with features like glucose, HbA1c, blood pressure, and diabetic status.
- Bangladesh dataset: Includes similar health indicators, with additional binary flags for stroke, hypertension, and cardiovascular disease.

Both datasets were sourced from open-access repositories and merged manually. The final dataset includes:

- Numeric features: glucose, HbA1c, BMI, systolic and diastolic blood pressure
- Binary indicators(technically Categorical but encoded): stroke, hypertensive, cardiovascular disease, diabetic status
- Categorical features: gender, source country

data was cleaned, standardized, and used strictly for educational purposes. 


# Preprocessing Steps
- Manual type conversion using pd.to_numeric() and .astype() 
- Standardized categorical values (e.g., 'M', 'F', 'Yes', 'No')
- Median imputation for numeric features
- Mode imputation for binary features 
- handling of missing values and feature encoding

# Modeling Goals
- Build a transparent and reproducible ML pipeline
- Evaluate model performance on clean, imputed data
- Document every step for clarity and reproducibility



# Authors
Natnael Melake 
Susan Mbazazi
Zahara Alinalika


