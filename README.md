# Customer Shopping Behavior Analysis

A complete end-to-end data analytics project analyzing customer shopping behavior using Python, SQL, and Power BI to generate business insights and recommendations.

This project explores 3,900+ transactions to understand spending patterns, customer segments, product performance, and subscription behavior.

📌 Project Objectives

Analyze customer purchasing behavior across demographics and categories

Identify high-value customers and products

Understand the impact of discounts, subscriptions, and shipping types

Build a business-ready interactive dashboard

Provide actionable recommendations for marketing and operations

🗂 Project Structure
File	Description
customer_shopping_behavior.csv	Raw dataset
Customer_Shopping_Behaviour_Analysis.ipynb	Data cleaning, EDA & feature engineering
Customer Behaviour.sql	SQL queries for business analysis
Customer behaviour dashboard.pbix	Interactive Power BI dashboard
project report.pdf	Final report with insights & recommendations
🧰 Tools & Technologies

Python (Pandas, NumPy, Matplotlib, Seaborn)

SQL (MySQL / PostgreSQL for analysis)

Power BI (dashboard and visualization)

Jupyter Notebook (analysis workflow)

📊 Dataset Overview

Rows: 3,900

Columns: 18

Key features:

Customer: Age, Gender, Location, Subscription Status

Purchase: Category, Item Purchased, Purchase Amount, Season

Behavior: Discount Applied, Review Rating, Shipping Type, Frequency

Missing values in review_rating were handled by imputing the median rating per product category 

project report

🔍 Analysis Performed
Python (EDA & Cleaning)

Column standardization (snake_case)

Missing value treatment (review ratings)

Feature engineering:

age_group

purchase_frequency_days

Dropped redundant fields (promo_code_used)

SQL Business Analysis

Key questions answered:

Revenue by gender

High-spending discount users

Top 5 products by rating

Shipping type comparison (Express vs Standard)

Subscribers vs Non-Subscribers revenue

Top 3 products per category

Repeat buyers and subscription likelihood

Revenue by age group

(Results are shown with tables in the report pages 3–6.) 

project report

📈 Dashboard (Power BI)

An interactive dashboard was created to visualize:

Revenue by category and age group

Subscription distribution

Sales trends

Product performance

Dashboard screenshot and layout are available in the report (page 7). 

project report

💡 Business Recommendations

From the analysis:

Promote exclusive benefits for subscribers

Reward repeat buyers to increase loyalty

Highlight top-rated and best-selling products in campaigns

Focus marketing on high-revenue age groups and express-shipping users

Balance discount strategies to avoid margin loss

(See page 8 for full recommendations.) 

project report

🚀 How to Run

Clone the repo

Open Customer_Shopping_Behaviour_Analysis.ipynb in Jupyter

Run all cells to reproduce analysis

Load SQL file into your database for queries

Open .pbix file in Power BI to explore dashboard

🧠 Outcome

This project demonstrates:

Practical data cleaning and feature engineering

Business-driven SQL analysis

Dashboard storytelling for decision-makers

It’s designed to simulate a real-world analytics workflow from raw data → insights → business action.
