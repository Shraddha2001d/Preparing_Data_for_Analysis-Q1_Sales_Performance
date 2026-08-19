# Preparing Data for Analysis | Q1 Sales Performance
## 📊 Project Overview

This project demonstrates how I prepared and analyzed transactional sales data in Microsoft Excel to create a management-ready Q1 sales summary.

The analysis focuses on comparing Q1 sales performance between 2022 and 2023 and breaking down the results by month.
## 🟦 Situation

The business had transactional sales data containing product information, order dates, prices, quantities, and other fields.

Management needed a clear summary of Quarter One sales performance and a comparison with the previous year to better understand business performance.

The raw data also required preparation before meaningful analysis could be performed.
## 🟨 Task

My objective was to:

- Prepare the raw dataset for analysis
- Improve the consistency and usability of the data
- Calculate order-level sales values
- Apply a business rule for tax calculation
- Calculate total Q1 sales for 2022 and 2023
- Analyze monthly sales performance
- Calculate the percentage change between the two years
- Present the results in an executive-friendly format
## 🟩 Action

I used Microsoft Excel to prepare and analyze the dataset.

#### Data Preparation

- Standardized product names using PROPER()
- Sorted transactions by Order Date
- Created Month and Year fields using MONTH() and YEAR()
- Reorganized the worksheet for easier analysis
- Hide unnecessary fields and froze panes for better usability

#### Data Transformation

Calculated order value using:

[Retail Price × Order Quantity]

Applied an IF() function to calculate 5% tax when the order value exceeded 2,000.

#### Sales Analysis

- Used SUMIFS() to calculate total Q1 sales for 2022 and 2023
- Calculated monthly sales for January, February, and March
- Calculated percentage change using:

[(2023 Sales - 2022 Sales) / 2022 Sales]

#### Reporting

- Created a structured Q1 sales summary
- Compared yearly and monthly performance
- Formatted the worksheet for management-level presentation
## 🟥 Result

The final output transformed the raw transactional dataset into a structured management-ready sales summary.

The analysis provides visibility into:

- Overall Q1 sales performance
- Year-over-year sales change
- Monthly sales performance
- Order-level sales values
- Tax applicability based on business rules

This made the data easier to interpret and provided a foundation for performance review and business decision-making.

Key takeaway: The goal of data analysis is not just to calculate numbers, but to transform raw data into information that can support better decisions.
## 🛠️ Tools & Skills

#### Tool: Microsoft Excel

Skills Demonstrated:

- Data Preparation
- Data Cleaning
- Data Transformation
- Sales Analysis
- Date Analysis
- Business Logic
- Year-over-Year Analysis
- Monthly Performance Analysis
- Executive Reporting

#### Excel Functions:

PROPER() | MONTH() | YEAR() | IF() | SUMIFS()

## 📌 Project Workflow
Raw Transaction Data

↓

Data Preparation

↓

Data Transformation

↓

Business Calculations

↓

Q1 Sales Analysis

↓

Year-over-Year Comparison

↓

Executive Summary
## 📷 Project Preview

The final Excel worksheet provides an executive-level view of Q1 sales performance and monthly comparisons.

<img width="1912" height="979" alt="Screenshot 2026-08-18 001613" src="https://github.com/user-attachments/assets/322ef3db-7fb1-4493-bbf7-e50b7903015b" />

## 💡 Analyst Perspective
- This project reinforced an important principle of data analytics:
- Good analysis starts with well-prepared data.
- Before generating insights, an analyst needs to ensure that the data is structured, consistent, and suitable for the business question being investigated.
