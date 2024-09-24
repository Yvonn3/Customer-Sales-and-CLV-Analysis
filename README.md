# Customer-Sales-and-CLV-Analysis

## Project Overview

This project analyzes customer sales data to gain insights into customer behavior, sales patterns, and Customer Lifetime Value (CLV). The analysis aims to inform business decisions related to customer acquisition, retention, and marketing strategies, with a particular focus on understanding and optimizing CLV.

## Data Source

The project uses a dataset named 'customer_sales.csv', which contains information about customer orders, including order dates, customer details, product information, sales, and profits.

## Project Workflow

1. **Data Understanding and Preprocessing**
   - Import and initial exploration of the dataset
   - Handling missing values
   - Data type conversions (e.g., date formatting)

2. **Exploratory Data Analysis (EDA)**
   - Analysis of date ranges in the dataset
   - Identification of unique customers and orders
   - Statistical analysis of sales data
   - Investigation of sales trends over time

3. **Outlier Detection and Handling**
   - Identification of outliers in sales data
   - Treatment of outliers for further analysis

4. **Discount Analysis**
   - Examination of the relationship between discounts, sales, and profits
   - Visualization of sales and profit at different discount levels

5. **Factor Analysis**
   - Regression analysis to identify factors affecting sales

6. **Customer Segmentation**
   - Determination of customer origin year
   - Calculation of customer age (tenure)

7. **Transaction Analysis**
   - Calculation of cumulative transaction amounts
   - Analysis of new customer acquisition over time

8. **Customer Lifetime Value (CLV) Analysis**
   - Calculation of historic CLV
   - Visualization and interpretation of CLV trends

## Key Findings

1. The dataset covers sales from 2011 to 2014.
2. There are 793 unique customers and 4,117 unique orders in the dataset.
3. Outliers in sales data were identified and treated.
4. The optimal discount level for maximizing profit appears to be around 10%.
5. Product name and city are significant factors affecting sales.
6. Customer Lifetime Value (CLV) tends to increase with customer tenure.
7. Customers acquired in 2011 have spent approximately $3,268 to date.
8. Retaining existing customers appears more beneficial than acquiring new ones, based on CLV analysis.

## Recommendations

1. Focus on customer retention strategies, as longer-tenured customers tend to have higher CLV.
2. Optimize discount strategies, considering the 10% discount level for maximizing profits.
3. Tailor marketing and sales strategies based on city-specific trends.
4. Investigate product-specific sales patterns to optimize inventory and marketing.
5. Develop targeted strategies for customers based on their tenure and spending patterns.
