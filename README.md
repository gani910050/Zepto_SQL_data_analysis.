# Zepto Sales & Inventory Dashboard

A data analysis and visualization project using **SQL** and **Power BI**, built on Zepto's product dataset.

## Project Overview
This project explores Zepto's product inventory and sales data to uncover insights on pricing, discounts, stock availability, and category-wise performance.

## Tools Used
- **SQL** – Data cleaning, exploration, and analysis
- **Power BI** – Interactive dashboard and visualizations

## Dataset
- `zepto_v3.csv` – Raw product data (category, MRP, discount, stock status, weight, etc.)
- `sql_project.sql` – SQL scripts for data cleaning and analysis queries

## Data Cleaning (SQL)
- Removed rows with zero MRP / selling price
- Converted prices from paise to rupees
- Checked for null values and duplicate product names

## Key Analysis Questions
1. Top 10 best-value products by discount percentage
2. High MRP products that are out of stock
3. Estimated revenue per category
4. Products with MRP > ₹500 and discount < 10%
5. Top 5 categories by average discount
6. Price per gram for products above 100g
7. Weight categorization (Low / Medium / Bulk)
8. Total inventory weight per category

## Dashboard Preview

### Page 1 — Overview
![Dashboard Page 1](images/dashboard_page1.png)

### Page 2 — Revenue & Product Details
![Dashboard Page 2](images/dashboard_page2.png)

## Key Insights
- **Cooking Essentials** and **Munchies** lead in both total revenue and inventory weight.
- About **89%** of products are currently in stock, **11%** out of stock.
- **Chocolates & Candies**, **Ice Cream & Desserts**, and **Packaged Food** offer the highest average discounts (~12-13%).
- Total of **2,554** unique products analyzed after data cleaning.

## Files in this Repo
- `sql_project.sql` — SQL queries for cleaning and analysis
- `zepto_v3.csv` — Dataset
- `Zepto_Dashboard.pbix` — Power BI dashboard file
- `images/` — Dashboard screenshots
