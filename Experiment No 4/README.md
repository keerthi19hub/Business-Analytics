# Cafe Sales Data Cleaning Using Power Query

## Overview

This project focuses on cleaning and transforming a raw **Cafe Sales dataset** using **Microsoft Power Query**. The dataset was obtained from Kaggle and contained various data quality issues that needed to be resolved before analysis.

## Dataset

The dataset contains cafe sales information such as:

- Transaction details
- Items sold
- Quantity
- Price Per Unit
- Total Spent
- Payment Method
- Location
- Transaction Date

The raw dataset contained issues such as missing values, `UNKNOWN` placeholders, incorrect data types, calculation errors, duplicate records, extra spaces, and invalid dates and quantities.

## Tools Used

- **Microsoft Excel**
- **Power Query Editor**
- **Kaggle Dataset**

## Data Cleaning Process

A total of **23 Applied Steps** were used to clean the dataset:

1. Initial Type
2. Headers
3. Set Data Types
4. Replace Error
5. Replace UNKNOWN
6. Format Types
7. Fix Total Spent
8. Fix Quantity
9. Fix Price
10. Remove Originals
11. Rename Columns
12. Final Data Types
13. Filter Dates
14. Fill Item
15. Fill Payment
16. Fill Location
17. Remove Invalid Rows
18. Remove Duplicates
19. Trim Text
20. Clean Text
21. Remove Blanks
22. Filter Quantity
23. Final Filter

## Key Cleaning Activities

- Corrected incorrect data types
- Replaced errors and `UNKNOWN` values
- Fixed Quantity, Price Per Unit, and Total Spent values
- Filled missing values where possible
- Removed invalid rows
- Removed duplicate records
- Trimmed and cleaned text values
- Filtered invalid dates and quantities
- Created a final analysis-ready dataset

## Outcome

The raw Cafe Sales dataset was successfully transformed into a **clean, consistent, and analysis-ready dataset**. The use of Power Query also makes the cleaning process **repeatable and easy to maintain**, as the same Applied Steps can be reapplied when the source data is refreshed.

## Key Learnings

This project provided practical experience in:

- Understanding real-world data quality problems
- Handling missing and inconsistent data
- Correcting data types and calculation errors
- Using Power Query for structured data cleaning
- Creating transparent and repeatable data transformation workflows
- Preparing data for further analysis and visualization

## Future Analysis

The cleaned dataset can be used for further analysis such as:

- Sales trend analysis
- Payment method distribution
- Item-wise sales performance
- Location-based performance comparison
- Quantity and revenue analysis
