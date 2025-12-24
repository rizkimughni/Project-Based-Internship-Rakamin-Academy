Project Based Internship - Bank Muamalat Business Intelligence Analyst x Rakamin Academy
Business Intelligence Sales Analysis Project

PT Sejahtera Bersama

As a Business Intelligence Analyst at PT Sejahtera Bersama, our role is to analyze historical sales data from 2020–2021, design interactive dashboards using data visualization tools, and deliver actionable insights to help maintain and improve sales performance.

Dataset 📊

This project utilizes four CSV datasets:

Customers.csv – Contains detailed customer information

Orders.csv – Stores transaction and order records

ProductCategory.csv – Defines product category classifications

Products.csv – Provides detailed product information

Tools 🛠️

The following tools will be used throughout the project:

Google BigQuery – Data storage and SQL querying
LookerStudio – Dashboard and data visualization creation
GitHub – Version control and storage of SQL queries and outputs
Canva – Final presentation of findings and recommendations

Tasks 🎯

You are required to import all provided datasets into Google BigQuery, ensuring that each table name matches the original dataset name without the .csv extension.
You must complete five challenges as outlined below:

Challenge 1: Identify Primary Keys
Determine the primary key for each dataset:
Primary key of the Customers table
Primary key of the Products table
Primary key of the Orders table
Primary key of the ProductCategory table

Challenge 2: Define Table Relationships
Identify and explain the relationships among the four tables.

Challenge 3: Create a Master Table
Build a consolidated table containing the following fields:
CustomerEmail → cust_email
CustomerCity → cust_city
OrderDate → order_date
OrderQty → order_qty
ProductName → product_name
ProductPrice → product_price
ProductCategoryName → category_name
TotalSales → total_sales
The data must be sorted by transaction date, from the earliest to the latest, and the column order should follow the structure shown in the example image.

Challenge 4: Data Export & Visualization
Export the master table from Challenge 3 into CSV format. Using data visualization tools, create dashboards that include at least:
Total overall sales
Total sales by product category
Total quantity sold by product category
Total sales by city
Total quantity sold by city
Top 5 product categories by sales
Top 5 product categories by quantity sold
