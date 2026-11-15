# Amazon India Sales & Business Performance Dashboard

An end-to-end data analytics project focused on analyzing Amazon India's sales performance, profitability, customer orders, product categories, payment methods, fulfilment methods, and geographic performance using Python and Power BI.

## Project Overview

This project analyzes **10,000 Amazon sales records** to identify business trends, evaluate sales and profitability, and provide actionable insights through a four-page Power BI dashboard.

The dashboard is designed to help business stakeholders monitor key performance indicators and make data-driven decisions.

## Business Objectives

- Analyze overall sales and profit performance.
- Identify high-performing product categories and products.
- Monitor order status, returns, and cancellations.
- Evaluate payment and fulfilment performance.
- Compare sales and profitability across different states.
- Identify business trends and opportunities for improvement.

## Dataset Information

| Description | Details |
|---|---:|
| Total Records | 10,000 |
| Total Columns | 13 |
| Date Range | Jan 2024 – Aug 2026 |
| Product Categories | 5 |
| Unique Products | 25 |
| Payment Methods | 5 |
| Fulfilment Methods | 3 |
| Order Status Categories | 4 |
| States | 10 |

**Data quality:** No missing values, duplicate rows, or duplicate Order IDs were identified during initial data exploration.

## Tools & Technologies

- **Python:** Data exploration and analysis
- **Pandas & NumPy:** Data manipulation and analysis
- **Jupyter Notebook:** Exploratory Data Analysis
- **Power BI:** Interactive dashboard development
- **Power Query:** Data transformation and preparation
- **DAX:** Measures and KPI calculations
- **Microsoft Excel:** Dataset source

## Key Performance Indicators

| KPI | Result |
|---|---:|
| Total Sales | ₹15.58 Crore |
| Total Profit | ₹3.32 Crore |
| Total Orders | 10,000 |
| Total Units Sold | 25,000 |
| Average Order Value | ₹15.58K |
| Profit Margin | 21.29% |
| Returned Orders | 485 |
| Cancelled Orders | 500 |
| Return Rate | 4.85% |
| Cancellation Rate | 5.00% |

## Power BI Dashboard

The dashboard consists of four analytical pages:

### 1. Overall Sales & Profit Performance
- Total Sales, Total Profit, Total Orders and Units Sold.
- Average Order Value and Profit Margin.
- Monthly Sales and Profit Trends.

### 2. Category & Product Performance
- Category-wise Sales.
- Category-wise Profit.
- Units Sold by Category.
- Top 10 Products by Sales.

### 3. Order Status & Revenue Loss
- Delivered, Shipped, Returned and Cancelled Orders.
- Return Rate and Cancellation Rate.
- Category-wise Returns and Cancellations.

### 4. Payment, Fulfilment & Geographic Performance
- Sales and Profit by Payment Method.
- Sales and Profit by Fulfilment Method.
- State-wise Sales.
- State-wise Profit and Orders.

## Key Business Insights

- The business generated approximately **₹15.58 Crore in sales** and **₹3.32 Crore in profit**.
- The overall profit margin was **21.29%**.
- A total of **10,000 orders** were recorded across the analysis period.
- **8,147 orders were delivered**, representing the majority of recorded orders.
- Returned and cancelled orders together accounted for **985 orders**, or 9.85% of total orders.
- UPI was the most frequently used payment method, accounting for **4,972 orders**.
- Amazon Fulfilment (FBA) handled **7,054 orders**, making it the most frequently used fulfilment method.
- Maharashtra recorded the highest order volume, with **1,840 orders**.

*Note: Returned and cancelled order counts are operational indicators. They should not be interpreted as confirmed financial losses without refund and revenue-recognition data.*

## Project Structure

```text
amazon-india-sales-dashboard/
│
├── dataset/
│   └── Amazon Sales Data India.xlsx
│
├── notebooks/
│   └── Amazon_India_Data_Exploration.ipynb
│
├── dashboard/
│   └── Amazon_India_Dashboard.pbix
│
├── documentation/
│   └── business_insights.md
│
├── screenshots/
│   ├── page1.png
│   ├── page2.png
│   ├── page3.png
│   └── page4.png
│
└── README.md
```

## Key Learnings

- Performed exploratory data analysis using Python.
- Evaluated data quality and validated important dataset fields.
- Transformed and prepared data using Power Query.
- Created calculated measures and business KPIs using DAX.
- Designed a multi-page Power BI dashboard.
- Converted business requirements into meaningful visualizations and insights.

## Disclaimer

This project is intended for educational and portfolio demonstration purposes. The analysis is based on the available dataset and does not represent official Amazon business results.
