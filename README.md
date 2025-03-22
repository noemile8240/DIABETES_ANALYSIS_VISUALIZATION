# 🧪 Diabetes Health Metrics & Visualization

This project explores health and lifestyle factors linked to diabetes using the Pima Indian dataset. SQL was used for data analysis, and Tableau was used to visualize patterns in glucose levels, BMI, cholesterol, and medication usage across diabetic and non-diabetic patients.

---

## 📊 About the Data

This analysis uses the publicly available **Pima Indians Diabetes Dataset**, which contains data for 768 adult women of Pima Indian heritage. The dataset includes medical metrics such as glucose, BMI, cholesterol, blood pressure, and pregnancy count — with a binary outcome variable indicating diabetes status.

📍 Original data was sourced from [Kaggle](https://www.kaggle.com/).

---

## 🧠 SQL Analysis

All data cleaning, exploration, and question-based analysis were conducted using SQL. The SQL scripts for each question are organized in the [`/sql_analysis`](./sql_analysis) directory.

These scripts cover topics such as:
- Age and BMI distributions
- Glucose and cholesterol by diabetes outcome
- Medication usage
- Summary statistics
- Custom risk rule logic

---

## 📈 Interactive Dashboard

👉 [View the Tableau Dashboard](https://public.tableau.com/app/profile/noemi.vargas7800/viz/Diabetes-Analysis_17425868700190/DiabetesStudyDashboards?publish=yes)![image](https://github.com/user-attachments/assets/55623cc4-0d18-4007-8075-cd47058d6158)


This interactive dashboard showcases:
- Diabetes prevalence
- Glucose and BMI comparisons
- Cholesterol breakdowns
- Medication usage trends
- Pregnancy-related glucose patterns

---

## 🖼 Preview

![Dashboard Preview](./images/preview_dashboard.png)

---

## 📁 Project Structure

```
diabetes-analysis-project/
├── README.md
├── data/
│   └── diabetes.csv
├── sql_analysis/
│   ├── 01_age_distribution.sql
│   └── ... (more SQL scripts)
├── dashboard/
│   └── dashboard_link.txt
├── reports/
│   └── diabetes_indianwomen_study.md
├── images/
│   └── preview_dashboard.png
└── LICENSE
```
