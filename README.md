# Credit-Card-Dashbord

This dashbord the analyzes credit card customers and transaction behavior patterns using PostgreSQL and Power BI.
The dashboard provides insights into revenue generation, customer segmentation, and spending patterns.

Tools -
PostgreSQL – Data storage and processing
Power BI – Data visualization and dashboard creation
SQL – Data extraction and transformation
DAX – Calculations and KPIs

Dataset-
Customer details (age, income group, job, education, marital status)
Credit card details (card category, credit limit, utilization, Transaction, Total Revenue)

Key KPIs-
Total Revenue: 11M
Total Interest Earned: 8M
Total Transaction Amount: 46M
Total Transaction Count: 667K
Customer Satisfaction Score (CSS): 3.2

Dashboard Features
1. Customer Analysis
Revenue by Age Group
Revenue by Income Group
Revenue by Education Level
Revenue by Marital Status
Revenue by Number of Dependents

2. Geographic Insights
Top 5 States contributing to revenue

3. Transaction Analysis
Revenue vs Total Transaction Trend (Quarter-wise)
Revenue by Expenditure Type (Fuel, Grocery, Travel, etc.)
Revenue by Card Category (Blue, Silver, Gold, Platinum)
Revenue by Usage Mode (Swipe, Chip, Online)

4. Time-Based Analysis
Weekly Revenue Trends
Quarter-wise performance comparison (Q1–Q4)

DAX Measures Used-
Total Revenue
Current Week Revenue
Previous Week Revenue
Week-over-Week Growth %
Week-over-Week Revenue Change
Income & Age Group

How to Run the Project -
Import CSV files into PostgreSQL
Create tables using SQL scripts
Load data using COPY command
Connect Power BI to PostgreSQL database
Refresh the dashboard
