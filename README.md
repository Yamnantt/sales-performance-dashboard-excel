# 📊 Sales Performance Dashboard (Excel)

## 📌 Project Overview
Built a dynamic Sales Performance Dashboard in Excel to analyze revenue trends, regional performance, and product contribution.

This project focuses on building stable KPI logic outside PivotTables to avoid slicer-related errors.




---

## 🎯 Business Problem

- YoY % showing #N/A
- Pivot becoming empty when slicer changed
- KPIs breaking due to Pivot dependency

---

## 🛠 Solution Approach

- Created structured Sales_fact table
- Calculated Year and Month columns
- Used SUMIFS for Current vs Previous Year logic
- Built error-proof YoY formula
- Separated KPI logic from PivotTables
- Connected slicers properly

---

## 📈 Key Features

- Dynamic Slicers (Year, Region, Product Category)
- Monthly Net Sales Trend
- Sales by Region
- Top 5 Products
- KPI Cards:
  - Total Sales
  - MoM Growth %
  - YoY Growth %
  - Best / Worst Month

---

## 🧠 Business Insights

- MoM improving trend
- YoY decline in selected region
- Revenue imbalance across regions
- Performance volatility across months

---

## 🏆 Key Learning

Dashboard is not about charts.
It is about structure, logic, and stability.

---

## 📂 Tools Used

- Microsoft Excel
- Power Query
- PivotTables
- SUMIFS
- LOOKUP
- Dynamic Slicers
