# Patient Health Records Dataset

This repository provides an anonymized collection of patient medical records for the period 2020–2025. The dataset is intended for applications in health analytics, risk prediction, and data quality exercises.

---

## Dataset Details

- **Filename:** patient_health_dataset.csv
- **Total records:** Approximately 500
- **Primary key:** Patient_ID

---

## Data Dictionary

| Column Name        | Description                        | Data Type                   |
|-------------------|-----------------------------------|-----------------------------|
| Patient_ID         | Unique patient identifier          | String                      |
| Name               | Patient full name                  | String                      |
| Age                | Age in years                       | Integer                     |
| Gender             | Male / Female / Unknown            | Categorical                 |
| City               | Standardized city names            | Categorical                 |
| BMI                | Body Mass Index                    | Float                       |
| Systolic_BP        | Systolic (upper) blood pressure    | Integer                     |
| Diastolic_BP       | Diastolic (lower) blood pressure   | Integer                     |
| Heart_Rate         | Heart rate (beats per minute)      | Integer                     |
| Cholesterol_Level  | Cholesterol measurement            | Integer                     |
| Diabetic           | Diabetes status (Yes/No/Unknown)   | Categorical                 |
| Smoking_Status     | Smoking status (Yes/No/Former/Unknown) | Categorical             |
| Medications        | Prescribed medications             | String                      |
| Last_Visit_Date    | Date of most recent clinical visit | Date                        |
| Follow_Up          | Days until next scheduled visit    | Integer                     |

---

## Key Insights & Sample Statistics

- **Average age:** 34 years
- **Most common city:** New York
- **Proportion with diabetes:** 28%
- **Average BMI:** 22.4
- **Most common blood pressure reading:** 120/80

---

## Suggested Analyses

- Investigate the relationship between BMI and cholesterol levels
- Assess smoking status in relation to heart disease risk
- Examine age-related trends in blood pressure
- Evaluate the impact of medications on clinical outcomes

---

## Data Cleaning Summary

- Standardized inconsistent text values
- Normalized date formats
- Separated blood pressure into systolic and diastolic components
- Imputed or replaced missing values with sensible defaults
- Removed unit annotations from BMI
- Normalized categorical variables

---

## Tools Used

- Google Sheets
- Excel
- Python
