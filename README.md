📌 Project Overview
This project is an interactive Sales Dashboard built in Power BI, presenting sales performance for 2023–2024.
It includes monthly and quarterly trends, a total sales KPI, and a date range filter.
The goal was to create a clean, business‑ready report using proper data modeling and Power Query transformations.

🛠 How the Project Was Built
1. Data Preparation (Power Query)

- Removed errors, empty rows, and duplicates

- Corrected data types

- Cleaned and standardized the FactSales table

2. Date Dimension (DimDate)
Created a full calendar table (2023–2024) with:

- Date

- Year

- Quarter

- Month number & name

Used for proper sorting and time‑based filtering.

3. Data Model
Star schema:

- FactSales (sales data)

- DimDate (date dimension)
Relationship: DimDate[Date] → FactSales[OrderDate] (1:)*

4. Dashboard Design
   
- Dark modern theme

- KPI at the top

- Monthly bar chart

- Quarterly line chart

- Interactive date slicer

🎯 Purpose

- The dashboard demonstrates:

- Power Query data cleaning

- Building a Date Dimension

- Star schema modeling

- Designing clear, interactive Power BI reports

It serves as a portfolio‑ready BI project showcasing practical analytical skills.
