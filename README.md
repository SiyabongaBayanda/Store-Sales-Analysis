#  Store Sales Analysis
##  Project Overview

This project analyzes Vrinda store sales data to identify sales trends,
customer purchasing behaviour, sales performance, and business
opportunities. 

### Objective
Analyze sales and customer purchasing patterns to identify revenue drivers, high-performing markets and channels, and opportunities for business growth.

## Data Source

**Source:** Kaggle  
**Dataset:** Vrinda Store Sales 
**Link:** [Download here](https://www.kaggle.com/datasets/amitkumar209/vrinda-store-sales-data)

## Business Questions

1. What are the total sales and orders?
2. Which category generates the most sales?
3. Which gender contributes the most sales?
4. Which age group generates the most sales?
5. Which month has the highest sales?
6. Which channels generate the most orders?
7. Show different orders status?
8. Which states generate the most sales?
   
## Tools Used

- SQL Server – Data storage, cleaning, and removing duplicates analysis
- SQL – Data transformation & formatting dates and business analysis
- Power BI – Data visualization and interactive dashboard
- Excel/CSV – Source dataset

## Project Workflow

Raw Dataset
    →
SQL Server
    →
Exploratory Data Analysis (EDA)
    →
Data Cleaning & Transformation
    →
SQL Data Analysis
    →
Power BI Dashboard
    →
Business Insights

[View SQL Queries](SQL_Store_Sales_Analysis.sql)

## Dashboard

![HR Analytics Dashboard](Sales_Report_Dashboard.png)

The Power BI dashboard contains:

### KPI's

- Sum of Amount/Revenue: ₹ 21.18M
- Total Orders: 31.05K
- Total Quantity Sold: 31.19K
- Average Order Value: ₹ 682

### Visualizations

- Monthly Sales Trend (Column Chart)
- Sales by Category (Bar Chart)
- Sales by Gender (Pie Chart)
- Sales by State (Bar Chart)
- Sales by Sales Channel (Pie Chart)
- Orders by Age & Gender (Column Chart)
- Order Status (Donut Chart)

## Key Insights

- Women represent the largest customer segment by sales contribution 64%.
- Customers aged 30–49 generated the largest share of sales, highlighting the Adult age group as a key target market.
- Set, Kurta, and Western Dress were the top-performing categories, collectively contributing 88% of total sales, making them the primary drivers of product revenue.
- Q1 recorded the highest quarterly sales, indicating strong sales performance during the first quarter.
- Maharashtra, Karnataka, and Uttar Pradesh were the top three sales-generating states, highlighting these regions as key markets for the business.
- Amazon, Myntra, and Flipkart were the strongest sales channels, collectively accounting for 80% of total sales, demonstrating the importance of these platforms to overall business performance.

## Recommendations

- Target women aged 30–49 with personalized marketing campaigns, product recommendations, and offers tailored to their purchasing preferences.
- Strengthen the Amazon, Myntra, and Flipkart sales channels by using targeted advertising, exclusive offers, and promotional coupons to increase customer engagement and sales.
- Increase inventory and staffing ahead of peak sales periods to ensure sufficient stock and operational capacity to meet higher customer demand and maximize sales opportunities.
- Investigate low-performing states to identify barriers to sales growth and develop targeted strategies such as regional promotions, localized marketing, and improved product availability.
