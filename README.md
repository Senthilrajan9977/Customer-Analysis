🛍️ Customer Shopping Behavior Analysis
📊 Project Overview

This project analyzes customer shopping behavior using transactional data from 3,900 purchases across multiple product categories. The main objective is to uncover insights into spending patterns, customer segmentation, product preferences, and subscription behavior to support data-driven business strategies.

🧾 Dataset Summary

Rows: 3,900

Columns: 18

Key Features:

Customer demographics: Age, Gender, Location, Subscription Status

Purchase details: Item Purchased, Category, Purchase Amount, Season, Size, Color

Shopping behavior: Discount Applied, Promo Code Used, Review Rating, Shipping Type, Previous Purchases, Frequency of Purchases

Missing Data: 37 missing values in Review Rating (handled via median imputation by product category)

🐍 Exploratory Data Analysis (Python)

Performed extensive data cleaning, transformation, and feature engineering in Python using pandas, numpy, and matplotlib:

Checked dataset structure and summary statistics

Handled missing values using category-wise median imputation

Standardized column names for readability

Created derived features:

age_group (age binning)

purchase_frequency_days (calculated from transaction data)

Verified redundancy between discount and promo features

Loaded the cleaned data into a PostgreSQL database for SQL-based business analysis

🧮 Data Analysis (SQL)

Executed advanced SQL queries in PostgreSQL to extract key business insights, including:

Revenue by Gender — Comparison of total spending by male vs. female customers

High-Spending Discount Users — Identifying customers who spend above average despite discounts

Top 5 Products by Rating — Highest-rated items based on average review scores

Shipping Type Comparison — Revenue difference between Standard and Express shipping

Subscribers vs. Non-Subscribers — Spending patterns and revenue contribution

Discount-Dependent Products — Top 5 products with the highest discount reliance

Customer Segmentation — Classification into New, Returning, and Loyal customers

Top Products per Category — Most frequently purchased items within each product category

Repeat Buyers & Subscription Trends — Correlation between repeat purchase behavior and subscription rates

Revenue by Age Group — Contribution analysis by customer age segment

📈 Dashboard (Power BI)

An interactive Power BI dashboard was built to visualize insights, featuring:

Revenue breakdowns by gender, category, and age group

Customer segmentation metrics

Purchase frequency and discount impact visualizations

Subscription performance analytics

💡 Business Recommendations

Boost Subscriptions: Promote exclusive offers for subscribers

Loyalty Programs: Incentivize repeat buyers with rewards

Discount Strategy: Optimize discount policies to protect margins

Product Positioning: Highlight top-rated and best-selling items

Targeted Marketing: Focus campaigns on high-revenue demographics and express-shipping users

🧰 Tech Stack

Languages: Python, SQL

Libraries: pandas, numpy, matplotlib, seaborn

Database: PostgreSQL

Visualization: Power BI

Tools: Jupyter Notebook, SQL Workbench
