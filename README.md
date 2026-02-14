# 📊 Sale Dashboard with SQL Connection  
## SalesAnalysis_SQL_PowerBI  

---

## 🚀 Project Overview

This project presents an end-to-end Sales Analytics solution built using **SQL Server (AdventureWorks Data Warehouse)** and **Power BI Desktop**.

The objective is to transform raw warehouse data into actionable business insights that support management decision-making.

It demonstrates the complete analytics workflow:

**SQL Server → T-SQL Data Cleaning → Star Schema Modeling → DAX Calculations → Interactive Power BI Dashboard**

---

## 🏗 Project Architecture

```
SQL Server (AdventureWorksDW)
        ↓
Data Cleaning using T-SQL
        ↓
Star Schema (Fact & Dimension Tables)
        ↓
Power BI Data Modeling
        ↓
DAX Measures & KPIs
        ↓
Interactive Dashboard & Business Insights
```

---

## 🛠 Tech Stack

- SQL Server (Express Edition)
- SQL Server Management Studio (SSMS)
- T-SQL
- AdventureWorks Data Warehouse
- Power BI Desktop
- DAX
- Star Schema Data Modeling

---

## 🗂 Data Source & Setup

### Requirements

- SQL Server (SQL Express)
- Power BI Desktop

### Database Installation

1. Download and restore **AdventureWorksDW** database  
2. Run the update script to refresh warehouse data  
3. Execute provided cleaning SQL scripts  
4. Open Power BI file and refresh the connection  

### Database Used

- AdventureWorksDW (Data Warehouse)  
- AdventureWorksLT (Transactional Database comparison)

This project demonstrates:

- Fact vs Dimension structure  
- Data warehouse architecture  
- Structured analytical data vs transactional systems  

---

## 📌 Business Objectives

The dashboard answers key business questions:

- What is the total sales and profit performance?  
- Which products generate the highest revenue?  
- Which regions perform best?  
- How do sales trends change over time?  
- How does actual sales compare to budget?  
- Which products contribute most to profit?  

---

## 🔎 Key Business Insights

- Top 15 products contribute 62% of total revenue.
- North America accounts for 48% of total sales but has 5% lower profit margin than Europe.
- Q4 sales are 18% higher than yearly average.
- 3 product categories are consistently below budget targets.
- Profit margin declined 4% compared to previous year. 

These insights help management optimize pricing, product strategy, and regional focus.

---

## 🧹 Data Cleaning Using T-SQL

Data transformation techniques applied:

- `LEFT JOIN`
- `WHERE` filtering
- `ORDER BY`
- `CASE()` function
- `ISNULL()` function
- Derived columns
- Column renaming
- Query formatting and documentation

### Tables Used

- FactInternetSales  
- DimDate  
- DimCustomer  
- DimProduct  
- DimSalesTerritory  
- FactBudget  

A proper **Star Schema relationship model** was implemented.

---

## 📊 Data Modeling in Power BI

- Established relationships between Fact & Dimension tables  
- Imported Budget table  
- Created a dedicated Measure Table  
- Implemented calculated columns and measures  

### DAX Measures Created

- Total Sales  
- Total Profit  
- Profit Margin %  
- Sales vs Budget  
- Quantity Sold  
- Top 10 Products  
- Year-over-Year Sales  
- Moving Average (Sales Trend)  

---

## 📈 Dashboard Features

✔ KPI Cards (Sales, Profit, Quantity)  
✔ Sales Trend Over Time (Line Chart)  
✔ Category Contribution (Pie Chart)  
✔ Top & Bottom Products Analysis  
✔ Regional Sales Map  
✔ Budget vs Actual Comparison  
✔ Profit Margin Analysis  
✔ Customer Drill-down View  
✔ Interactive Filters & Slicers  

---

## 📥 Dashboard Files

- `Sales Report.pbix`  
- `Sales Report.pdf`  

---

## 🧭 How to Run This Project

1. Install SQL Server Express & SSMS  
2. Restore AdventureWorksDW database  
3. Run provided T-SQL cleaning scripts  
4. Open Power BI file  
5. Update SQL connection if required  
6. Refresh data  

---

## 🎯 Skills Demonstrated

- SQL Query Writing  
- Data Cleaning & Transformation  
- Data Warehousing Concepts  
- Star Schema Modeling  
- Advanced DAX Calculations  
- Business Intelligence Reporting  
- Dashboard Design  
- KPI Development  
- Analytical Thinking  
- Business Insight Extraction  

---

## 💡 Project Value

This project simulates a real-world business reporting scenario where decision-makers require clear and actionable insights from structured warehouse data.

It demonstrates the ability to:

- Work with enterprise data warehouses  
- Build scalable analytical models  
- Create professional dashboards  
- Translate data into strategic business decisions  
