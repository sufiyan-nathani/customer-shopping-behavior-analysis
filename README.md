# Customer Shopping Behavior Analysis

## Project Overview

This is an end-to-end data analytics project completed using Python, MySQL, and Power BI. The project analyzes customer shopping behavior using transactional data consisting of 3,900 purchase records and 18 columns.

The main objective of this project was to transform raw customer shopping data into meaningful business insights through data cleaning, exploratory data analysis, SQL-based business analysis, and interactive dashboard creation.

## Tools Used

- Python
- Pandas
- MySQL
- SQL
- Power BI
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Data Visualization
- Business Insights

## Dataset Overview

The dataset contains 3,900 customer purchase records across multiple product categories. It includes customer demographics, purchase details, product preferences, discounts, subscription status, shipping methods, purchase frequency, and review ratings.

The dataset was used to analyze customer spending patterns, purchasing behavior, product performance, customer segments, and subscription trends.

## Data Preparation

The following data preparation steps were performed using Python and Pandas:

- Loaded the CSV dataset into Python using Pandas
- Explored the dataset structure using `df.info()` and `df.describe()`
- Identified and handled 37 missing values in the `review_rating` column using the median rating of the corresponding product category
- Standardized column names using snake_case
- Created an `age_group` feature to categorize customers by age
- Created a `purchase_frequency_days` feature to represent purchase frequency in days
- Examined the relationship between `discount_applied` and `promo_code_used`
- Removed the redundant `promo_code_used` column
- Prepared the cleaned dataset for database integration
- Loaded the cleaned data into MySQL for SQL-based analysis

## Key Analysis Areas

- Revenue Analysis by Gender
- High-Spending Customers Using Discounts
- Top 5 Products by Average Customer Rating
- Standard vs. Express Shipping Comparison
- Subscribers vs. Non-Subscribers Analysis
- Products with the Highest Discount Usage
- Customer Segmentation: New, Returning, and Loyal
- Top 3 Products Within Each Category
- Repeat Purchases and Subscription Behavior
- Revenue Contribution by Age Group

## Business Insights

- Compared revenue contributions across male and female customers.
- Identified customers who used discounts but spent above the average purchase amount.
- Evaluated product ratings to identify highly rated products.
- Compared average purchase amounts between Standard and Express shipping customers.
- Analyzed spending patterns and total revenue for subscribers and non-subscribers.
- Identified products with a high proportion of discount-based purchases.
- Segmented customers based on purchase history to understand customer loyalty.
- Analyzed product popularity within individual categories.
- Examined the relationship between repeat purchases and subscription adoption.
- Evaluated revenue contributions across different customer age groups.

## Business Recommendations

- Increase subscription adoption through exclusive benefits, personalized offers, and subscription incentives.
- Strengthen customer loyalty programs using rewards, targeted promotions, and repeat-purchase incentives.
- Optimize discount strategies by evaluating product-level discount usage and protecting profit margins.
- Promote highly rated and frequently purchased products through targeted marketing campaigns.
- Focus marketing efforts on high-revenue customer age groups and relevant customer segments.
- Evaluate shipping preferences to identify opportunities to improve customer experience and support sales growth.

## Project Workflow

1. Imported the customer shopping behavior dataset from a CSV file.
2. Loaded and explored the dataset using Python and Pandas.
3. Cleaned the data and handled missing values.
4. Standardized column names and performed feature engineering.
5. Examined data consistency and removed a redundant column.
6. Loaded the cleaned dataset into MySQL.
7. Wrote SQL queries to analyze customer purchasing behavior and answer business questions.
8. Analyzed revenue, product ratings, discount usage, customer segments, and subscription trends.
9. Connected the analyzed data to Power BI.
10. Developed an interactive dashboard to visualize key metrics and business patterns.
11. Prepared business recommendations based on the analysis.

## Dashboard Preview

Add your Power BI dashboard screenshot here after uploading it to this repository.

Example:

[Customer Shopping Behavior Dashboard](dashboard.jpg)

## Files in This Project

- `customer_shopping_behavior.csv` - Original customer shopping behavior dataset
- `customer_shopping_behavior_analysis.ipynb` - Python notebook for data cleaning, feature engineering, and exploratory data analysis
- `customer_shopping_behavior.sql` - SQL queries for business analysis using MySQL
- `customer_shopping_behavior_dashboard.pbix` - Power BI dashboard file
- `dashboard_screenshot.png` - Dashboard preview image
- `README.md` - Project documentation

## Conclusion

This project demonstrates how customer shopping data can be transformed into actionable business insights using Python, MySQL, and Power BI. The analysis covers customer spending patterns, product performance, discount usage, subscription behavior, and customer segmentation.

By combining data cleaning, SQL-based analysis, and interactive visualization, the project supports data-driven decision-making in customer retention, subscription growth, promotional planning, and product strategy.

## Author

**Sufiyan Nathani**

Aspiring Data Analyst skilled in Python, SQL, MySQL, Microsoft Excel, Power BI, Data Cleaning, Exploratory Data Analysis, Data Visualization, and Business Insights.
