# AdventureWorks Business Intelligence & Data Engineering Project

## 📊 Overview
This repository contains my end-to-end BI and Data Engineering project developed during my internship at **Elevo Pathways**.  
It focuses on building a complete data pipeline and interactive analytics dashboard for **Adventure Works Cycles**, a global bike manufacturer.

---

## 🚀 Tools Used
- **Microsoft SQL Server** – OLTP and Data Warehouse databases  
- **SSIS (SQL Server Integration Services)** – ETL pipeline design and data loading  
- **Power BI** – Interactive sales reports and dashboards  
- **T-SQL** – Data extraction and transformation queries  

---

## 🧱 Data Engineering (ETL)
Implemented using SSIS and SQL Server:
- Designed a **Data Warehouse schema** optimized for analytics
- Built **ETL pipelines** to:
  - Extract data from OLTP (AdventureWorks)
  - Transform and clean data
  - Load it into the DW
- Configured **incremental loading** with `LastJobTime` and `CurrentJobTime` parameters
- Added logic for **initial load**, **delta load**, and **data validation**

📂 Folder: `Data Engineering/`

---

## 📈 Business Intelligence (Power BI)
Developed an interactive **Sales Analytics Dashboard** with:
- **KPIs:** Revenue, Cost, Profit Margin, Active Customers, etc.
- **Customer Insights:** Active customers by location, shipping time, weekdays
- **Product Insights:** Top-selling categories, most profitable models
- **Time-Series Visuals** for Revenue, Profit, and Cost
- **Filters** by Date and Location

📂 Folder: `Business Intelligence/`

---

## 📸 Screenshots
Include:
- Power BI dashboard pages  
- SSIS pipeline flow  
- DW schema overview  

---

## 🧠 Key Learnings
- Implemented ETL and DW design principles
- Built analytical reports for decision-making
- Improved SQL query optimization and performance analysis

---
