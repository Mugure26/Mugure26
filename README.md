# Customer Sales Analysis & Business Insights

## Project Overview

This project analyzes customer sales data to identify revenue patterns,
product performance, regional performance, monthly trends, and customer value.

The project demonstrates how Python, SQL, statistics, and data visualization
can be used to transform sales data into meaningful business insights.

---

## Business Problem

A retail business wants to understand:

- Which products generate the most revenue?
- Which products sell the highest number of units?
- Which regions perform best?
- How does revenue change over time?
- Which product categories generate the most revenue?
- Who are the most valuable customers?
- How can the business improve sales performance?

---

## Objectives

The main objectives of this project are to:

1. Clean and prepare sales data.
2. Perform exploratory data analysis.
3. Calculate important sales KPIs.
4. Analyze product and regional performance.
5. Analyze monthly revenue trends.
6. Perform customer-level analysis.
7. Segment customers based on revenue.
8. Use SQL to perform business analysis.
9. Create visualizations and dashboards.
10. Provide data-driven business recommendations.

---

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SQL
- SQLite
- Google Colab
- Data Visualization
- Exploratory Data Analysis

---

## Key Performance Indicators

| KPI | Result |
|---|---:|
| Total Revenue | KSh 2,018,500 |
| Total Units Sold | 136 |
| Total Transactions | 20 |
| Average Transaction Value | KSh 100,925 |

---

## Key Findings

### Product Performance

Laptops generated the highest revenue in the dataset, while mice
recorded the highest number of units sold.

This demonstrates that the product with the highest sales volume
does not necessarily generate the highest revenue.

### Regional Performance

Mombasa recorded the highest revenue among the regions analyzed.

The business can investigate the factors contributing to this
performance and determine whether successful strategies can be
applied to other regions.

### Category Performance

Electronics generated significantly more revenue than accessories,
while accessories recorded higher sales volume.

### Monthly Performance

Revenue varied considerably across the months in the dataset.
October recorded the highest monthly revenue.

### Customer Analysis

Customer-level analysis was performed to identify high-value,
medium-value, and low-value customers.

---

## Customer Segmentation

Customers were segmented according to their total revenue contribution.

The segments include:

- High Value
- Medium Value
- Low Value

This segmentation can help a business develop targeted marketing
and customer retention strategies.

---

## SQL Analysis

SQL was used to calculate:

- Total revenue
- Total units sold
- Revenue by product
- Revenue by region
- Revenue by category
- Monthly revenue

The SQL queries are available in:

`sql/sales_analysis.sql`

---

## Business Recommendations

### 1. Focus on High-Value Products

Maintain adequate inventory of high-revenue products such as laptops
and use targeted marketing campaigns to maximize their contribution.

### 2. Use Product Bundling

Combine high-value electronics with popular accessories such as mice
and keyboards to increase transaction value.

### 3. Investigate Regional Performance

Mombasa generated the highest revenue. The business should investigate
the factors contributing to this performance.

### 4. Monitor Sales Trends

Large monthly fluctuations should be investigated to identify possible
seasonal patterns, promotions, stock issues, or changes in customer demand.

### 5. Use Customer Segmentation

High-value customers should receive targeted retention strategies,
while lower-value customers can be encouraged to increase their
purchase frequency or transaction value.

---

## Project Structure

```text
Customer-Sales-Analysis/
│
├── data/
│   └── sales_data.csv
│
├── notebooks/
│   └── customer_sales_analysis.ipynb
│
├── sql/
│   └── sales_analysis.sql
│
├── visualizations/
│   └── final_sales_dashboard.png
│
├── customer_sales_analysis.py
├── customer_sales_portfolio.csv
├── customer_analysis.csv
├── README.md
└── requirements.txt
     
Writing /content/README.md
