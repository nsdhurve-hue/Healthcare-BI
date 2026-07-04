# Healthcare Stroke Data Analysis Report

## 1. Project Overview

This project analyzes a healthcare dataset containing patient demographic information, medical history, lifestyle factors, and stroke outcomes. The objective is to identify the major factors associated with stroke risk and present meaningful insights through interactive Power BI visualizations.

The dashboard enables healthcare professionals, researchers, and decision-makers to explore patient characteristics and understand the relationship between medical conditions and stroke occurrence.

---

# 2. Dataset Description

**Dataset Name:** Healthcare Stroke Prediction Dataset

The dataset contains medical records of patients collected for stroke prediction analysis.

### Dataset Summary

* Total Records: **5,110**
* Total Columns: **12**
* Missing Values: **201** (BMI column)
* Target Variable: **stroke**

### Data Dictionary

| Column            | Description                                                       |
| ----------------- | ----------------------------------------------------------------- |
| id                | Unique patient identifier                                         |
| gender            | Gender of the patient                                             |
| age               | Age in years                                                      |
| hypertension      | Indicates whether the patient has hypertension (0 = No, 1 = Yes)  |
| heart_disease     | Indicates whether the patient has heart disease (0 = No, 1 = Yes) |
| ever_married      | Marital status                                                    |
| work_type         | Employment category                                               |
| Residence_type    | Urban or Rural residence                                          |
| avg_glucose_level | Average blood glucose level                                       |
| bmi               | Body Mass Index                                                   |
| smoking_status    | Smoking habit of the patient                                      |
| stroke            | Stroke occurrence (0 = No, 1 = Yes)                               |

---

# 3. Data Quality Assessment

The dataset is generally clean and well structured.

### Missing Values

* BMI contains **201 missing values**.
* No missing values exist in the remaining columns.

### Data Types

* Numerical Columns

  * Age
  * Average Glucose Level
  * BMI

* Categorical Columns

  * Gender
  * Work Type
  * Residence Type
  * Smoking Status
  * Ever Married

* Binary Columns

  * Hypertension
  * Heart Disease
  * Stroke

---

# 4. Dataset Statistics

### Total Patients

**5,110**

### Average Age

Approximately **43 years**

### Average BMI

Approximately **28.9**

### Average Glucose Level

Approximately **106 mg/dL**

### Stroke Cases

* Stroke = 1: **249 patients**
* No Stroke = 0: **4,861 patients**

Stroke prevalence is approximately **4.87%** of the dataset.

---

# 5. Demographic Analysis

## Gender Distribution

The dataset contains patients from three gender categories.

* Female: 2,994
* Male: 2,115
* Other: 1

The dataset is slightly female dominant.

---

## Residence Analysis

Patients are almost equally distributed between:

* Urban
* Rural

This provides balanced geographical representation.

---

## Work Type Analysis

Employment categories include:

* Private
* Self-employed
* Government Job
* Children
* Never Worked

Private sector employees represent the largest group.

---

## Smoking Status Analysis

Smoking information includes:

* Never Smoked
* Formerly Smoked
* Smokes
* Unknown

A significant number of records have an unknown smoking status, which should be considered during interpretation.

---

# 6. Medical Condition Analysis

## Hypertension

Most patients do not have hypertension.

Only a small percentage of patients are diagnosed with hypertension.

---

## Heart Disease

Heart disease cases are much lower than non-heart disease cases, indicating that the dataset is largely composed of healthy individuals with respect to cardiovascular disease.

---

# 7. Stroke Analysis

The dataset is highly imbalanced.

* Non-Stroke Cases: Approximately 95%
* Stroke Cases: Approximately 5%

This imbalance should be considered when developing predictive machine learning models, as accuracy alone may not be an appropriate evaluation metric.

---

# 8. Dashboard Visualizations

The Power BI dashboard includes visualizations designed to analyze the dataset effectively.

Typical visuals include:

* KPI Cards
* Bar Charts
* Column Charts
* Pie Charts
* Donut Charts
* Scatter Charts
* Treemap
* Gauge Chart
* Funnel Chart
* Matrix/Table
* Slicers for interactive filtering

These visuals allow users to compare patient demographics, medical conditions, and stroke outcomes dynamically.

---

# 9. Key Insights

* The dataset contains over five thousand patient records.
* Stroke occurrence is relatively rare (about 4.9%).
* Female patients slightly outnumber male patients.
* Urban and rural populations are nearly equal.
* Private-sector workers form the largest employment category.
* BMI contains missing values that should be handled before advanced analysis.
* Hypertension and heart disease are important medical factors associated with stroke risk.
* Average glucose level and age are valuable continuous variables for identifying high-risk patients.

---

# 10. Business Value

This dashboard can help healthcare organizations:

* Monitor patient demographics.
* Identify populations at higher risk of stroke.
* Support preventive healthcare initiatives.
* Improve clinical decision-making.
* Assist researchers in exploring stroke-related patterns.
* Provide interactive reporting for hospital administrators.

---

# 11. Skills Demonstrated

* Data Cleaning
* Data Transformation
* Power BI Dashboard Development
* DAX Calculations
* Data Modeling
* Healthcare Analytics
* Business Intelligence Reporting
* Interactive Data Visualization

---

# 12. Conclusion

The Healthcare Stroke Dashboard provides a comprehensive overview of patient demographics, health conditions, and stroke incidence. By combining statistical summaries with interactive visualizations, the report enables users to identify important healthcare trends and supports evidence-based decision-making. The dataset also serves as a strong foundation for predictive analytics and machine learning models aimed at early stroke risk detection.
