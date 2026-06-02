# Retail Sales Data Engineering Project

## Overview

This project presents an end-to-end Retail Sales Data Engineering solution that transforms raw retail transaction data into actionable business insights. The pipeline performs data ingestion, profiling, cleaning, transformation, feature engineering, KPI generation, and business intelligence reporting using Power BI.

The objective is to create a reliable analytical dataset that supports data-driven decision-making through interactive dashboards and key business metrics.

---

## Problem Statement

Retail transaction data often contains missing values, duplicate records, inconsistent formats, and data quality issues that impact business reporting.

This project aims to design and implement a complete ETL pipeline to:

* Integrate multiple retail data sources
* Perform data quality assessment and cleansing
* Generate business-ready analytical datasets
* Develop interactive dashboards for business insights

---

## Technology Stack

* Python
* Pandas
* NumPy
* Jupyter Notebook
* Power BI
* Git & GitHub

---

## Project Architecture

```text
Data Source (Excel Workbook)
            ↓
      Data Ingestion
            ↓
       Data Profiling
            ↓
       Data Cleaning
            ↓
    Data Transformation
            ↓
       Curated Data 
            ↓
      KPI Generation
            ↓
      Power BI Dashboard
```

---

## Dataset

Source file contains:

* retail_data1
* retail_data2
* product_details

Key attributes include:

* Transaction Information
* Customer Details
* Product Details
* Payment Information
* Sales Locations
* Discounts
* Revenue Metrics

---

## Data Quality Challenges Identified

* Missing price values
* Duplicate transaction IDs
* Negative and zero quantities
* Category inconsistencies
* Product naming inconsistencies
* Date format inconsistencies

---

## Data Cleaning & Transformation

### Data Cleaning

* Missing value imputation
* Duplicate removal
* Invalid quantity removal
* Category standardization
* Product name standardization
* Date formatting

### Feature Engineering

* Revenue Calculation
* Month Extraction
* KPI Generation
* Business Metric Creation

Revenue Formula:

```python
Revenue = Price × Quantity × (1 - Discount)
```

---

## Key Performance Indicators

| KPI                 | Value          |
| ------------------- | -------------- |
| Total Revenue       | ₹1.164 Billion |
| Total Orders        | 7,914          |
| Total Customers     | 1,960          |
| Average Order Value | ₹147.08K       |
| Top Product         | Laptop         |

---

## Key Business Insights

* Electronics contributes approximately 58% of total revenue.
* Laptop is the highest revenue-generating product.
* Chennai is the leading revenue-generating city.
* Card payments contribute the highest revenue share.
* Online and offline channels show balanced performance.
* Clothing contributes the lowest share of revenue.

---

## Power BI Dashboard Features

* Executive KPI Dashboard
* Revenue Trend Analysis
* Category Performance Analysis
* City-wise Revenue Analysis
* Product Performance Analysis
* Payment Method Analysis
* Customer Analysis
* Interactive Filters & Slicers
* Drill-through Reporting
  <img width="1157" height="641" alt="image" src="https://github.com/user-attachments/assets/f7f73f21-e798-4116-ae51-46b74de420ee" />
  <img width="1088" height="586" alt="image" src="https://github.com/user-attachments/assets/c3283819-54f7-4350-8aa2-5ae1f9242533" />



---

## Project Structure

```text
Retail-Sales/

├── Data/
│   ├── Original_data.xlsx
│   └── cleaned_data.csv
│
├── Code/
│   ├── Retail_Sales_ETL.ipynb
│   ├── Retail_KPI_Analysis.ipynb
│   ├── config.py
│   └── requirements.txt
│
├── PowerBI/
│   └── RetailDashboard.pbix
│
├── Documentation/
│   ├── Project_Report.docx
│   ├── Architecture.png
│   └── DataFlow.png
│
└── README.md
```

---

## Future Scope

* Azure Blob Storage Integration
* Azure Data Factory Pipeline
* Azure SQL Database
* Real-Time Data Processing
* Automated ETL Orchestration
* Cloud-Based Analytics Platform

---


