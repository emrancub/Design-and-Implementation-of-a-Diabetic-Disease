# Design and Implementation of a Diabetic Disease Identification Algorithm Based on Data Mining - Dataset

# Dataset Overview

This dataset contains information related to pregnancies and health measurements, with a focus on predicting diabetes likelihood. Features include pregnancies, glucose levels, blood pressure, skin thickness, insulin, BMI, diabetes pedigree function, and age. The dataset contains information on diabetic patients with the following columns:

1. **Pregnancies**: Number of pregnancies (int64)
2. **Glucose**: Glucose level (int64)
3. **BloodPressure**: Blood pressure (int64)
4. **SkinThickness**: Skin thickness (int64)
5. **Insulin**: Insulin level (int64)
6. **BMI**: Body mass index (float64)
7. **DiabetesPedigreeFunction**: Diabetes pedigree function (float64)
8. **Age**: Age of the patient (int64)
9. **Outcome**: Diabetes outcome (int64)

## Data Statistics

- **Non-Null Count**: 768 entries for each column
- **Dtypes**: Data types of each column (int64 or float64)

This dataset provides valuable information for studying diabetes and related factors.


## Sample Data

| Pregnancies | Glucose | BloodPressure | SkinThickness | Insulin | BMI  | DiabetesPedigreeFunction | Age |
|-------------|---------|---------------|---------------|---------|------|--------------------------|-----|
| 6           | 148     | 72            | 35            | 0       | 33.6 | 0.627                    | 50  |
| 1           | 85      | 66            | 29            | 0       | 26.6 | 0.351                    | 31  |
| 8           | 183     | 64            | 0             | 0       | 23.3 | 0.672                    | 32  |
| 1           | 89      | 66            | 23            | 94      | 28.1 | 0.167                    | 21  |
| 0           | 137     | 40            | 35            | 168     | 43.1 | 2.288                    | 33  |


## Missing Values

| Feature                   | Missing Values |
|---------------------------|-------|
| Pregnancies               | 0     |
| Glucose                   | 0     |
| BloodPressure             | 0     |
| SkinThickness             | 0     |
| Insulin                   | 0     |
| BMI                       | 0     |
| DiabetesPedigreeFunction  | 0     |
| Age                       | 0     |
| Outcome                   | 0     |

## Summary Statistics

| Feature                   | Count | Mean  | Std   | Min   | 25%   | 50%   | 75%   | Max   |
|---------------------------|-------|-------|-------|-------|-------|-------|-------|-------|
| Pregnancies               | 768   | 3.85  | 3.37  | 0.00  | 1.00  | 3.00  | 6.00  | 17.00 |
| Glucose                   | 768   | 120.89| 31.97 | 0.00  | 99.00 | 117.00| 140.25| 199.00|
| BloodPressure             | 768   | 69.11 | 19.36 | 0.00  | 62.00 | 72.00 | 80.00 | 122.00|
| SkinThickness             | 768   | 20.54 | 15.95 | 0.00  | 0.00  | 23.00 | 32.00 | 99.00 |
| Insulin                   | 768   | 79.80 | 115.24| 0.00  | 0.00  | 30.50 | 127.25| 846.00|
| BMI                       | 768   | 31.99 | 7.88  | 0.00  | 27.30 | 32.00 | 36.60 | 67.10 |
| DiabetesPedigreeFunction  | 768   | 0.47  | 0.33  | 0.08  | 0.24  | 0.37  | 0.63  | 2.42  |
| Age                       | 768   | 33.24 | 11.76 | 21.00 | 24.00 | 29.00 | 41.00 | 81.00 |
| Outcome                   | 768   | 0.35  | 0.48  | 0.00  | 0.00  | 0.00  | 1.00  | 1.00  |

Feel free to use these summary statistics for a better understanding of the dataset.


## Conclusion

For more detailed information, please refer to the dataset named "diabetes_dataset.csv" included in this repository. Additionally, you can find a comprehensive analysis in the diabeties.ipynb file inside the code folder.

I collected this data from [Kaggle](https://www.kaggle.com) and this is the open datasouce, a platform for data science and machine learning. Sourced from the National Institute of Diabetes and Kidney Diseases, this dataset comprises information from 768 female patients aged 21 years and above.

Feel free to explore the dataset and the associated analysis to gain deeper insights into the predictions and trends related to diabetes.

---

**Note:** If you encounter any issues or have questions, please don't hesitate to reach out for further clarification or assistance.

