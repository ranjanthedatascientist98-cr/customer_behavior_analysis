🛍️ Customer Behavior Analysis
End-to-End Retail Customer Analytics Project using Python, SQL & Power BI

A data-driven customer analytics project focused on understanding shopping behavior, customer loyalty, subscription adoption, product performance, and revenue drivers to generate actionable business recommendations. Built using Python, MySQL, and Power BI.

📌 Project Overview

Retail businesses generate massive amounts of customer transaction data every day. However, transforming this raw data into meaningful business decisions requires a structured analytics workflow.

This project analyzes 3,900 customer transactions across demographics, purchasing behavior, subscriptions, discounts, product categories, shipping preferences, and customer reviews.

The goal was to answer critical business questions such as:

Who generates the most revenue?
Which products perform best?
Do subscriptions increase customer spending?
Are discounts driving sales or hurting margins?
Which customer segments should be targeted for growth?
Why is subscription adoption extremely low?

The project follows a complete analytics lifecycle:

Raw Data → Data Cleaning → Feature Engineering → SQL Analysis → Business Insights → Power BI Dashboard → Strategic Recommendations

🎯 Business Problem

The company wants to:

Increase revenue
Improve subscription adoption
Identify high-value customers
Optimize discount strategies
Improve customer retention
Discover untapped customer segments

This project provides data-backed recommendations to achieve those objectives.

📊 Dataset Information
Metric	Value
Total Records	3,900
Total Columns	18
Missing Values	37
Domain	Retail / E-Commerce
Data Type	Customer Transaction Data
Key Features
Customer Information
Age
Gender
Location
Subscription Status
Purchase Information
Product Purchased
Category
Purchase Amount
Season
Size
Color
Behavioral Information
Previous Purchases
Review Rating
Frequency of Purchase
Discount Applied
Promo Code Used
Shipping Type

🛠️ Technology Stack
Python
Pandas
NumPy
SQLAlchemy
SQL
MySQL
CTEs
Window Functions
Subqueries
Aggregations
BI Tool
Power BI
Documentation
PowerPoint
Business Report

⚙️ Data Engineering & Cleaning

Before analysis, the dataset was transformed and standardized.

Missing Value Treatment

37 missing review ratings were imputed using:

Median Rating by Product Category
Feature Engineering

Created customer age segments:

Age Group
Young Adult
Adult
Middle Aged
Seniors

Converted purchase frequency labels into numerical intervals:

Original Value	Converted
Weekly	7
Bi-Weekly	14
Monthly	30
Annually	365
Database Preparation
Renamed columns using snake_case convention
Removed structural inconsistencies
Loaded cleaned data into MySQL using SQLAlchemy

🔍 SQL Business Analysis

A series of strategic SQL queries were developed to answer real-world business questions.

Analysis Performed

✅ Revenue Contribution by Gender

✅ High-Value Discount Customers

✅ Top Rated Products

✅ Shipping Preference Analysis

✅ Subscription Spending Comparison

✅ Discount Dependency Analysis

✅ Customer Segmentation

✅ Top Products by Category

✅ Repeat Buyers vs Subscription Adoption

✅ Revenue Contribution by Age Group

The project demonstrates:

CTEs
Window Functions
DENSE_RANK()
ROW_NUMBER()
CASE WHEN
Aggregate Functions
Subqueries

📈 Power BI Dashboard
Dashboard KPIs
KPI	Value
Total Customers	3.9K
Average Purchase Amount	$59.76
Average Rating	3.75
Subscription Rate	7.3%
Dashboard Features
Revenue by Category
Sales by Category
Revenue by Age Group
Sales by Age Group
Subscription Analysis
Gender Analysis
Shipping Analysis
Dynamic Filters

💡 Key Business Insights
1. Clothing Dominates Revenue

Clothing generated approximately:

$104,000

making it the strongest-performing category.

Recommendation

Increase inventory allocation and marketing investments for clothing products.

2. Young Adults Generate Highest Revenue

Revenue Contribution:

Segment	Revenue
Young Adult	$62,143
Middle Aged	$59,197
Adult	$55,978
Seniors	$55,763

Young adults are the highest-value customer segment.

3. Subscription Program Underperforms

Only:

7.3%

of customers are subscribed.

More importantly:

Subscribers do NOT spend more than non-subscribers.

This indicates the subscription model is failing to deliver meaningful value.

4. Female Subscriber Gap

One of the most interesting discoveries:

0 Female Customers
Subscribed

Female customers purchase products across all categories, yet none are enrolled in the subscription program.

This represents a significant untapped growth opportunity.

5. Gift Buying Behavior

Products such as:

Blouses
Skirts
Jewelry
Dresses
Scarves
Handbags

are frequently purchased through male customer accounts.

This suggests:

Buyer ≠ End User

The business captures the purchaser but not the actual product user.

6. Loyal Customers Dominate

Customer Segments:

Segment	Count
Loyal	3116
Returning	701
New	83

Approximately 80% of customers belong to the Loyal segment.

This indicates strong retention but weak acquisition.

🚀 Strategic Recommendations
Subscription Growth

Target customers with:

More than 5 Purchases

Offer:

Free Shipping
Cashback Rewards
Early Sale Access

Goal:

Increase Subscription Rate
7.3% → 15%
Within 6 Months
Female Customer Acquisition

Launch:

Women's Premium Club

Benefits:

Exclusive Launches
Loyalty Rewards
Fashion Recommendations
Express Shipping
Early Access Sales
Gift-Based Marketing

Create:

Gifts for Her
Birthday Collection
Anniversary Collection
Valentine's Collection

Expected Impact:

5–10%
Increase in Average Order Value
Family Membership Program

Introduce:

Family Fashion Membership

Benefits:

Shared Reward Points
Couple Discounts
Birthday Rewards
Early Access

📁 Repository Structure
Customer-Behavior-Analysis/
│
├── Dataset/
│   └── customer_shopping_behavior.xlsx
│
├── SQL/
│   └── customer_behavior_analysis.sql
│
├── Python/
│   └── customer_behavior_analysis.ipynb
│
├── PowerBI/
│   └── customer_behavior_dashboard.pbix
│
├── Reports/
│   ├── Customer_Behavior_Analysis_Report.pdf
│   └── Presentation.pptx
│
├── Dashboard_Screenshots/
│
└── README.md
🎓 Skills Demonstrated
Data Analytics
Data Cleaning
Data Wrangling
Exploratory Data Analysis
Feature Engineering
Statistical Thinking
SQL
Complex Queries
Window Functions
Customer Segmentation
Business KPI Analysis
Python
Pandas
Missing Value Treatment
Data Transformation
Business Analytics
Power BI
KPI Design
Interactive Dashboards
Data Storytelling
Business Visualization
Business Intelligence
Revenue Analysis
Customer Segmentation
Subscription Optimization
Customer Acquisition Strategy

📌 Project Outcome

This project demonstrates the complete workflow expected from a modern Data Analyst:

✔ Data Cleaning & Preparation

✔ SQL-Based Business Analysis

✔ Customer Segmentation

✔ Power BI Dashboard Development

✔ Strategic Business Recommendations

✔ Executive-Level Reporting

The analysis identified three major growth opportunities:

Increase subscription adoption.
Convert female end-users into direct customers.
Improve new customer acquisition while leveraging the strong loyal customer base.
👨‍💻 Author

Chittaranjan Mohapatra
Data Analyst | SQL | Python | Power BI | Business Intelligence

"Turning customer data into actionable business decisions."
