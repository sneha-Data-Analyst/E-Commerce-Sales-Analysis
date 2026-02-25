# E-Commerce-Sales-Analysis
End-to-end E-Commerce Sales Analysis using Power BI: Data cleaning, modeling, KPI development, and interactive dashboard reporting.
# 📊 Power BI – E-Commerce Sales Analysis

## 📌 Project Overview
This project demonstrates an end-to-end data analysis workflow using Power BI. 
The objective was to transform raw e-commerce sales data into meaningful business insights through structured data modeling and interactive dashboard development.

---

## 🗂 Dataset Used
The project uses three CSV files:
- List of Orders.csv
- Order Details.csv
- Sales Target.csv

---

## 🔹 Phase 1: Data Transformation & Modeling

- Imported multiple CSV datasets into Power BI
- Restricted dataset to first 500 rows
- Standardized data types (Date, Fixed Decimal Number)
- Created calculated column: **Profit Margin (%)**
- Created conditional column: **Profit Status (Loss / Break-Even / Profit)**
- Merged tables using Order ID
- Established relationships between:
  - List of Orders ↔ Order Details
  - Order Details ↔ Sales Target
- Handled missing values and duplicate records

---

## 🔹 Phase 2: Data Visualization & Dashboard Development

- Designed interactive dashboard for sales performance analysis
- Created KPIs:
  - Total Sales
  - Total Profit
  - Profit Margin
- Built visuals for:
  - Category-wise performance
  - Regional (State-wise) analysis
  - Monthly sales trends
- Applied filters and slicers for dynamic reporting

---

## 🛠 Tools & Technologies
- Microsoft Power BI
- Power Query
- Data Modeling
- DAX

---

## 🎯 Key Learning Outcomes
- Improved hands-on experience in data cleaning and transformation
- Built relational data models using real-world datasets
- Developed interactive dashboards for business decision-making
- Strengthened analytical thinking and reporting skills

---

## 📌 Project Structure

PowerBI-Ecommerce-Sales-Analysis  
│  
├── 1_Data_Modeling  
├── 2_Data_Visualization  
├── Dataset  
└── README.md
