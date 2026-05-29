# 🛒 E-Commerce Company Case Study – SQL Data Analysis Project
## 📖 Project Overview
This project is a complete MySQL-based E-Commerce Data Analysis Case Study focused on extracting actionable business insights from transactional data.  
As a Data Analyst, the objective of this project was to analyze customer behavior, product performance, sales trends, and inventory patterns using SQL queries and business intelligence techniques.  
The project simulates real-world business scenarios commonly faced in e-commerce organizations and demonstrates practical SQL problem-solving skills.  

## 🎯 Business Objectives  
The analysis focuses on the following business areas:  
•	Customer Insights  
Understand customer distribution, buying frequency, and acquisition trends.  
•	Product Analysis  
Identify high-performing and low-performing products/categories.  
•	Sales Optimization  
Analyze revenue trends, monthly growth, and average order value.  
•	Inventory Management  
Detect fast-moving products and potential inventory mismatches.  

🗂️ Dataset 
The project uses four relational datasets:
1. Customers
Column Name	Description
customer_id	Unique customer ID
name	Customer name
location	Customer city/location
2. Products
Column Name	Description
product_id	Unique product ID
name	Product name
category	Product category
price	Product price
3. Orders
Column Name	Description
order_id	Unique order ID
order_date	Date of order
customer_id	Customer placing the order
total_amount	Total order amount
4. Order Details
Column Name	Description
order_id	Order reference
product_id	Product reference
quantity	Quantity ordered
price_per_unit	Unit price

🧹 Data Cleaning & Validation
Before analysis, multiple data quality checks were performed:
•	Duplicate detection
•	Null value checks
•	Blank value checks
•	Invalid quantity and pricing validation
•	Future/incorrect date validation
•	Referential integrity checks
•	Order total consistency verification

📊 Key Business Insights
1️) Product Category Distribution
•	Electronics products dominate the catalog.
•	Wearable Tech and Photography categories have comparatively fewer products.

2️) Top Customer Locations
Top 3 cities with highest customer count:
•	Delhi
•	Chennai
•	Jaipur
This insight helps in targeted regional marketing campaigns.

3️) Customer Order Frequency Analysis
Most customers placed:
•	1 to 3 orders
•	Very few customers placed more than 5 orders
This indicates opportunities for customer retention and loyalty programs.

4️) Category Popularity Analysis
Categories with highest unique customer reach:
1.	Electronics
2.	Wearable Tech
3.	Photography
Electronics showed the broadest customer appeal.

5️) Month-on-Month Sales Growth Analysis
Sales trends were analyzed using SQL Window Functions.
Key findings:
•	Strong sales spikes in:
o	July 2023
o	September 2023
o	December 2023
•	Major decline observed in February 2024.

6️) Largest Sales Decline
•	February 2024 recorded the highest negative sales growth.
This may indicate:
•	Seasonal demand drop
•	Marketing inefficiency
•	Inventory shortages

7️) Average Order Value (AOV) Trends
AOV analysis revealed:
•	Significant increase during festive/high-demand periods
•	Sharp drop in February 2024
Useful for pricing and promotional strategy planning.

8️) Fastest Moving Products
Top products based on turnover rate:
•	Digital SLR Camera
•	Bluetooth Headphones
•	Portable Bluetooth Speaker
These products may require:
•	Frequent restocking
•	Better inventory planning

9️) Low Customer Penetration Products
Products purchased by less than 40% of customers:
•	Smartphone 6"
•	Wireless Earbuds
This indicates possible:
•	Low demand
•	Pricing issues
•	Product-market mismatch

10) Customer Growth Analysis
Customer acquisition trends were analyzed month-wise.
Observations:
•	Strong growth in April 2023
•	Declining new customer growth toward late 2023 and early 2024

1️1) Peak Sales Months
Top-performing months:
•	September 2023
•	December 2023
•	July 2023
Useful for:
•	Staffing
•	Inventory forecasting
•	Marketing campaign planning

🛠️ SQL Concepts Used
This project demonstrates practical usage of:
•	Joins
•	Common Table Expressions (CTEs)
•	Aggregate Functions
•	Window Functions
•	Date Functions
•	Subqueries
•	Data Validation Queries
•	Business KPI Calculations

💻 Technologies Used
•	MySQL
•	SQL Window Functions
•	Relational Database Concepts
•	Data Cleaning Techniques

📁 Project Structure
├── E-Commerce Code.sql
├── Insights.docx
├── README.md

🚀 How to Run the Project
1.	Import the datasets into MySQL.
2.	Create the database:
CREATE DATABASE cdj_ecommerce;
3.	Run the SQL script file.
4.	Execute analysis queries.
5.	Review generated insights.

📈 Learning Outcomes
Through this project, I learned:
•	Real-world SQL data analysis
•	Business-oriented querying
•	Data cleaning and validation
•	KPI analysis for e-commerce businesses
•	Advanced SQL window functions
•	Translating raw data into actionable insights

📌 Future Improvements
Possible enhancements:
•	Power BI dashboard integration
•	Python-based EDA
•	Predictive sales forecasting
•	Customer segmentation analysis
•	Inventory optimization modeling

👨‍💻 Author
Vivek
Aspiring Data Analyst passionate about SQL, Data Analytics, and Business Intelligence.
________________________________________
⭐ If you found this project useful
Please consider giving the repository a ⭐ on GitHub.

