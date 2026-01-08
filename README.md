# 📊 Telecom Customer Churn Analysis

Welcome to the **Telecom Customer Churn Analysis** project!  
This is a real-world **Data Analytics case study** where telecom customer churn patterns are analyzed using **Python and Power BI** to provide actionable insights for customer retention.

---

## 📌 Objective

The main objectives of this project are:

- 🔍 Understand customer behavior and churn patterns  
- 📉 Identify key factors that lead to customer churn  
- 📈 Provide insights to improve customer retention and revenue  
- Simulate how a **Data Analyst** presents insights to business stakeholders

---

## 🧰 Tools & Technologies Used

| Tool       | Purpose |
|------------|--------|
| Python     | Data cleaning, preprocessing, and Exploratory Data Analysis (EDA) |
| Pandas & NumPy | Handling datasets, aggregation, and numerical analysis |
| Matplotlib & Seaborn | Visualization of churn patterns and trends |
| Power BI   | Interactive dashboards and visual storytelling |

---

## 📂 Dataset Summary

- **Dataset File:** `WA_Fn-UseC_-Telco-Customer-Churn.csv`  
- **Customer Demographics:** Gender, Senior Citizen, Partner, Dependents  
- **Account Information:** Tenure, Contract, Payment Method, Monthly & Total Charges  
- **Services:** Internet, Phone, Streaming, etc.  
- **Target Variable:** `Churn` (Yes / No)  
- **Format:** CSV

---

## 📊 Business Questions & Analysis

### 🔸 1. Churn vs Contract Type
- Objective: Understand which contract type has the highest churn  
- Visuals: Bar charts & stacked column charts  

### 🔸 2. Churn vs Tenure
- Objective: Analyze whether shorter tenure increases churn probability  
- Visuals: Histogram & line plots  

### 🔸 3. Churn vs Monthly Charges
- Objective: Identify if higher monthly charges lead to churn  
- Visuals: Scatter plots & boxplots  

### 🔸 4. Churn vs Payment Method
- Objective: Determine if payment method affects churn rates  
- Visuals: Pie charts & bar charts  

### 🔸 5. Correlation Analysis
- Objective: Explore relationships between numerical features and churn  
- Visuals: Heatmaps

---

## 📌 Power BI Dashboard Overview

The Power BI dashboard provides:

- Interactive slicers for **contract type, tenure, and payment method**  
- Drill-down functionality for detailed insights  
- KPI cards highlighting **churn percentage, average tenure, and monthly charges**  
- Clean, business-friendly visuals  

Each visual answers a specific business question clearly.

---

## 🔍 Python Exploratory Data Analysis (EDA)

Using **Pandas & Seaborn / Matplotlib**, the following steps were performed:

- Handling missing values and duplicates  
- Data type conversion and preprocessing  
- Grouped aggregations for churn counts  
- Visualizations for churn patterns across different features  
- Correlation and distribution analysis

---

## 🚀 Key Takeaways

- Customers with **month-to-month contracts** are more likely to churn  
- Shorter tenure customers have **higher churn probability**  
- Higher **monthly charges** increase churn likelihood  
- Payment method (electronic checks) impacts churn behavior  
- Hands-on experience with **data cleaning, EDA, and dashboard creation**

---

## 📁 Project Structure

```text
📦 Telecom-Customer-Churn-Project/
│
├── 📊 Power BI Dashboard
│   └── PowerBI_Dashboard.pbix
│
├── 🐍 Python Analysis
│   └── telco_customer_churn.ipynb
│
├── 📈 Dataset
│   └── WA_Fn-UseC_-Telco-Customer-Churn.csv
│
└── 📄 README.md
