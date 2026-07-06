# 🚖 Ola Driver Attrition Analysis using Python

## 📌 Project Overview

Driver attrition is one of the biggest operational challenges for ride-hailing companies like Ola. High attrition increases recruitment costs, reduces service availability, and impacts overall business performance.

This project analyzes Ola's driver dataset using Python to identify the key factors influencing driver attrition through data cleaning, feature engineering, exploratory data analysis (EDA), and business insights.

---

## 🎯 Objectives

- Understand the driver attrition problem and its business impact.
- Perform data cleaning and preprocessing.
- Handle missing values using appropriate techniques.
- Create new analytical features through feature engineering.
- Explore driver demographics and performance trends.
- Analyze factors affecting driver attrition.
- Generate actionable business insights and recommendations.

---

## 📂 Dataset Information

The dataset contains driver demographic details, employment information, performance metrics, business value, income, and attrition-related attributes.

Key Columns include:

- Driver_ID
- Age
- Gender
- City
- Education_Level
- Dateofjoining
- LastWorkingDate
- Income
- Quarterly Rating
- Total Business Value

---

## 🛠 Tools & Libraries

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 📋 Project Workflow

### 1. Data Loading

- Imported dataset into Google Colab
- Loaded Excel file using Pandas

### 2. Data Exploration

- Dataset shape
- Data types
- Missing value analysis
- Statistical summary
- Unique driver count

### 3. Data Cleaning

- Missing value handling
- Date conversion
- Data validation

### 4. Feature Engineering

Created new analytical features:

- Attrition
- Tenure_Days
- Rating_Increased
- Income_Increased

### 5. Exploratory Data Analysis (EDA)

Performed analysis on:

- Age Distribution
- Income Distribution
- Quarterly Rating Distribution
- Total Business Value Distribution
- Monthly Joining Trend
- Monthly Leaving Trend
- Quarterly Rating Trend
- Monthly Income Trend
- Monthly Business Value Trend
- City-wise Attrition
- Income vs Attrition
- Quarterly Rating vs Attrition

---

## 📈 Key Business Insights

- Average driver age is approximately **34.67 years**.
- Average monthly income is around **₹65,652**.
- Average quarterly rating is **2.01**, indicating moderate driver performance.
- Lower income and lower quarterly ratings are associated with higher attrition risk.
- Attrition varies across different cities, highlighting the need for location-specific strategies.
- Performance and earnings are key factors influencing driver retention.

---

## 💡 Recommendations

- Introduce performance-based incentive programs.
- Improve earning opportunities for low-income drivers.
- Provide training and support for low-rated drivers.
- Implement city-specific retention strategies.
- Use predictive analytics to identify high-risk drivers.
- Conduct regular feedback and recognition programs.

---

## 📊 Project Outcome

The analysis successfully identified important demographic and performance factors associated with driver attrition. The findings can help Ola improve driver retention, reduce operational costs, and enhance workforce management through data-driven decision-making.

---

## 📁 Repository Structure

```
📦 ola-driver-attrition-analysis-python
│
├── Dataset.xlsx
├── Ola Driver Attrition Analysis.ipynb
├── Ola Driver Attrition Analysis.pdf
├── README.md
└── Images
      ├── Age Distribution.png
      ├── Income Distribution.png
      ├── Quarterly Rating Distribution.png
      ├── Total Business Value Distribution.png
      ├── Monthly Joining Trend.png
      ├── Monthly Leaving Trend.png
      ├── Quarterly Rating Trend.png
      ├── Monthly Income Trend.png
      ├── Monthly Business Value Trend.png
      ├── City Wise Attrition.png
      ├── Income vs Attrition.png
      └── Rating vs Attrition.png
```

---

## ⭐ Conclusion

This project demonstrates how Python can be used to perform end-to-end exploratory data analysis on operational datasets. By combining data preprocessing, feature engineering, visualization, and business insights, the analysis provides practical recommendations that can help improve driver retention and operational efficiency.
