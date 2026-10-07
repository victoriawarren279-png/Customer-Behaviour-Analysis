# Customer Behaviour Analysis

## Project Overview

This project analyses customer purchasing behaviour to identify patterns and factors that may influence purchasing decisions, customer loyalty and sales performance.

The project combines SQL analysis with Power BI visualisation to turn raw customer data into actionable business insights.

## Business Problem

The objective of the analysis was to understand customer purchasing behaviour and identify patterns across:

- Customer demographics
- Product categories
- Purchase behaviour
- Discounts
- Reviews
- Shipping methods
- Customer loyalty
- Subscription status

The analysis was designed to answer specific business questions around what customers purchase, how they purchase and which factors may influence purchasing behaviour.

## Analytical Approach

The project followed an end-to-end analytics workflow:

**Raw Customer Data → SQL Analysis → Business Insights → Power BI Dashboard**

### 1. Data Analysis with SQL

SQL was used to explore the customer dataset and answer business questions relating to:

- Discount usage and purchase amounts
- Product review ratings
- Shipping methods and purchasing behaviour
- Discount patterns across products
- Customer segmentation
- Product performance within categories

The SQL analysis can be found here:

[View SQL Analysis](sql/customer_behaviour_analysis.sql)

## Key Findings

The analysis identified several patterns in customer purchasing behaviour:

- **Male customers generated higher total revenue**, contributing £157,890 compared with £75,191 from female customers.
- **Gloves received the highest average review rating** at 3.86, followed by Sandals (3.84) and Boots (3.82).
- **Express shipping customers had a higher average purchase amount** (£60) compared with Standard shipping (£58).
- **Subscription status had little difference in average spend**, with both subscribers and non-subscribers averaging £59 per purchase. However, non-subscribers generated substantially more total revenue (£170,436) due to having a larger customer base.
- **Discount usage was highest for Hats**, with 50% of purchases involving a discount, followed by Sneakers (49.66%) and Coats (49.07%).
- **The majority of customers were classified as Loyal**, with 3,116 customers compared with 701 Returning and 83 New customers.
- **Clothing showed strong product-level demand**, with Blouses and Pants recording 171 purchases each, followed by Shirts with 169.
- **Repeat buyers were predominantly non-subscribers**, with 2,518 repeat buyers classified as non-subscribers compared with 958 subscribers.
- **Young Adults generated the highest revenue by age group**, contributing £62,143, followed by Middle-Aged customers (£59,197).


### 2. Power BI Dashboard

The findings from the SQL analysis were translated into an interactive Power BI dashboard.

The dashboard provides:

- Customer KPIs
- Average purchase amount
- Average review rating
- Revenue by category
- Sales by category
- Revenue by age group
- Sales by age group
- Subscription analysis

Interactive filters allow users to explore the results by:

- Subscription status
- Gender
- Product category
- Shipping type

[View Power BI Dashboard](power-bi/dashboard.md)

## Key Dashboard Features

### Customer KPIs

The dashboard provides a high-level overview of:

- Number of customers
- Average purchase amount
- Average review rating

### Category Analysis

Revenue and sales are compared across:

- Clothing
- Accessories
- Footwear
- Outerwear

### Customer Demographics

Revenue and sales are analysed across different customer age groups.

### Interactive Analysis

The dashboard allows users to filter the analysis dynamically.

For example, selecting the Clothing category updates the customer KPIs and visualisations to show the behaviour of customers purchasing within that category.

## Tools Used

- SQL Server
- SQL
- Power BI
- DAX
- GitHub

## Project Outcomes

This project demonstrates the ability to:

- Translate business questions into SQL queries
- Analyse customer purchasing behaviour
- Use aggregations, CTEs, CASE statements and window functions
- Segment customers based on purchasing behaviour
- Identify product and category performance
- Build interactive Power BI dashboards
- Connect analytical findings to business questions
- Present data in a clear, decision-focused format

## Project Structure

```text
Marketing-Data-Analysis/
│
├── README.md
│
├── sql/
│   └── customer_behaviour_analysis.sql
│
└── power-bi/
    ├── dashboard.md
    ├── dashboard_overview.png
    └── dashboard_filtered_clothing.png


