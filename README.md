# 📊 Customer Churn Analysis Dashboard

## 🚀 Project Overview

This project analyzes customer churn patterns in a telecom company using **Power BI, Power Query, DAX, and Excel**.

The objective is to identify key churn drivers, evaluate revenue impact, and provide actionable insights to improve customer retention.

- **Total Records Analyzed:** 7,043 Customers  
- **Total Features:** 21 Columns  
- **Domain:** Telecom Customer Analytics  

---

## 🎯 Business Objective

Telecom companies face revenue loss due to customer churn.

This project aims to:

- Identify high-risk customers  
- Analyze revenue contribution & customer lifetime value  
- Understand contract and service impact on churn  
- Support data-driven retention strategy  

---

## 🗂 Dataset Description

Each record represents a telecom customer and includes:

- Demographics (Gender, Senior Citizen, Dependents)
- Service Details (Internet, Streaming, Tech Support)
- Contract Information
- Billing & Payment Data
- Monthly & Total Charges
- Churn Status

---

## 🧹 Data Cleaning & Transformation (Power Query)

- Corrected data types  
- Converted `TotalCharges` from text to numeric  
- Replaced blank values with `null`  
- Created numeric churn indicator (`Churn_Flag`)  
- Generated derived analytical columns  

---

## ⚙️ Feature Engineering

### 🔹 Churn_Flag  
Converted `Churn (Yes/No)` → `1/0` for numeric analysis.

### 🔹 Average Revenue Per Month (ARPU Logic)
- TotalCharges / tenure

### 🔹 Customer Lifetime Value (CLV Proxy)
- MonthlyCharges × tenure

### 🔹 Customer Value Segmentation
- Customers categorized into:
  - Low Value
  - Medium Value
  - High Value
  - No Charges Yet
 
---

## 📈 Key Performance Indicators (KPIs)

The dashboard tracks:

- Total Customers  
- Churned Customers  
- **Churn Rate (%)**  
- Total Revenue  
- Average Revenue Per Customer  
- Average Tenure  

---

## 📊 Key Insights

- Month-to-month contracts show highest churn rate  
- Fiber optic users exhibit higher churn risk  
- High monthly charges correlate with increased churn  
- Electronic check payment method shows higher churn tendency  
- New customers (low tenure) are more likely to churn  
- High-value customer churn poses significant revenue risk  

---

## 💡 Business Recommendations

- Encourage long-term contracts to reduce churn  
- Develop targeted retention campaigns for high-risk segments  
- Monitor high-value customers closely  
- Improve onboarding experience for new customers  
- Optimize pricing and payment flexibility  

---
## 🛠 Tools & Technologies Used

- Power BI  
- Power Query  
- DAX  
- Microsoft Excel  

---

## 📌 Project Deliverables

- Interactive Power BI Dashboard  
- Business KPI Metrics  
- Customer Segmentation Analysis  
- Executive-Level Insights  

---

## 📷 Dashboard Preview

![Dashboard]()

---
