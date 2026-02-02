# FUTURE_DS_02
Customer Churn &amp; Retention Analysis | Power BI + Python End-to-end churn analysis for a subscription-based telecom business using Python (EDA &amp; data cleaning) and Power BI (interactive dashboards). Identifies churn patterns, key retention drivers, customer lifetime trends, and provides actionable insights to reduce customer loss.
# Customer Churn & Retention Analysis – Telco Subscription Business

## 📌 Project Overview
Customer churn is one of the biggest challenges for subscription-based businesses.  
This project focuses on analyzing **customer churn behavior**, identifying **key retention drivers**, and understanding **customer lifetime trends** using real-world telecom data.

The analysis is performed using **Python for data cleaning & exploratory analysis** and **Power BI for interactive dashboarding**.

---

## 🎯 Objectives
- Identify churn patterns across customer segments
- Analyze key drivers influencing customer retention
- Study customer lifetime value (CLV) trends
- Build an interactive dashboard to support data-driven retention strategies

---

## 📂 Dataset
- **Source:** Kaggle – Telco Customer Churn Dataset
- **Records:** 7,043 customers
- **Target Variable:** Churn (Yes / No)

---

## 🛠 Tools & Technologies
- **Python:** Pandas, NumPy, Matplotlib, Seaborn
- **Power BI:** DAX, interactive dashboards
- **Data Analysis Techniques:** EDA, feature engineering, segmentation

---

## 🔄 Project Workflow

### 1️⃣ Data Cleaning & Preprocessing (Python)
- Handled missing and incorrect values (`TotalCharges`)
- Converted data types for analysis
- Created new features:
  - Tenure Groups
  - Service Count
  - Estimated Customer Lifetime Value (CLV)

### 2️⃣ Exploratory Data Analysis (EDA)
- Churn distribution analysis
- Churn by contract type, payment method, and services
- Tenure vs churn behavior
- Monthly charges impact on churn
- Customer lifetime value comparison

### 3️⃣ Power BI Dashboard Development
- Created a **2-page interactive dashboard**:
  - **Page 1:** Churn Overview
  - **Page 2:** Retention Drivers & Customer Lifetime Analysis
- Implemented DAX measures for:
  - Churn rate
  - Retention rate
  - Average tenure
  - Customer lifetime value

---

## 📊 Dashboard Pages

### 🔹 Page 1: Customer Churn Overview
- Total Customers
- Churn Rate & Retention Rate
- Churn distribution
- Churn by:
  - Contract Type
  - Payment Method
  - Internet Service
  - Tenure Group
- Interactive slicers for customer segmentation

### 🔹 Page 2: Retention Drivers & Customer Lifetime
- Average CLV and tenure
- Churn by tenure group
- Monthly charges vs churn
- Service count impact on churn
- High-risk customer segmentation table

---

## 🔍 Key Insights
- Month-to-month contracts show the highest churn
- Early-stage customers (0–1 year) are most likely to churn
- Automatic payment methods reduce churn significantly
- Customers with more subscribed services have lower churn
- Long-tenure customers contribute higher lifetime value

---

## 🚀 Business Recommendations
- Promote long-term contracts with incentives
- Encourage automatic payment methods
- Focus retention efforts on early-tenure customers
- Improve service quality for high-churn segments
- Bundle services to increase customer stickiness

---

