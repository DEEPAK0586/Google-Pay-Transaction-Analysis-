# 💳 Google Pay Transaction Analysis Dashboard | Power BI

## 📌 Project Overview

This project focuses on analyzing Google Pay transaction data using Microsoft Power BI. The dashboard provides insights into transaction performance, customer spending patterns, payment methods, merchant performance, and transaction status.

The interactive dashboard helps understand business performance through KPIs, charts, and dynamic filters.

## 🎯 Project Objectives

- Analyze overall transaction performance.
- Identify monthly transaction trends.
- Understand category-wise spending patterns.
- Analyze transaction success and failure rates.
- Identify top-performing merchants and cities.
- Understand payment method distribution.

## 🛠️ Tools & Technologies

- **Power BI Desktop** – Dashboard development and visualization.
- **Power Query** – Data cleaning and transformation.
- **DAX** – Calculated measures and KPIs.
- **Data Modeling** – Fact and Dimension tables.

## 📊 Dashboard KPIs

| KPI | Value |
|---|---:|
| Total Transactions | 5,000 |
| Total Amount | 11.06M |
| Average Transaction | 2.21K |
| Successful Transactions | 4,572 |
| Success Rate | 91.44% |

*Values represent the overall dashboard snapshot and may change with filters.*

## 📈 Dashboard Visualizations

1. **Monthly Transaction Trend** – Analyzes transaction patterns across months.
2. **Spending by Category** – Displays category-wise transaction amounts.
3. **Transaction Status Distribution** – Shows successful, failed, and pending transactions.
4. **Top 10 Merchants** – Identifies merchants based on transaction amount.
5. **City-wise Transaction Analysis** – Compares transaction amounts across cities.
6. **Payment Method Distribution** – Analyzes the usage of different payment methods.

## 🎛️ Interactive Filters

The dashboard includes the following slicers:

- Date Range
- Category
- City
- Payment Method
- Transaction Status

These filters allow users to explore transaction data dynamically.

## 🗂️ Data Model

The project follows a dimensional data modeling approach.

**Fact Table:**
- Fact_Transactions

**Dimension Tables:**
- Dim_Date
- Dim_Category
- Dim_Merchant

Relationships are established using primary and foreign keys to enable effective data analysis.

## 📐 DAX Measures

The dashboard uses DAX measures for calculating:

- Total Transactions
- Total Amount
- Average Transaction
- Successful Transactions
- Success Rate

## 💡 Key Insights

- Achieved an overall transaction success rate of 91.44%.
- Shopping contributes the highest spending among categories.
- Chennai records the highest transaction amount among the displayed cities.
- TNEB and Water Board are among the leading merchants by transaction amount.
- UPI is the most frequently used payment method in the displayed dataset.

## 📷 Dashboard Preview

![Google Pay Transaction Analysis Dashboard](dashboard.png)

## 🚀 How to Use

1. Clone or download this repository.
2. Install Microsoft Power BI Desktop.
3. Open the `.pbix` project file.
4. Refresh the dataset if required.
5. Explore the dashboard using interactive slicers and visualizations.

## 👨‍💻 Author

**Deepak Kishore A**

Aspiring Data Analyst | B.Sc Computer Science

Skills: SQL | Python | Excel | Power BI

---

⭐ If you find this project useful, consider giving this repository a star!
