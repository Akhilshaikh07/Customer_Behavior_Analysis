# Customer Behavior Analysis – End-to-End Data Analyst Project
🔍 Overview

This project presents a complete end-to-end data analysis workflow using Python, SQL (MySQL), and Power BI to analyze customer purchasing behavior.

The objective is to clean and explore raw data, perform structured analysis using SQL, and deliver actionable business insights through an interactive Power BI dashboard.

# Dataset

Source: Customer purchase dataset

Format: CSV

Records: 627 customers

Main Features:

Customer demographics (gender, age group)

Purchase behavior (purchase amount, previous purchases)

Product details (category, item purchased)

Subscription status

Shipping type

Discount usage

Review ratings

# 🛠 Tools & Technologies
Python (Jupyter Notebook)

Data Cleaning & EDA

Libraries:

pandas

numpy

matplotlib

seaborn

SQL (MySQL)

Data storage and analytical querying

Concepts used:

Aggregations (SUM, AVG, COUNT)

Subqueries

CTEs

Window functions (ROW_NUMBER)

CASE statements

Power BI

Data modeling & relationships

DAX measures

Interactive dashboards & KPIs

⚙️ Project Workflow
1 Data Loading (Python)

Imported raw CSV data into Jupyter Notebook using Pandas.

Reviewed dataset structure, column types, and data volume.

2 Exploratory Data Analysis (EDA)

Performed EDA to understand customer behavior and data quality:

Checked missing values and duplicates

Analyzed distribution of:

Purchase amounts

Review ratings

Categories and age groups

Visualized trends using bar charts and summary statistics

3 Data Cleaning & Preparation

Handled missing and inconsistent values

Standardized categorical fields (Yes/No, text columns)

Corrected data types for numerical and categorical columns

Prepared a clean dataset for SQL and Power BI analysis

4 SQL Analysis (MySQL)

Loaded cleaned data into MySQL and answered key business questions:

🔹 Key SQL Insights

Revenue comparison by gender

Customers who used discounts but spent above average

Top 5 products with highest average review ratings

Impact of shipping type on purchase amount

Subscription vs non-subscription spending behavior

Products with highest discount usage rate

Customer segmentation:

New

Returning

Loyal

Top 3 products per category

Subscription likelihood of repeat buyers

Revenue contribution by age group

5 Power BI Dashboard

Built an interactive dashboard to visualize insights:

📌 KPIs

Total Customers: 627

Average Purchase Amount: $60.73

Average Review Rating: 3.77

📊 Visuals

Revenue by category

Revenue by age group

Subscription split

Customer segment performance

Shipping type comparison

🎛 Filters & Slicers

Subscription status

Gender

Category

Shipping type

📈 Key Business Insights

Clothing category generates the highest revenue

Subscribed customers contribute higher average spend

Discounts do not necessarily reduce revenue

Loyal customers show stronger subscription behavior

Younger and adult age groups drive most revenue

