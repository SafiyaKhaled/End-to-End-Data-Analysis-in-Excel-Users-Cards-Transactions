# 📊 Customer, Cards & Transactions Analysis with Excel (Power Query + Power Pivot + DAX)

## 🔹 Project Overview
This project analyzes customer demographics, card usage, and transaction behavior using **Excel (Power Query, Power Pivot, Pivot Tables, and DAX)**.  
The dataset consists of:
- **Users Data**
- **Cards Data**
- **Transactions Data** (13M+ rows)

The goal was to integrate these datasets, clean them, and build an analytical model to generate insights and dashboards.

## 🔹 Data Processing
- **Power Query**:
  - Removed duplicates and null values.
  - Standardized column types (dates, numbers, text).
  - Ensured consistency between keys (User ID, Card ID, Transaction ID).

- **Data Modeling (Power Pivot)**:
  - Built relationships between **Users → Cards → Transactions**.
  - Created measures and KPIs using **DAX**.

## 🔹 KPIs & Measures (DAX)
- **Average Age of Customers** → `45`
- **% of Users with Debt** → `94%`
- **Number of Users with Debt** → `1,898`
- **Total Customers** → `2,000`
- **Near Retirement Customers** → `433`
- **Total Transaction Amount** → `571,835,522.28`
- **Total Transactions** → `13,305,915`
- **Average Transaction Value** → `42.98`
- **Total Debt Amount** → `-67,519,042.34`
- **Total Credit Amount** → `639,354,564.62`

## 🔹 Dashboards

### 1️⃣ Customer Insights Dashboard
- Age distribution of users.  
- Customers close to retirement.  
- Percentage and number of users with debt.  

### 2️⃣ Cards & Financials Dashboard
- Breakdown of **Credit vs Debt Amounts**.  
- KPIs of total customers, debt %, total debt, and total credit.  
- Card type analysis.  


### 3️⃣ Transactions Dashboard
- Total number of transactions (13M+).  
- Average transaction value.  
- Trend of transaction amounts over time.  
- Top customers by transaction amount.  


## 🔹 Tools & Skills Demonstrated
- **Excel** (Advanced)
  - Power Query
  - Power Pivot
  - Pivot Tables
  - DAX (Measures & KPIs)
- **Data Cleaning & Transformation**
- **Data Modeling & Relationships**
- **Dashboard Design & Visualization**


## 📌 Key Insights
- A large portion of customers (~94%) are in debt, with a negative balance of `-67.5M`.  
- Average customer age is **45**, with **433 near retirement**.  
- Transactions dataset contained **13M+ records**, successfully processed with Power Pivot.  
- Credit volume (`639M`) is significantly higher than debt (`67M`), showing overall financial strength.  


## 🚀 Conclusion
This project demonstrates how **Excel (Power Query + Power Pivot + DAX)** can be leveraged to handle millions of rows, build a solid data model, and generate actionable insights with interactive dashboards.  

