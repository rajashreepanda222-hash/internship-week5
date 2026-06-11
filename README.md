# Customer & Sales Data Analysis Dashboard

## Project Overview

This project performs end-to-end data analysis on customer and sales datasets using Python, Pandas, and Matplotlib.

The analysis follows a 7-day workflow:

* Day 1: Load Datasets
* Day 2: Data Cleaning & Preparation
* Day 3: Customer Analysis
* Day 4: Sales Analysis
* Day 5: Advanced Analysis & Pivot Tables
* Day 6: Dashboard Creation
* Day 7: Report & Business Insights

---

## Datasets Used

### customer_data.csv

| Column           | Description                          |
| ---------------- | ------------------------------------ |
| CustomerID       | Unique customer identifier           |
| Tenure           | Number of months customer has stayed |
| MonthlyCharges   | Monthly subscription charges         |
| TotalCharges     | Total amount spent                   |
| Contract         | Contract type                        |
| PaymentMethod    | Payment method used                  |
| PaperlessBilling | Billing preference                   |
| SeniorCitizen    | Senior citizen status                |
| Churn            | Customer churn status                |

### sales_data.csv

| Column      | Description         |
| ----------- | ------------------- |
| Date        | Transaction date    |
| Product     | Product name        |
| Quantity    | Quantity sold       |
| Price       | Product price       |
| Customer_ID | Customer identifier |
| Region      | Sales region        |
| Total_Sales | Total sales amount  |

---

## Technologies Used

* Python
* Pandas
* Matplotlib
* CSV Files

---

## Features Implemented

### Day 2: Data Cleaning

* Removed extra spaces from column names
* Handled missing numerical values using median
* Handled missing categorical values using "Unknown"
* Converted date columns to datetime format

### Day 3: Customer Analysis

* Customer Lifetime Value (CLV)
* Churn Rate Calculation
* Contract Distribution Analysis
* Payment Method Analysis

### Day 4: Sales Analysis

* Monthly Sales Trend
* Best Selling Products
* Regional Sales Analysis

### Day 5: Advanced Analysis

* Pivot Table Creation
* Product Revenue Analysis
* Exported analysis results to CSV

### Day 6: Dashboard Creation

Generated visualizations:

1. Monthly Sales Trend
2. Top Products by Revenue
3. Regional Sales Distribution
4. Contract Distribution
5. Churn Distribution

All charts are automatically saved inside:

visualizations/

---

## Output Files

### Analysis Files

* regional_sales.csv
* top_products.csv

### Visualization Files

* monthly_sales_trend.png
* top_products_revenue.png
* regional_sales_distribution.png
* contract_distribution.png
* churn_distribution.png

---

## Project Structure

```text
project/
│
├── customer_data.csv
├── sales_data.csv
├── analysis.py
├── README.md
│
├── regional_sales.csv
├── top_products.csv
│
└── visualizations/
    ├── monthly_sales_trend.png
    ├── top_products_revenue.png
    ├── regional_sales_distribution.png
    ├── contract_distribution.png
    └── churn_distribution.png
```

---

## How to Run

1. Install required libraries

```bash
pip install pandas matplotlib
```

2. Place both datasets in the project folder

* customer_data.csv
* sales_data.csv

3. Run the analysis script

```bash
python analysis.py
```

4. View generated results and visualizations.

---

## Business Insights

* Identify customer churn patterns.
* Analyze customer contract preferences.
* Determine top-performing products.
* Monitor monthly sales trends.
* Compare sales performance across regions.

---
