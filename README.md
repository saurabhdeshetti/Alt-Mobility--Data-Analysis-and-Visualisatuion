# Alt Mobility - Data Analysis and Visualisation
## Overview

This repository contains SQL queries and analysis scripts designed to evaluate Alt Mobility’s order, sales, payment, and customer retention data.
The goal is to provide actionable insights to improve business performance and customer experience.

## Approach
### 1. Data Extraction & Preparation

 •	Data Sources:
   1. `customer_orders`: Contains order-level details.
   2. `payments`: Contains payment transaction details.
   3. `cohort table`: Created and Used for cohort analysis.
    
•	Joins & Filtering:
1. Orders and payments are joined on `order_id` for comprehensive reporting.
2. Filtering is applied to focus on delivered orders for 'Revenue' and 'Average Order Value' calculations.

### 2. SQL Query Design
  
•	Order & Sales Analysis:
1. Distribution of order statuses to assess fulfillment efficiency.
2. Monthly revenue and order trends to identify seasonality and growth.
3. Average order value to benchmark customer spending.

•	Customer Analysis:
1. Identification of repeat customers to measure engagement.
2. Segmentation of new vs returning customers by month for acquisition and retention insights.

•	Payment Analysis:
1. Distribution and success rates of payment statuses.
2. Analysis of payment failures by method to identify process improvements.

•	Order Details Report:
1. Comprehensive view combining order and payment data for operational monitoring.

•	Customer Retention (Cohort Analysis):
1. Cohorts defined by first purchase month.
2. Retention measured as the number of customers making repeat purchases in subsequent months.

### 3. Visualization & Reporting
  
•	Data is prepared for visualization of trends and cohort tables using `Tableau`.

•	Key findings are summarized for business applications.

## How to Use
1.	Run SQL Queries:

	•	Execute queries on your database to generate raw data outputs.

4.	Analyze Results:
  
	•	Use outputs for visualization and further analysis.

3.	Review Findings:
  
	•	Refer to the Summary of Findings for actionable insights and recommendations.
