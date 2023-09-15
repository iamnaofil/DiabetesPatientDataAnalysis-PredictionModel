# DiabetesPatientDataAnalysis-PredictionModel
The analysis provides insights into diabetes prediction using certain medical measurements. While the model demonstrates predictive power, it's essential to consider its limitations and consult medical experts for comprehensive diagnosis and treatment decisions.


## Introduction

This repository contains a Python-based analysis and prediction model for diabetes diagnosis using a dataset of female Pima Indian patients. The project aims to explore the dataset, build a predictive model, and provide an interactive dashboard for making predictions. The README file provides detailed information on how to use the project and its various components.

## Project Overview

- **Data Source**: The dataset is originally from the National Institute of Diabetes and Digestive and Kidney Diseases. It focuses on diagnosing diabetes based on specific medical measurements.

- **Analysis**: The project includes data preprocessing, exploratory data analysis (EDA), and predictive modeling. It also offers an interactive dashboard for user input and visualization.

- **Predictive Model**: A logistic regression model is developed to predict diabetes outcomes.

## Dataset

- **Dataset Source**: The dataset is provided in the `diabetes_dataset.csv` file.

- **Dataset Features**:
  - Pregnancies
  - Glucose
  - BloodPressure
  - SkinThickness
  - Insulin
  - BMI
  - DiabetesPedigreeFunction
  - Age
  - Outcome (0 = No Diabetes, 1 = Diabetes)
 
**Data Anomilies :**

Pregnancies:

Check for negative values: Pregnancies should always be a non-negative integer. Ensure there are no negative values.
Glucose:

Check for extreme values: Glucose levels that are too high or too low could be anomalies. Plot a histogram to visualize the distribution and look for outliers.
Check for missing values or zeros: Glucose levels of zero may indicate missing data or anomalies.
BloodPressure:

Check for extreme values: Blood pressure should be within a reasonable range. Plot a histogram to visualize the distribution and look for outliers.
Check for missing values or zeros: Blood pressure of zero may indicate missing data or anomalies.
SkinThickness:

Check for extreme values: Skin thickness values that are too high or too low could be anomalies. Plot a histogram to visualize the distribution and look for outliers.
Check for missing values.
Insulin:

Check for extreme values: Insulin levels that are too high or too low could be anomalies. Plot a histogram to visualize the distribution and look for outliers.
Check for missing values.
BMI:

Check for extreme values: BMI values that are too high or too low could be anomalies. Plot a histogram to visualize the distribution and look for outliers.
Check for missing values or zeros: BMI of zero may indicate missing data or anomalies.
DiabetesPedigreeFunction:

Check for extreme values: Ensure that the values are within a reasonable range. Plot a histogram to visualize the distribution and look for outliers.
Check for missing values.
Age:

Check for negative values: Age should always be a non-negative integer. Ensure there are no negative values.
Check for extreme values: Age values that are too high (unlikely in this context) could be anomalies. Plot a histogram to visualize the distribution and look for outliers.
Outcome:

Check for values other than 0 and 1: The outcome should ideally be binary, with 0 indicating no diabetes and 1 indicating diabetes. Ensure there are no other values.


**Installation Libraries**

```pip install pandas numpy scikit-learn dash plotly```
