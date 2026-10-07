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
