# 🛒 Reliance Smart Sales Report 

This Power BI project analyzes sales and return data from a retail chain called **Reliance Smart**. The goal is to uncover actionable insights across customer behavior, product performance, store types, and regional trends using interactive dashboards.

---

## 📄 Project Description

The Reliance Smart Sales Report provides a comprehensive view of sales, profitability, and returns over a two-year period (1997–1998). It allows business stakeholders to:
- Compare revenue, profit, and returns monthly
- Understand product-level performance
- Analyze customer segments by gender, priority level, and member card type
- Evaluate store and region-wise effectiveness
- Track return quantities by products and brands

The project is divided into two key dashboards:
1. **Primary Dashboard** – high-level performance insights
2. **Distribution Dashboard** – return trends, store and product-level performance

---

## 📦 Data Overview

The report is built using structured datasets that include:

| Table Name        | Description |
|-------------------|-------------|
| `d_Customers`     | Customer demographics, membership info, and segmentation flags |
| `d_Products`      | Product brand, category, price, cost, fat content, recyclable flag |
| `d_Stores`        | Store location, type, square footage, opening dates |
| `d_Regions`       | Sales region and district info |
| `f_Transactions`  | Sales transactions (product, customer, store, quantity, date) |
| `f_Returns`       | Product return quantities per store and date |
| `d_Calendar`      | Date intelligence with month, quarter, year, day names, weekend flag |

---

## 📊 Key Metrics (DAX Measures)

- `M_Total_Revenue`: Total revenue = ∑ (Quantity × Discounted Price)
- `M_Total_Cost`: Total product cost = ∑ (Quantity × Cost)
- `M_Total_Profit`: Revenue - Cost
- `M_Profit_Margin`: Profit ÷ Revenue
- `M_Qty_Return`: Total quantity returned
- `M_Total_Transactions`: Total number of Transactions 
- `M_Previous_Month_Revenue`, `M_Previous_Month_Profit`, etc.
- `M_YTD_Revenue`: Year-to-date revenue

---

## 📊 Dashboards Overview

### 1. **Primary Report**
A high-level overview of business performance and customer trends.

**Key Visuals:**
- 🔼 **Revenue, Profit & Returns vs. Previous Month** (with goal indicators)
- 📦 **Total Quantity Sold**
- 📅 **Total Profit by Month**
- 🍔 **Quantity Sold by Fat Category**
- 💳 **Total Revenue by Member Card Type**
- 🥇 **Top 10 Products by Profit**
- 🌍 **Transactions by Country and Day**
- 📅 **Transactions by Weekdays**
- 🔘 Filters: Year (1997/1998), Gender

---

### 2. **Distribution Report**
Focuses on return analysis, regional/store performance, and brand-level insights.

**Key Visuals:**
- 🏪 **Store Type Wise Revenue**
- 🌎 **Country Wise Profit Share**
- 🧾 **Top 10 Returned Products**
- 🏷️ **Product Brand-Wise Summary Table**
- 🗺️ **State Wise Transactions (Tree Map)**
- 📍 **Region Wise Revenue (Map View)**
- 🔘 Filters: Year (1997/1998), Priority Level (High/Standard)

---

## 📌 Key Insights

- 🥇 Bronze member cardholders generate 56% of the revenue.
- 🧼 High-fat items contribute over 65% of total quantity sold
- 📆 December consistently shows the highest profits
- 🇺🇸 USA dominates profit share (66.75%)
- 🧾 Top profitable brand: Hermanos
- 🧃 Most returned product: Hermanos Red Pepper
- 🛒 Store Type with Highest Revenue: Supermarket

 🧠 Skills Demonstrated

- **Power BI**: Dashboard creation, slicers, maps, tree maps, KPI cards, donut charts
- **DAX**: Custom measures (profit, revenue, returns, YTD, margin)
- **Power Query**: Data cleaning, transformations, type casting, column creation
- **Data Modeling**: Relationships across fact and dimension tables
- **Data Analysis**: Deriving business insights from raw data

🚀 This project demonstrates a complete end-to-end Power BI reporting solution—covering data transformation, modeling, DAX measure creation, and insightful dashboard design—highlighting my proficiency in turning raw data into actionable business intelligence.
