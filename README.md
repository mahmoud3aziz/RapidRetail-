# 📊 RapidRetail Performance Dashboard

## 📖 Overview
This project delivers a comprehensive end-to-end analysis of the RapidRetail dataset.

The workflow started with SQL Database management, followed by deep data cleaning, building a Star Schema, and creating advanced DAX Measures to drive business decisions.

The project transforms raw data into a professional multi-page interactive dashboard.

---

## 🎯 Objectives
-Design and implement a robust SQL Database to house retail data.

-Perform advanced Data Cleaning to ensure 100% data integrity.

-Analyze Sales, Returns, Customer Demographics, and Product Profitability.

-Develop complex DAX calculations (YoY Growth, Profit Margin, Return Rates).

-Optimize operational efficiency by identifying high-return stores and low-profit items.
---

## 🧰 Tools Used
- **SQL Server / MySQL** – Database Creation & Initial Data Cleaning.
- **Power BI Desktop** – Modeling, DAX & Dashboard Design  
- **Power Query** – ETL (Extract, Transform, Load) processes

---
## 🛠 Project Workflow & Data Cleaning
This project follows a professional data pipeline:

-**SQL Layer**: Created tables and loaded raw data. Used SQL queries to remove duplicates and handle missing values at the source.

-**ETL Phase (Power Query)**: - Standardized data types (Currency, Dates).

  1)Created Conditional Columns for age binning and income segmentation.
  2)Merged Sales and Returns tables to calculate net performance accurately.

-**Data Modeling (Star Schema)**: - Connected FactSales and FactReturns with dimension tables (DimCustomer, DimProduct, DimStore, DimCalendar).

---

## 📐 DAX Measures Developed

-Total Revenue & Profit: $1.76M Revenue with a 59.67% Margin.

-YoY % Growth: Calculated a massive 212.2% year-over-year increase.

-Return Rate Analysis: Tracking returns to identify quality issues.

-Average Order Value (AOV): Measuring customer purchasing power ($6.54 average).

-Time Intelligence: Comparing monthly performance across 2017 and 2018.

---

## 📊 Dashboards Included
The report is divided into interactive pages for easy navigation:

-xecutive Financials: High-level KPIs (Revenue, Profit, Cost).
-Product Insights: Best-sellers vs. low-profit items and "Fat Content" analysis.
-Customer Segmentation: Breakdown by Income, Education, and Age.
-Sales & Returns: Deep dive into monthly trends and store performance.
-Each dashboard uses optimized visuals chosen to deliver insights quickly and clearly.

---
## Full Project
<img width="1378" height="780" alt="Image" src="https://github.com/user-attachments/assets/c4a2ba76-5c11-4a49-aad9-53faa3e39569" />

<img width="1376" height="777" alt="Image" src="https://github.com/user-attachments/assets/80e1b8b1-694c-4aed-9e26-929d23003a76" />

<img width="1383" height="782" alt="Image" src="https://github.com/user-attachments/assets/89e47045-5997-4ec0-ab9c-98bce244f3cc" />

<img width="1382" height="785" alt="Image" src="https://github.com/user-attachments/assets/d2b37882-d32b-4eb8-9887-466f3520eea4" />


<img width="793" height="765" alt="Image" src="https://github.com/user-attachments/assets/41c0b5a9-b670-405c-b6e1-1607bd9e0a88" />


---
