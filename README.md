# Patient Health Records Dataset 📊

This repository contains an anonymized dataset of patient medical records collected between **2020 and 2025**. It is designed for **health analytics**, **risk prediction**, and **data cleaning practice**.  

---

## 📁 Dataset Details

- **Filename:** `patient_health_dataset.csv`  
- **Total Records:** ~500  
- **Primary Key:** `Patient_ID`  

---

## 🗂 Data Dictionary

| Column Name        | Description                        | Data Type                   |
|-------------------|-----------------------------------|-----------------------------|
| Patient_ID         | Unique patient identifier          | String                      |
| Name               | Patient full name                  | String                      |
| Age                | Age in years                       | Integer                     |
| Gender             | Male / Female / Unknown            | Categorical                 |
| City               | Standardized city names            | Categorical                 |
| BMI                | Body Mass Index                    | Float                       |
| Systolic_BP        | Upper blood pressure value         | Integer                     |
| Diastolic_BP       | Lower blood pressure value         | Integer                     |
| Heart_Rate         | Beats per minute                   | Integer                     |
| Cholesterol_Level  | Cholesterol reading                | Integer                     |
| Diabetic           | Yes / No / Unknown                 | Categorical                 |
| Smoking_Status     | Yes / No / Former / Unknown        | Categorical                 |
| Medications        | Prescribed medicines               | String                      |
| Last_Visit_Date    | Date of last visit                 | Date                        |
| Follow_Up          | Days until next visit              | Integer                     |

---

## 📊 Key Insights & Statistics (Sample)

- **Average Age:** 34 years  
- **Most Common City:** New York  
- **Patients with Diabetes:** 28%  
- **Average BMI:** 22.4  
- **Most Common Blood Pressure:** 120/80  

---

## 🔍 Analysis Suggestions

- Correlation between **BMI** and **Cholesterol**  
- **Smoking** vs **Heart Disease Risk**  
- **Age** vs **Blood Pressure Trends**  
- **Medication Impact Analysis**  

---

## 🧹 Data Cleaning Notes

- Standardized inconsistent text values  
- Converted dates to uniform format  
- Split blood pressure into systolic/diastolic  
- Replaced missing values with defaults  
- Removed units from BMI  
- Normalized categorical columns  

---

## 🛠 Tools Used

- Google Sheets  
- Excel  
- Python  
