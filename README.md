#  Supply Chain Performance Analysis

## Project Overview

This project analyzes the delivery performance of a global e-commerce supply chain using a dataset of more than 180,000 orders. The objective was to understand why deliveries are getting delayed, measure their impact on business performance, and identify opportunities to improve logistics operations.

The analysis covers the complete workflow from cleaning raw data to generating business insights and recommendations. Python was used for data preprocessing, exploratory analysis, KPI tracking, and identifying operational bottlenecks across different business dimensions.

The project includes:

- Data Cleaning & Preprocessing
- Feature Engineering
- Exploratory Data Analysis (EDA)
- KPI Development
- Root Cause Analysis
- Time-Series Analysis
- Business Recommendations

---

## Business Problem

The company was facing frequent delays between the expected delivery date and the actual shipment completion date. These delays affected customer experience, reduced delivery reliability, increased operational inefficiencies, and impacted profitability.

The goal of this project was to identify the major reasons behind delayed deliveries and provide practical recommendations that could help improve supply chain performance.

---

## Project Objectives

- Analyze the impact of delayed deliveries on profitability.
- Identify the major factors contributing to shipment delays.
- Compare delivery performance across regions and shipping modes.
- Study seasonal and time-based delivery trends.
- Generate business recommendations to improve logistics operations.

---

## Data Cleaning & Preprocessing

Before starting the analysis, the dataset was cleaned and prepared by removing unnecessary columns, handling missing values, fixing inconsistent records, standardizing categorical variables, and converting date columns into appropriate formats for analysis.

---

## Feature Engineering

Additional business metrics were created to better evaluate delivery performance. These include:

- Order Processing Time
- Delivery Delay
- Shipping Delay Percentage
- Profit/Loss Category
- Delivery Status

These features made it easier to compare scheduled deliveries with actual delivery performance.

---

## Exploratory Data Analysis

The dataset was explored from multiple business perspectives to understand delivery performance and identify operational issues.

The analysis included:

- Profitability Distribution
- Delay Percentage Analysis
- Region-wise Delivery Performance
- Shipping Mode Comparison
- Department-wise Performance
- Correlation between Delivery Delays and Profitability

Some important observations from the analysis were:

- More than 55% of orders were delivered late.
- First Class shipping showed higher delay rates than expected.
- Certain regions consistently recorded poor delivery performance.
- Delivery delays had a noticeable impact on overall profitability.

---

## KPI Development

Several business KPIs were created to monitor supply chain performance, including:

- Delayed Order Percentage
- Average Delivery Delay
- Profit at Risk due to Delays
- 90th Percentile Delay
- High Delay Regions
- Shipping Mode Performance
- Department-wise Operational Efficiency

---

## Root Cause Analysis

A detailed analysis was performed across different business dimensions such as regions, shipping modes, departments, customer segments, and order status.

The analysis revealed that Central Africa had one of the highest delay percentages. First Class shipping experienced significantly more delays than Standard Class. Seasonal demand spikes increased operational pressure, while payment processing delays also contributed to late shipments.

---

## Time-Series Analysis

Delivery performance was analyzed across different time periods, including monthly, weekly, and hourly trends.

This helped identify peak operating hours with the highest shipment delays, recurring weekly patterns, and seasonal periods where logistics performance dropped significantly.

---

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Key Insights

- More than half of all deliveries were delayed.
- Delivery delays directly affected business profitability.
- Some regions and departments consistently underperformed.
- First Class shipping recorded higher-than-expected delays.
- Seasonal order surges created major operational bottlenecks.

---

## Business Recommendations

Based on the findings, the following recommendations were suggested:

- Automate alerts for payment processing delays exceeding two hours.
- Improve inventory allocation for departments with frequent delays.
- Review carrier performance for underperforming shipping modes.
- Strengthen workforce planning during peak demand periods.
- Build real-time dashboards to monitor delivery performance.

---

## Project Outcome

The project successfully identified the major operational issues affecting delivery performance and profitability. The insights generated from the analysis can help improve logistics efficiency, operational planning, delivery reliability, and customer satisfaction.
