# Retail Data Analysis Project
# Project Overview
This project focuses on analyzing a retail dataset extracted from Kaggle to derive meaningful insights into sales performance, product profitability, and regional sales trends. The analysis involves data extraction, transformation, and loading (ETL) processes, followed by SQL-based analytical queries to explore key business metrics.

# Dataset Details
The dataset consists of transactional data, including order details, pricing, discounts, and profitability metrics. Key columns in the dataset:

Order Information: order_id, order_date, ship_mode, segment
Location Details: country, city, state, postal_code, region
Product Information: category, sub_category, product_id
Pricing & Sales Data: cost_price, list_price, quantity, discount_percent, discount, sale_price, profit

# Data Processing & Analysis
# 1. Data Preparation & Loading
Extracted the dataset from Kaggle and performed data cleaning.
Derived new columns:
Discount = (list_price * discount_percent / 100)
Sale Price = (list_price - discount)
Profit = (sale_price - cost_price)
Loaded the cleaned dataset into SQL Server by creating appropriate tables and importing records from Excel.

# 2. Business Insights & SQL Analysis
Performed various SQL-based analyses to derive key insights:

Top 10 highest revenue-generating products
Top 5 best-selling products in each region
Month-over-month sales growth comparison for 2022 and 2023
Identified the highest sales month for each product category
Determined the subcategory with the highest profit growth in 2023 compared to 2022
# Technologies Used
SQL Server – Data storage and analysis
Excel – Data extraction and initial processing
Python (Optional) – For data cleaning and visualization (if applicable)
Kaggle – Data source
# Results & Insights
The analysis provides a comprehensive view of retail sales trends, helping businesses identify high-performing products, seasonal trends, and areas for improvement in pricing and discount strategies.
