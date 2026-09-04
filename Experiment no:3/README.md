Retail Business Analytics Dashboard
📌 Project Overview

This project is a Retail Business Analytics Dashboard created using MySQL and Power BI. The main purpose of the project is to analyse retail sales data and understand customer behaviour, product performance, store performance, payment methods, and customer demographics.

The data was first stored and prepared in MySQL and then connected to Power BI for cleaning, modelling, analysis, and dashboard creation.

🎯 Objectives
Connect MySQL database with Power BI.
Clean and transform the retail data using Power Query.
Create relationships between different tables.
Create DAX measures for important calculations.
Build an interactive three-page Power BI dashboard.
Analyse sales, customers, stores, payments, and demographics.
🗄️ Database

A MySQL database named RetailDB was created with the required retail tables.

Main tables used:

Sales – Contains transaction details such as SaleID, ProductID, StoreID, Quantity, SaleDate, and TotalAmount.
Products – Contains product-related information.
Stores – Contains store-related information.
Customer Details – Contains customer information.
Calendar – Used for date and time-based analysis.
🧹 Data Preparation

The data was prepared using Power Query Editor.

Some of the main operations performed were:

Removed duplicate records.
Checked missing values.
Renamed columns where required.
Changed data types.
Created Age Groups.
Created Month, Year, and Month-Year fields.
🔗 Data Modeling

A star-schema style model was created in Power BI.

The main relationships were:

Sales → Products using ProductID
Sales → Stores using StoreID
Sales → Customer Details using SaleID
Sales → Calendar using Date
📊 DAX Measures

The following measures were created:

Total Sales
Total Orders
Total Quantity
Total Customers
Average Order Value
Average Customer Age
Customer Count

These measures were used in KPI cards, charts, and other dashboard visuals.

📈 Dashboard Pages
Page 1 – Retail Sales & Customer Overview

This page provides an overall view of the business.

It includes:

Total Sales – 317.65K
Total Orders – 15
Total Quantity – 92
Total Customers – 15
Product-wise sales
City-wise sales
Sales by date
Sales by month and year

Slicers were added for Month Year, Category, City, and Month Name.

Page 2 – Customer & Store Segmentation

This page focuses on customer and store analysis.

It includes:

Sales by Gender
Orders by Store Type
Sales by Customer Segment
Comparison of Regular, New, and Premium customers
Page 3 – Payment & Demographic Analysis

This page focuses on payment methods and customer demographics.

It includes:

Sales by Payment Method
UPI, Credit Card, Debit Card, and Cash analysis
Sales by Age Group
Gender, Customer Segment, and Payment Method slicers
🛠️ Tools & Technologies
MySQL Workbench – Database creation and SQL operations
Power BI Desktop – Data analysis and dashboard creation
Power Query – Data cleaning and transformation
DAX – Measures and calculations
✅ Conclusion

This project helped in understanding how MySQL and Power BI can be used together for business analytics. The final dashboard provides an interactive way to analyse retail performance and understand customer behaviour through different charts, KPIs, and filters.
