# E-commerce Customer Behaviour Analysis|Excel Dashboard
## Project Overview
This data analysis project focused on understanding e-commerce customer purchasing behaviour, sales performance, product trends, and customer demographics using Microsoft Excel.
The project transforms raw transactional data into an interactive dashboard using data cleaning, formulas, PivotTables, charts, slicers, and geographic visualization.
## Dataset Used
-<a href=https://github.com/KhushiPanchi/e-commerce-customer-behaviour-analysis/blob/main/dataset.csv>Dataset</a>
## Business Objective
The analysis focuses on:
- Identifying high-engagement customer age groups.
- Understanding customer demographics through gender distribution.
- Evaluating sales performance across different states.
- Identifying top-performing product categories.
- Analyzing customer payment preferences.
- Examining the relationship between customer ratings, delivery time, and discounts. 
- Evaluating order fulfillment performance through delivered, cancelled, and returned orders.
- Tracking key business KPIs, including total sales, total orders, and successfully delivered orders.
## Dashboard Preview
-<a href=https://github.com/KhushiPanchi/e-commerce-customer-behaviour-analysis/blob/main/dashboard.png>Dashboard</a>
## Project Workflow
### 1.Raw Data
- Collected a 4,000-row E-Commerce Customer Behaviour dataset
- Dataset contains customer, order, product, sales, discount, payment, and delivery-related information.
- Key fields include : Order_ID,Customer_ID,Order_Date,Customer_Age,Gender,City,State,Category,Sub_Category,Product_Name,Quantity,Unit_Price,Discount,Payment_Method,Order_Status,Customer_Rating,Delivery_Days,Category_sales.
### 2.Data Cleaning & Preparation
- Checked for duplicate records
- Identified and handled missing values
- Corrected data types and formatting
- Standardized categorical values such as Gender, City, Category, Payment Method, and Order Status
- Verified numerical fields such as Quantity, Sales, Discount, Rating, and Delivery Days
- Created/validated calculated fields required for analysis such as Total_Price, Discounted_Price.
### 3.Analysis
Used Excel PivotTables and calculated metrics to analyze:
- Customer shopping frequency by age group
- Gender distribution
- Total sales by city
- Total sales by product category
- Payment method preferences
- Average delivery days and discount
- Delivery/order status distribution
- Key performance indicators (KPIs) such as: Total Sales,Total Orders,Successfully Delivered Orders 
### 4.Visualization
-	Bar Chart: Order Status Detail, Age Distribution
-	Pie Chart: Gender Ratio
-	Donut Chart: Payment Method Distribution
-	KPIs: Delivered count, Total Sales, Total orders
-	Slicer: State 
-	Column Chart: Total sales as per category
-	Funnel Chart: Total sales as per sub-category

![E-Commerce Customer Behaviour Dashboard](https://github.com/KhushiPanchi/e-commerce-customer-behaviour-analysis/blob/main/dashboard.png)
## Future Enhancements
-	Power BI Dashboard: Recreate the Dashboard in power bi with more advanced interactive visualizations.
-	Trend Analysis: Analyze monthly and yearly sales trends to identify seasonality and growth patterns.
- Predictive Analysis: Use Python and machine learning to predict customer purchasing behaviour, sales, and customer churn.
-	Automated Data Refresh: Use Power Query to automate data cleaning and dashboard updates when new data is added.
-	Database Integration: Store and manage the e-commerce data in a SQL database and connect it directly to the analytics dashboard.
## Conclusion
The E-Commerce Customer Behaviour Analysis project demonstrates how raw e-commerce data can be transformed into meaningful business insights using Microsoft Excel. Through data cleaning, analysis, PivotTables, KPIs, and interactive visualizations, the project provides a clear understanding of customer behaviour, sales performance, product categories, payment preferences, and delivery performance.
