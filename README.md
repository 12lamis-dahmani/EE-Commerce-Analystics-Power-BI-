# E-Commerce Analytics Dashboard – Power BI Project

## Project Overview

This project is a complete Power BI business intelligence dashboard based on an online retail dataset. The goal of this project is to analyze e-commerce sales performance, customer behavior, product performance, and time-based trends.

The dashboard was created as a portfolio project to demonstrate skills in:

- Data cleaning with Power Query
- Data modeling with a star schema
- DAX measures and calculated columns
- Interactive dashboard design
- Business KPI analysis
- Data visualization and storytelling

---

##  Project Goal

The main objective of this Power BI project is to build an interactive dashboard that helps answer important business questions such as:

- How much revenue was generated?
- Which countries generate the most sales?
- Which products are the best and worst performers?
- How does customer activity change over time?
- How many customers buy repeatedly?
- Which weekdays and quarters have the strongest sales?
- Which product categories contribute most to revenue?

---

## Dataset

The project uses the Online Retail dataset, which contains transactional data from an e-commerce business.

### Dataset Information

The dataset includes information such as:

- Invoice number
- Stock code
- Product description
- Quantity
- Invoice date
- Unit price
- Customer ID
- Country

### Source

Dataset: Online Retail Dataset  
Source: Kaggle / UCI Machine Learning Repository

> Note: The raw dataset is not included in this repository if licensing restrictions apply.  
> The Power BI file contains the transformed data model and dashboard.

---

##  Tools Used

- Power BI Desktop
- Power Query
- DAX
- Microsoft Excel
- GitHub

---

##  Data Cleaning

The raw dataset was cleaned and transformed in Power Query before building the dashboard.

Main cleaning steps:

- Removed invalid transactions
- Removed negative quantities and returns
- Removed rows with missing CustomerID
- Removed rows with missing InvoiceNo
- Filtered out rows with UnitPrice less than or equal to 0
- Corrected data types
- Created revenue column
- Created date-related columns
- Removed unnecessary columns
- Prepared the data for modeling
