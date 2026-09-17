# 🏦 BankPulse — Bank Customer Churn Analysis

> Turning customer data into actionable banking insights using **SQL + Power BI**

---

## 📌 Project Overview

**BankPulse** is a Bank Customer Churn Analysis project built to understand customer behaviour, identify churn patterns, and find customer segments that may need more attention.

The project combines **SQL analysis** with an interactive **Power BI dashboard** to move from raw customer data to meaningful business insights.

### 🎯 Business Question

**Why are customers leaving the bank, and which customer segments show different churn patterns?**

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| 🗄️ **SQL** | Data exploration and business analysis |
| 📊 **Power BI** | Interactive dashboard and visualization |
| 📐 **DAX** | KPI and churn calculations |
| 📁 **Excel / CSV** | Dataset and data preparation |

---

## 📊 Dashboard Overview

The Power BI dashboard is divided into four sections:

### 1️⃣ Overview
Provides a high-level view of the bank's customer base and churn performance.

**Includes:**
- Total Customers
- Retained Customers
- Churned Customers
- Overall Churn Rate
- Churn by Geography
- Churn by Age Group
- Churn by Gender
- Churn by Product Count
- Churn by Active Member Status

### 2️⃣ Customer Details & Segmentation

Focuses on understanding the customer profile and segmentation.

**Includes:**
- Customer demographics
- Geography
- Age groups
- Credit segments
- Product usage
- Customer financial characteristics
- Customer-level details

### 3️⃣ Key Churn Insights

This section focuses specifically on churn patterns and potential retention areas.

**Analysis includes:**
- Churn Rate by Geography
- Churn Rate by Age Group
- Churn Rate by Number of Products
- Active vs Inactive Customer Churn
- Key findings
- Business recommendations

### 4️⃣ Filters

An interactive filter page allows users to explore different customer segments dynamically.

**Filters include:**
- Geography
- Gender
- Age Group
- Credit Segment
- Active Member Status

---

## 🔍 SQL Analysis

The project contains SQL queries covering multiple business questions.

### 👥 Customer Analysis

- Total customer count
- Duplicate Customer ID check
- Customer distribution by Geography
- Gender analysis
- Age analysis
- Credit Score analysis
- Balance analysis
- Number of Products
- Tenure
- Active Member status
- Credit Card ownership

### 📉 Churn Analysis

- Total churned customers
- Retained customers
- Overall churn rate
- Churn by Geography
- Churn by Gender
- Churn by Age Group
- Churn by Credit Score Segment
- Churn by Balance Segment
- Churn by Number of Products
- Active vs Inactive customer churn

### 💰 High-Value Customer Analysis

The analysis also identifies high-value customers who have churned using:

- Balance
- Estimated Salary
- Geography

This helps explore customer segments where financial value and churn occur together.

---

## 📈 Key Findings

Some notable findings from the analysis:

| Metric | Finding |
|--------|---------|
| 📊 Overall Churn Rate | **52.78%** |
| 👤 50+ Customer Churn | **87.28%** |
| 💤 Inactive Customer Churn | **64.71%** |
| 🌍 Germany Churn Rate | **76.54%** |
| 🌍 Spain Churn Rate | **69.73%** |
| 📦 1 Product Churn | **67.09%** |

> **Note:** Churn rate alone does not represent the size of a customer segment. Segment customer counts should also be considered before making business decisions.

---

## 💡 Business Insights

The analysis highlights several areas that can be investigated further:

- Customers in different geographical regions show different churn patterns.
- Customer activity is associated with differences in churn.
- Older customer groups show noticeably different churn behaviour.
- Product count is associated with varying churn rates.
- High-value churned customers can be identified using balance and salary-related criteria.
- Combining multiple customer attributes can help identify specific segments for deeper retention analysis.

---

## 🎯 Business Objective

The main objective of this project is to help a bank:

- Understand customer churn behaviour
- Identify customer segments with higher churn
- Analyse customer activity and product usage
- Identify potentially valuable churned customers
- Support data-driven customer retention analysis

---

## 🧠 Skills Demonstrated

**SQL**
- Aggregations
- GROUP BY
- CASE statements
- Filtering
- HAVING
- Customer segmentation
- Business analysis

**Power BI**
- Dashboard design
- KPI cards
- Slicers
- Interactive filtering
- Data visualization
- Drill-down analysis
- Data storytelling

**DAX**
- Churn Rate
- Segment-based calculations
- KPI measures
- Filter-context analysis

---

## 📂 Project Structure

```text
BankPulse-Customer-Churn-Analysis/
│
├── 📁 Dataset/
│   └── customer_bank.csv
│
├── 📁 SQL/
│   └── bank_churn_analysis.sql
│
├── 📁 PowerBI/
│   └── Bank_Churn_Dashboard.pbix
│
├── 📁 Dashboard/
│   ├── overview.png
│   ├── customer-details.png
│   ├── key-insights.png
│   └── filters.png
│
└── 📄 README.md
```

Project Workflow

Raw Customer Data
       ↓
Data Exploration
       ↓
SQL Business Analysis
       ↓
Customer Segmentation
       ↓
DAX Calculations
       ↓
Power BI Dashboard
       ↓
Key Insights
       ↓
Business Recommendations





📸 Dashboard Preview

Overview

Customer Details

Key Insights

Filters

📁 Project Files
📊 Power BI Dashboard — Interactive .pbix dashboard
🗄️ SQL File — Business analysis queries
📁 Dataset — Customer churn dataset
📸 Dashboard Screenshots — Visual preview of the project
👩‍💻 About the Project

This project was created as part of my Data Analytics portfolio to strengthen my practical skills in SQL, Power BI, DAX and business-oriented data analysis.

The focus was not only on creating charts, but on connecting the analysis with real business questions and customer retention decisions.
