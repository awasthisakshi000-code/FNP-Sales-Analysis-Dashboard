FNP (Ferns & Petals) — Sales Analysis Dashboard (2023)

Author: Sakshi Awasthi
Files included: dataset, dashboard workbook, screenshots, queries

Problem statement

Ferns & Petals (FNP) is an online gifting company. The dataset contains details of orders, products, customers, and dates for 2023. The goal of this project is to analyze sales and customer behavior and provide actionable business insights to help improve sales strategy and customer satisfaction.

Key business questions answered:
Total Revenue: Overall revenue generated in 2023.
Average Order & Delivery Time: Average time taken from order to delivery.
Monthly Sales Performance: Sales fluctuation across months.
Top Products by Revenue: Identify top revenue-generating products.
Customer Spending Analysis: How much customers spend on average.
Sales Performance of Top 5 Products: Track top 5 products.
Top 10 Cities by Number of Orders: Cities with highest order volumes.
Order Quantity vs. Delivery Time: Whether larger orders take longer to deliver.

Tools used
Excel (Tables, PivotTables, Pivot Charts, slicers)
Power Query and Data Modelling (for cleaning & transforming data)

Data cleaning steps
Standardized date columns and converted to Date type.
Removed duplicates and invalid rows (missing order IDs).
Created helper columns: OrderMonth, DeliveryTimeDays (delivery_date - order_date), Occasion.
Aggregated revenue by product, city, and month.

Key visualizations
Monthly revenue trend (line chart).
Top 10 products by revenue (bar chart).
Revenue by occasion (stacked bar / donut).
Top 10 cities by number of orders (horizontal bar).
Scatter: order quantity vs. delivery time (trend line).
Revenue Comparison Between Occasions: Compare revenue by occasion (Diwali, Holi, Valentine’s, etc.).
Product Popularity by Occasion: Which products are popular per occasion.
