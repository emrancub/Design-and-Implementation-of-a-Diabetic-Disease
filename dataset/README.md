# Design and Implementation of a Diabetic Disease Identification Algorithm Based on Data Mining - Dataset

## Overview

This dataset comprises medical and demographic information from 100,000 patients, focusing on predicting diabetes. Below is an overview of the dataset.

## Dataset Structure

The dataset is structured with 100,000 entries and 9 columns.

| Column               | Non-Null Count | Dtype  |
|----------------------|----------------|--------|
| gender               | 100,000        | object |
| age                  | 100,000        | float64|
| hypertension         | 100,000        | int64  |
| heart_disease        | 100,000        | int64  |
| smoking_history      | 100,000        | object |
| bmi                  | 100,000        | float64|
| HbA1c_level          | 100,000        | float64|
| blood_glucose_level  | 100,000        | int64  |
| diabetes             | 100,000        | int64  |

## First Five Rows

| gender | age  | hypertension | heart_disease | smoking_history | bmi  | HbA1c_level | blood_glucose_level | diabetes |
|--------|------|--------------|---------------|------------------|------|-------------|----------------------|----------|
| Female | 80.0 | 0            | 1             | never            | 25.19| 6.6         | 140                  | 0        |
| Female | 54.0 | 0            | 0             | No Info          | 27.32| 6.6         | 80                   | 0        |
| Male   | 28.0 | 0            | 0             | never            | 27.32| 5.7         | 158                  | 0        |
| Female | 36.0 | 0            | 0             | current          | 23.45| 5.0         | 155                  | 0        |
| Male   | 76.0 | 1            | 1             | current          | 20.14| 4.8         | 155                  | 0        |

## Missing Values

| Column               | Missing Values |
|----------------------|----------------|
| gender               | 0              |
| age                  | 0              |
| hypertension         | 0              |
| heart_disease        | 0              |
| smoking_history      | 0              |
| bmi                  | 0              |
| HbA1c_level          | 0              |
| blood_glucose_level  | 0              |
| diabetes             | 0              |

## Dataset Description

| Statistic            | age    | hypertension | heart_disease | bmi   | HbA1c_level | blood_glucose_level | diabetes |
|----------------------|--------|--------------|---------------|-------|-------------|----------------------|----------|
| count                | 96,128 | 96,128       | 96,128        | 96,128| 96,128      | 96,128               | 96,128   |
| mean                 | 41.80  | 0.08         | 0.04          | 27.32 | 5.53        | 138.22               | 0.09     |
| std                  | 22.46  | 0.27         | 0.20          | 6.77  | 1.07        | 40.91                | 0.28     |
| min                  | 0.08   | 0.00         | 0.00          | 10.01 | 3.50        | 80.00                | 0.00     |
| 25%                  | 24.00  | 0.00         | 0.00          | 23.40 | 4.80        | 100.00               | 0.00     |
| 50%                  | 43.00  | 0.00         | 0.00          | 27.32 | 5.80        | 140.00               | 0.00     |
| 75%                  | 59.00  | 0.00         | 0.00          | 29.86 | 6.20        | 159.00               | 0.00     |
| max                  | 80.00  | 1.00         | 1.00          | 95.69 | 9.00        | 300.00               | 1.00     |


## Conclusion

For more detailed information, please refer to the dataset named "diabetes_prediction_dataset.csv" included in this repository. Additionally, you can find a comprehensive analysis in the Diabeties.ipynb file inside the code folder.

I collected this data from [Kaggle](https://www.kaggle.com), a platform for data science and machine learning.

Feel free to explore the dataset and the associated analysis to gain deeper insights into the predictions and trends related to diabetes.

---

**Note:** If you encounter any issues or have questions, please don't hesitate to reach out for further clarification or assistance.

