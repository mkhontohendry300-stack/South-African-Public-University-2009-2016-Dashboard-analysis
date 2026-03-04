South African Public University Data Analysis (2009–2016)

Comprehensive analysis of South African public university data using Excel, SQL, and Power BI.

This project is a quantitative audit of enrolment and graduation trends across South African public universities over seven years. It covers the full data pipeline — from raw source data through to a structured data mart, analytics-ready CSV files, and an interactive Power BI dashboard.

The goal is to surface meaningful patterns in how student enrolments and graduate outputs have evolved across institutions, qualification levels, fields of study, and demographic groups, providing a data-driven foundation for institutional and policy-level insights

Project Overview

This project analyses public university data from 2009 to 2016, focusing on:

> Student Enrollments
> Graduation Rates
> Faculty Demographics
> Financial Performance
> Research Outputs

The goal was to transform raw institutional data into actionable insights using a structured analytics workflow:
Excel → SQL → Power BI → Business Insights

Objectives

By completing this project, I demonstrated the ability to:
Clean and prepare large datasets using Excel
Design and query relational databases using SQL
Build interactive dashboards in Power BI
Extract strategic insights from multi-year institutional data
Present findings in a structured analytical report

Tools & Technologies

Microsoft Excel – Data cleaning & preprocessing
SQL (PostgreSQL) – Data storage & advanced querying
Power BI Desktop – Data modelling & interactive dashboards
DAX – Calculated measures & KPIs

📂 Project Structure
📁 South-Africa-University-Data-Analysis
│
├──  Cleaned_Data/
│   └── Cleaned_University_Data.xlsx
│
├──  SQL/
│   ├── Database_Schema.sql
│   ├── Enrollment_Queries.sql
│   ├── Graduation_Queries.sql
│   ├── Faculty_Queries.sql
│   ├── Financial_Queries.sql
│   └── Research_Queries.sql
│
├──  PowerBI/
│   └── University_Analysis_Dashboard.pbix
│
├──  Summary_Report.pdf
│
└── README.md

 Project Breakdown
1️⃣ Data Cleaning & Preparation (Excel)

Standardised column names and data formats
Converted dates to a consistent format (YYYY-MM-DD)
Handled missing values
Removed duplicate records
Validated numerical consistency
Applied conditional formatting to detect anomalies

Deliverable: Cleaned and structured dataset ready for SQL ingestion.

2️⃣ SQL Database & Analysis
Database Setup

Created relational schema
Defined appropriate data types (INTEGER, VARCHAR, DATE)
Imported cleaned dataset

Key Analytical Questions Solved
> Enrollment Trends

Identified the university with the highest enrollment in 2016
Calculated average annual enrollment growth rate (2009–2016)

> Graduation Performance

Compared graduation success rates across institutions
Ranked top-performing universities

> Faculty Analysis

Calculated student-to-staff ratios
Analysed gender and race distribution

> Research Performance

Identified top universities by research output
Compared research funding vs publication output

> Financial Health

Analysed income sources
Calculated the % expenditure allocated to staff salaries
Identified budget surplus/deficit trends

Deliverable: Optimised SQL queries + exported results (CSV/views)

3️⃣ Power BI Dashboards

Four interactive dashboards were created:

 1. Enrollment & Graduation Dashboard
 2. Faculty Demographics Dashboard
 3. Financial Overview Dashboard
 4. Research Performance Dashboard
