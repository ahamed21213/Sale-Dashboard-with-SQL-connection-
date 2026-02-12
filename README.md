📊 Sale Dashboard with SQL Connection
SalesAnalysis_SQL_PowerBI
🚀 Project Overview

This project presents an end-to-end Sales Analytics solution built using SQL Server (AdventureWorks Data Warehouse) and Power BI Desktop.

The objective is to analyze sales performance, monitor KPIs, and generate actionable business insights for management decision-making.

It demonstrates the complete analytics workflow:

SQL Database → Data Cleaning (T-SQL) → Data Modeling → DAX Measures → Interactive Power BI Dashboard

🛠 Tech Stack

SQL Server (Express Edition)

SQL Server Management Studio (SSMS)

T-SQL

AdventureWorks Data Warehouse

Power BI Desktop

DAX

Star Schema Data Modeling

🗂 Data Source & Setup
Requirements

SQL Server (SQL Express)

Power BI Desktop

Database Installation

Download and restore AdventureWorks databases:

🔗 https://docs.microsoft.com/en-us/sql/samples/adventureworks-install-configure?view=sql-server-ver15&tabs=ssms

Update Data Warehouse using SQL script:

🔗 https://github.com/techtalkcorner/SampleDemoFiles/blob/master/Database/AdventureWorks/Update_AdventureWorksDW_Data.sql

We work mainly with:

AdventureWorksDW (Data Warehouse)

Compare with AdventureWorksLT (Lightweight transactional DB)

This helps understand:

Structured vs Transactional data

Fact vs Dimension tables

Data warehouse architecture

📌 Business Objective

The dashboard answers key business questions:

What is the total sales and profit performance?

Which products generate the highest revenue?

Which regions perform best?

How do sales trends change over time?

How does actual sales compare to budget?

🧹 Data Cleaning using T-SQL

Performed data transformation using:

LEFT JOIN

WHERE clause

ORDER BY

CASE() function

ISNULL() function

Column renaming

Derived columns

SQL formatting & commenting

Tables Used

FactInternetSales

DimDate

DimCustomer

DimProduct

DimSalesTerritory

FactBudget

Implemented Fact & Dimension relationship structure (Star Schema).

📊 Data Modeling in Power BI

Connected Fact & Dimension tables

Created relationships

Imported Budget table

Built dedicated Measure Table

Created DAX Measures:

Total Sales

Total Profit

Profit Margin

Sales vs Budget

Quantity Sold

Top 10 Products

📈 Dashboard Features

✔ KPI Cards (Sales, Profit, Quantity)
✔ Line Chart (Sales Trend Over Time)
✔ Pie Chart (Category Contribution)
✔ Bar Charts (Top & Bottom Products)
✔ Map Visualization (Regional Sales)
✔ Budget vs Actual Comparison
✔ Gradient Conditional Formatting
✔ Customer Drill-down View
✔ Pivot Table Analysis

🖼 Dashboard Preview

(Add your screenshots here — already included above)

📥 Dashboard Files

🔹 Download Power BI File (.pbix):
https://github.com/AsifRashid01/SalesAnalysis_SQL_PowerBI/blob/main/Sales%20Report.pbix

🔹 View Dashboard PDF:
https://github.com/AsifRashid01/SalesAnalysis_SQL_PowerBI/blob/main/Sales%20Report.pdf

🎯 Skills Demonstrated

SQL Query Writing

Data Cleaning & Transformation

Data Warehousing Concepts

Star Schema Modeling

DAX Calculations

Business Intelligence Reporting

Dashboard Design

Analytical Thinking

💡 Project Value

This project simulates a real-world business scenario where management requires clear and actionable insights from structured sales data.

It transforms raw warehouse data into measurable KPIs and interactive business reports
