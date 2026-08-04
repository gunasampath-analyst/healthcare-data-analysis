# 🏥 Healthcare Data Analysis | Exploratory Data Analysis (EDA)

> **Transforming raw healthcare data into actionable business insights using Python, statistical analysis, and data visualization.**

![Python](https://img.shields.io/badge/Python-Data%20Analysis-3776AB?logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Manipulation-150458?logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-013243?logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Visualization-purple)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter&logoColor=white)

---

# 📖 Executive Summary

Healthcare organizations generate vast amounts of operational and patient data every day. Extracting meaningful insights from this information enables hospitals to improve operational efficiency, optimize resource utilization, reduce healthcare costs, and enhance patient care.

This project performs a comprehensive **Exploratory Data Analysis (EDA)** on a real-world healthcare dataset containing over **55,000 patient records**. Using Python and industry-standard data analytics libraries, the analysis uncovers trends in patient demographics, hospital admissions, medical conditions, billing patterns, insurance providers, and length of hospital stay.

The project demonstrates an end-to-end analytical workflow—from data cleaning and feature engineering to visualization and business insight generation.

---

# 🎯 Business Problem

Healthcare providers must answer critical business questions such as:

- Which medical conditions generate the highest healthcare costs?
- Which hospitals contribute the most to overall revenue?
- How do insurance providers impact billing patterns?
- What factors influence longer hospital stays?
- How can patient demographics support healthcare planning?

Without systematic analysis, identifying these trends becomes difficult and limits strategic decision-making.

---

# 🎯 Project Objectives

The primary objectives of this analysis are to:

- Analyze patient demographics and healthcare utilization
- Identify the most common medical conditions
- Evaluate hospital billing performance
- Compare healthcare costs across insurance providers
- Study admission trends and patient flow
- Measure hospital length of stay
- Generate actionable insights through visual analytics

---

# 📂 Dataset Information

| Attribute | Details |
|------------|---------|
| Dataset | Healthcare Dataset |
| Source | Kaggle |
| Records | **55,500** |
| Features | **15** |
| Data Type | Structured Healthcare Data |

### Dataset Includes

- Patient Information
- Age & Gender
- Blood Type
- Medical Conditions
- Hospital Information
- Admission Details
- Insurance Provider
- Billing Amount
- Medications
- Test Results

---

# 🛠 Tech Stack

| Technology | Purpose |
|------------|----------|
| Python | Data Analysis |
| Pandas | Data Cleaning & Manipulation |
| NumPy | Numerical Analysis |
| Matplotlib | Data Visualization |
| Seaborn | Statistical Visualization |
| Jupyter Notebook | Development Environment |

---

# 🔄 Project Workflow

```text
Healthcare Dataset
        │
        ▼
Data Understanding
        │
        ▼
Data Cleaning
        │
        ▼
Data Preprocessing
        │
        ▼
Feature Engineering
        │
        ▼
Exploratory Data Analysis
        │
        ▼
Statistical Analysis
        │
        ▼
Data Visualization
        │
        ▼
Business Insights & Recommendations
```

---

# 🧹 Data Preparation

The dataset was cleaned and transformed through the following preprocessing steps:

- Inspected dataset structure and data types
- Checked for missing values
- Removed duplicate records
- Converted date columns into datetime format
- Created new analytical features:
  - Length of Stay
  - Age Group
  - Admission Month
- Validated data consistency
- Generated summary statistics

---

# 📊 Business Questions Addressed

## 👥 Patient Analytics

- Which medical conditions are most prevalent?
- Which age groups require the highest healthcare services?
- What is the gender distribution of patients?

---

## 💰 Financial Analytics

- Which medical conditions generate the highest billing?
- Which hospitals contribute the greatest revenue?
- How do insurance providers compare in billing amounts?

---

## 🏥 Operational Analytics

- What is the average hospital length of stay?
- Which admission type occurs most frequently?
- Is there a relationship between hospital stay duration and billing amount?

---

# 📈 Exploratory Analysis

The project includes analysis on:

- Patient Demographics
- Medical Conditions
- Hospital Billing
- Insurance Providers
- Admission Types
- Monthly Billing Trends
- Length of Stay
- Correlation Analysis
- Statistical Summary
- Feature Engineering

---

# 💡 Key Business Insights

## 💰 Revenue Insights

- Certain medical conditions account for a significantly larger proportion of total healthcare billing.
- Hospital revenue distribution varies considerably across institutions.

---

## 🏥 Operational Insights

- Longer hospital stays generally lead to increased billing amounts.
- Admission trends provide valuable information for workforce planning and resource allocation.

---

## 👥 Patient Insights

- Patient demographics reveal distinct healthcare utilization patterns.
- Age groups and medical conditions influence hospitalization frequency.

---

## 📌 Business Recommendations

- Improve resource allocation for high-volume medical conditions.
- Monitor long-duration hospital stays to optimize operational efficiency.
- Collaborate with insurance providers showing higher healthcare expenditure.
- Use monthly admission trends for workforce and capacity planning.
- Build predictive models to estimate future healthcare costs.

---

# 📷 Project Visualizations

## 💰 Total Billing by Medical Condition

![Billing by Medical Condition](images/billing_by_condition.png)

---

## 🏥 Top Hospitals by Total Billing

![Hospital Billing](images/hospital_billing.png)

---

## 📈 Monthly Billing Trend

![Monthly Billing](images/monthly_billing.png)

---

## 🏨 Distribution of Length of Stay

![Length of Stay](images/length_of_stay.png)

---

## 🩺 Length of Stay by Medical Condition

![Length of Stay by Condition](images/length_of_stay_my_medical_condition.png)

---

## 🚑 Admission Type Distribution

![Admission Types](images/admission_type_distribution.png)

---

## 🧪 Test Result Distribution

![Test Results](images/test_results.png)

---

# 📁 Project Structure

```text
Healthcare-Data-Analysis
│
├── data
│   └── healthcare_dataset.csv
│
├── notebooks
│   └── hc.ipynb
│
├── images
│   ├── billing_by_condition.png
│   ├── hospital_billing.png
│   ├── monthly_billing.png
│   ├── length_of_stay.png
│   ├── admission_type_distribution.png
│   └── ...
│
├── requirements.txt
│
└── README.md
```

---

# 🚀 Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Data Wrangling
- Feature Engineering
- Statistical Analysis
- Business Intelligence
- Data Visualization
- Insight Generation
- Python Programming

---

# 🔮 Future Enhancements

- Develop an interactive Power BI dashboard
- Deploy a Streamlit web application
- Integrate SQL-based analytical queries
- Perform predictive modeling for healthcare cost estimation
- Apply machine learning techniques for patient risk prediction

---

# ▶️ How to Run the Project

Clone the repository:

```bash
git clone https://github.com/yourusername/Healthcare-Data-Analysis.git
```

Navigate to the project directory:

```bash
cd Healthcare-Data-Analysis
```

Install the required libraries:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open **hc.ipynb** and run all cells.

---

# 👨‍💻 Author

## Guna Sampath

**Aspiring Data Analyst | MCA Student**

Passionate about transforming raw data into actionable business insights using **Python, SQL, Power BI, Excel, and Data Visualization**.

### Skills

- Python
- SQL
- Power BI
- Excel
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Business Intelligence

---

## ⭐ If you found this project useful, consider giving it a Star!
