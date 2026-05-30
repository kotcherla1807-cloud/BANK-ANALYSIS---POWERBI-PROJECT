Project Overview

The Banking Analytics Dashboard is a Power BI project developed to analyze banking customer information and financial metrics. The dashboard provides insights into customer count, total balance, average credit score, risk status, and branch-wise performance analysis.

This project helps in understanding customer banking behavior, identifying high-risk customers, monitoring branch performance, and supporting better decision-making using data visualization.

Dashboard Preview

(Add your dashboard screenshot here)

Example:

![Banking Analytics Dashboard](dashboard.png)

You can upload your screenshot to GitHub and rename it as dashboard.png.

Project Objective

The main objective of this project is to:

Analyze banking customer data
Monitor branch-wise customer performance
Calculate total balances and customer count
Evaluate average credit scores
Identify high-risk and low-risk customers
Create interactive Power BI visualizations
Tools & Technologies Used
Power BI Desktop
Microsoft Excel / CSV Dataset
DAX (Data Analysis Expressions)
Power Query
Data Visualization Techniques
Dataset Description

The dataset contains customer banking information such as:

Column Name	Description
Customer_ID	Unique customer ID
Customer_Name	Name of customer
Branch	Bank branch location
Balance	Customer account balance
Credit Score	Customer credit score
Risk_Status	High Risk / Low Risk
Step-by-Step Process of the Project
Step 1: Data Collection

Collected banking customer data from dataset sources such as Excel/CSV files.

Process:
Imported customer banking dataset
Verified missing values
Checked data consistency
Step 2: Data Cleaning & Transformation

Performed data preprocessing using Power Query Editor.

Activities Performed:
Removed duplicate values
Handled missing values
Corrected branch names

Example:

Before	After
Blr	Bangalore
Chn	Chennai
Hyd	Hyderabad
Changed data types
Cleaned unnecessary columns
Step 3: Data Modeling

Created relationships and structured data for analysis.

Actions:
Defined relationships between tables
Organized customer data
Created calculated fields
Step 4: Creating DAX Measures

Created important DAX measures for KPI calculations.

Total Balance
Total Balance = SUM(Banking[Balance])
Customer Count
Customer Count = COUNT(Banking[Customer_ID])
Average Credit Score
Average Credit Score = AVERAGE(Banking[Credit Score])
High Risk Customers
High Risk Customers =
CALCULATE(
COUNT(Banking[Customer_ID]),
Banking[Risk_Status]="High Risk"
)
Low Risk Customers
Low Risk Customers =
CALCULATE(
COUNT(Banking[Customer_ID]),
Banking[Risk_Status]="Low Risk"
)
Step 5: Dashboard Design

Designed an interactive Banking Analytics Dashboard using Power BI visualizations.

KPIs Added
Total Balance
Customer Count
Average Credit Score
Charts Used
1. Average Credit Score by Branch

Used a Bar Chart to compare branch-wise credit scores.

2. Customer Count & Risk Analysis

Used a Pie Chart to visualize:

High Risk Customers
Low Risk Customers
3. Total Balance by Branch

Used an Area/Line Chart for branch-wise balance analysis.

4. Highest Balance by Branch

Used a Funnel Chart to compare branch performance.

5. Summary Table

Created a detailed table showing:

Branch
Customer Count
Total Balance
Average Credit Score
High Risk Customers
Low Risk Customers
Step 6: Adding Filters (Slicers)

Implemented slicers for better interactivity.

Branch Filter

Users can filter dashboard insights based on:

Bangalore
Chennai
Hyderabad

This improves user interaction and dynamic reporting.

Step 7: Dashboard Insights

Key insights generated from the dashboard:

Hyderabad branch shows higher customer balance.
Credit scores are similar across branches.
Low-risk customers are higher than high-risk customers.
Customer distribution differs branch-wise.
Dashboard Features

✔ Interactive Dashboard
✔ Dynamic Filtering
✔ KPI Monitoring
✔ Risk Analysis
✔ Branch-wise Comparison
✔ Customer Analytics
