# Retail Customer Retention Analytics with Power BI

## Project Overview

This project analyzes Target customer data using Power BI to understand customer churn, retention, purchasing behavior, loyalty performance, promotion impact, store performance, and Customer Lifetime Value (CLV).

## Objective

- Analyze customer churn and retention
- Identify repeat purchasing behavior
- Evaluate loyalty tier performance
- Analyze promotion usage and purchase amounts
- Compare store and channel performance
- Calculate Customer Lifetime Value (CLV)
- Identify customer segments for retention strategies

## Dataset

The project uses multiple CSV files covering:

- Customer Demographics
- Customer Transactions
- Churn Labelled Customers
- Store Locations
- Related customer and transaction data

The datasets were loaded into Power BI and relationships were created between the tables.

## Tools & Technologies

- Power BI
- Power Query
- DAX
- Data Cleaning
- Data Modeling
- Data Visualization

## Data Preparation & Cleaning

- Standardized column formats
- Extracted date attributes from membership and transaction dates
- Created Transaction Year and Transaction Month
- Loaded five CSV files into Power BI
- Created and validated relationships between tables
- Merged customer transaction and store information where required

## Analysis Performed

### 1. Churn & Retention Analysis

Created DAX measures for:

- Total Customers
- Churned Customers
- Churn Rate
- Repeat Customers
- Repeat Customer Percentage

Analyzed churn by:

- Region
- Income Group
- Sales Channel
- Loyalty Tier

Created a customer retention funnel showing:

- Total Customers
- Repeat Customers
- Churned Customers

### 2. Repeat Purchase Analysis

Calculated customer purchase frequency and created customer segments:

- Low Tier
- Mid Tier
- High Tier

Analyzed:

- Average purchase frequency by region
- Average purchase frequency by income level
- Customer segment distribution
- Most purchased product categories
- Product categories purchased by loyal customers

### 3. Promotion & Loyalty Analysis

Created measures to analyze:

- Promotion transaction percentage
- Average purchase amount with promotions
- Average purchase amount without promotions

Also analyzed:

- Churn by loyalty tier
- Points earned vs points redeemed

### 4. Store & Channel Performance

Merged customer transaction data with store location information.

Analyzed:

- Average transaction amount by store type
- Churn by store type
- Customer retention by store opening year

### 5. Customer Lifetime Value (CLV)

Calculated:

- Customer Total Spend
- Membership Duration
- Customer Lifetime Value
- Average Customer CLV

Created CLV segments:

- High CLV
- Low CLV

Analyzed CLV by:

- Loyalty Tier
- Region
- Days Since Last Purchase

### 6. Repeat Customer Analysis

Created measures to identify customers with more than one purchase and calculated the repeat customer percentage.

## Key Insights

- Basic Tier customers generated the highest CLV.
- Central Region showed the highest average CLV.
- 66.7% of customers belonged to the Low CLV segment.
- The analysis identified customer churn patterns across loyalty tiers, regions, income groups, and sales channels.
- Customer purchase frequency was analyzed across different customer segments.
- Promotion usage and loyalty point activity were analyzed to understand customer engagement.

## Dashboard

The final Power BI solution contains four interactive report pages featuring:

### KPI Cards

- Total Customers
- Churned Customers
- Churn Rate
- Promotion Percentage
- CLV Metrics

### Interactive Filters

- Region
- Income Level
- Loyalty Tier
- Sales Channel

### Analytical Visualizations

- Churn Analysis
- Retention Analysis
- Promotion Impact
- Loyalty Performance
- Store Performance
- CLV Analysis
- Customer Segmentation
- Repeat Purchase Analysis

## Business Recommendations

- Focus retention strategies on Basic-tier customers due to their higher churn.
- Increase loyalty point redemption through targeted campaigns and personalized offers.
- Provide exclusive benefits for Premium and Elite customers to strengthen loyalty.
- Use CLV segmentation to identify customers who may benefit from personalized retention strategies.

## Project File

`Dashboard.pbix`
