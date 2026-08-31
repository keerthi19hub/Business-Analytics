Superstore Sales Performance Analysis — Power BI

A Power BI dashboard that analyzes sales and profit performance for a retail superstore across products, categories, and regions, built on the popular Sample Superstore dataset.

About the Project

A retail company wants to understand how its sales and profit are doing across different products, categories, and regions. This project takes the raw Sample Superstore data, cleans it up in Power BI, and turns it into an interactive dashboard that makes those patterns easy to see at a glance.

Dataset
Source: Sample Superstore dataset
Size: 9,994 rows
Fields include: Order Date, Ship Date, Customer ID, Segment, Region, City, State, Product ID, Category, Sub-Category, Sales, Quantity, Discount, and Profit
Each row represents a single order line, so one order can appear more than once if it included multiple products.

What Was Done
Data Import — Loaded the Sample_Superstore data into Power BI as a table.
Data Cleaning — Used Power Query to promote headers, fix column data types (Sales, Quantity, and Discount as numbers), correct the date locale for Order Date and Ship Date, and confirm there were no empty or error values in key columns.
Data Modeling — Added calculated columns (Month, Month Number, Quarter, Year) and built core DAX measures:
Total Sales — SUM of all sales values
Total Profit — SUM of all profit values
Total Quantity — total units sold
Total Orders — distinct count of orders placed
Dashboard Design — Built a two-page interactive report (see below).

Tools Used
Power BI Desktop
Power Query Editor
DAX (Data Analysis Expressions)

Dashboard Pages

Page 1 — Sales Overview
KPI cards: Total Sales (2.30M), Total Profit (286.40K), Quantity Sold (38K), Total Orders (5K)
Total Sales by Category
Total Sales by Region
Total Sales by Sub-Category
Top 10 Products by Sales


Page 2 — Trends and Regions
Sales Trend Over Time (2014–2017)
Sales by Region and Category table
Total Sales by State (map)
Slicers for Region, Category, Segment, and Order Date

Key Insights

Technology and Furniture bring in the most sales, followed closely by Office Supplies.
West and East regions consistently sell more than Central and South.
Phones, Chairs, and Storage are the top sub-categories; Labels and Fasteners barely contribute.
Sales show clear spikes at certain points in the timeline.
California (Los Angeles in particular) is one of the stronger markets.
The Consumer segment places orders more often than Corporate or Home Office.
Standard Class is the most common shipping method used across orders.

How to View
Clone this repository.
Open powerbi/Superstore_Sales_Dashboard.pbix in Power BI Desktop.
Use the slicers on Page 2 to filter by Region, Category, Segment, or Order Date.

Learning Outcomes
Importing and cleaning data properly using Power Query before building anything on top of it.
Writing DAX formulas to create calculated columns and measures.
Understanding how KPI cards, bar charts, line charts, and maps each serve a different purpose on a dashboard.
Adding slicers to make a report interactive rather than a static set of charts.
Designing dashboard pages around what an actual user would want to know.
