# Farmers-Market-Analytics-Project
Tools: SQL Server, Power BI
Skills: ETL, Data Cleaning, Data Modelling, KPI , Dashboard, EDA

📘Project Overview

This project analyzes a farmers market dataset to uncover insights about product demand, customer behavior, vendor performance, and geographic sales patterns.
I built a complete end-to-end BI solution using:

SQL Server for ETL: extracting, cleaning, transforming raw data
Star schema modelling for efficient analysis
Power BI dashboards for producing actionable business insights

The result is an interactive dashboard that helps stakeholders understand what products drive sales, which customers buy the most, and how performance varies across vendors and locations.

🎯 Objectives

Clean and structure raw market data using SQL Server
Create a star schema for analytical reporting
Build KPIs to measure market performance
Visualize trends in product demand, vendor contribution, and customer segments
Provide insights to support inventory planning, pricing, and promotional decisions

🛠️ Tech Stack

Languages: SQL
Tools: SQL Server, Power BI
Concepts: ETL, EDA, Fact–Dimension Modelling, KPI Design, Data Visualization

🧩 Data Pipeline (ETL Workflow)
1. Extract
          Imported raw CSV data into SQL Server
          Validated column types and formats

2. Transform
          Cleaned inconsistent values, duplicates, nulls
          Normalized product names and customer details
          Created calculated fields for revenue, quantity, product category
          Built views for product, vendor, customer analysis
          Designed Fact table + Dimension tables (Star Schema)

3. Load
         Loaded transformed datasets into Power BI
         Connected via SQL views for optimized queries

📊 Dashboard Features
1. Product Performance
                   Top-selling products by quantity
                   Product-wise revenue contribution
                   Demand distribution across categories

2. Customer Insights
                  High-value customers
                  Repeat purchasing patterns
                  Pareto analysis (20% customers driving majority of sales)

3. Vendor Analytics
                  Vendor-wise quantity contribution
                  Comparison among 7 vendors
                  Performance indicators

4. Geographic Insights
                  ZIP-code level demand visualization
                  Regional customer clusters

5. Market KPIs
                 Total Quantity Sold
                 Total Customers
                 Total Vendors

🔍 Key Insights
            Top 2 products account for majority market demand, indicating strong concentration.
            
            Customer-wise quantity distribution shows a clear Pareto pattern (a small segment buys most products). 
            
            Vendor performance is unequal, with a few vendors contributing significantly more.
            
            Certain ZIP codes show high recurring demand, revealing potential micro-marketing opportunities.
