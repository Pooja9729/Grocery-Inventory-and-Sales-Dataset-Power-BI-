# Grocery-Inventory-and-Sales-Dataset-Power-BI-
📌 Project Overview

This project analyzes grocery sales and inventory data using Power BI to uncover sales trends, monitor stock levels, and identify products requiring reordering. The objective is to enable data-driven decision-making for retail operations through interactive dashboards and actionable insights.

🎯 Project Objectives
Analyze overall sales performance and revenue trends
Monitor inventory levels and stock availability
Identify low-stock and reorder-required products
Understand product-wise and category-wise demand
Optimize inventory to reduce stock-outs and overstocking
Track key business KPIs such as Revenue, Sales Quantity, Inventory Value
Support supplier planning and procurement decisions
🏬 Domain

Retail Analytics / Inventory Management
📊 Problem Statement

Grocery retailers often face challenges in monitoring sales performance and inventory levels due to fragmented data and lack of real-time insights. Poor visibility into product demand and stock status can result in stock shortages, excess inventory, and lost revenue.
This project transforms raw grocery sales and inventory data into interactive Power BI dashboards to:
Identify top- and low-performing products
Track inventory health and reorder requirements
Align stock levels with actual sales demand
📂 Data Source

Grocery Sales & Inventory Dataset (2024–2025)
Collected from Google Dataset Search and publicly available grocery inventory datasets
Stored and managed using Microsoft Excel (.xlsx)
🧾 Attribute Details

Key attributes included in the dataset:
Product ID, Product Name, Category
Supplier ID, Supplier Name
Stock Quantity, Reorder Level, Reorder Quantity
Unit Price, Total Stock Value, Reorder Cost
Sales Volume, Revenue, Profit Margin
Stock Level, Stock Action, Inventory Turnover Rate
Dates: Received Date, Last Order Date, Expiration Date
Warehouse Location, Status
Date

🛠️ Tools & Technologies

Microsoft Excel (.xlsx) – Data storage, cleaning, and preprocessing
Excel Functions – XLOOKUP/VLOOKUP, calculations, validation
Power BI Desktop – Data modeling, DAX, dashboards
Power Query – Data transformation and cleansing
🔄 Data Preprocessing & Integration
Data Collection:
Combined grocery sales and inventory data for the period 2024–2025

Data Cleaning (Excel):
Imported CSV files into Excel
Filled missing values and aligned columns
Standardized text formats
Created calculated columns using formulas
Applied consistent styling across all sheets

Data Cleaning (Power Query):
Standardized text formats
Split and renamed columns
Ensured consistent data types

Data Integration:
Appended cleaned datasets to create a unified dataset ready for analysis
🧠 Data Modeling & DAX
Data Modeling:
Created Grocery dimension tables
Established relationships with the main fact table using:
Product field for product-level analysis
Category field for category-level analysis

DAX Components

Calculated Columns:
Stock Level
Stock Action
Turnover Segment

Measures:
Total Revenue
Inventory Value
Low Stock Items
Reorder Required
Sales by Last Month
Product Count

Parameters:
Category Parameter
Status Parameter
Turnover Segment
Year
📈 Analysis & Visualizations
Analysis Performed:

Product-wise and category-wise sales analysis
Revenue and sales trend analysis (monthly & yearly)
Inventory health and reorder requirement analysis
Sales demand vs available stock comparison

Visualizations Created:
KPI Cards (Total Revenue, Quantity Sold, Orders)
Line Charts (Sales trends over time)
Bar & Column Charts (Product & category sales)
Tables & Matrix (Detailed inventory view)
Donut/Pie Charts (Category contribution)
Slicers (Date, Category, Product, Stock Status)


⭐ Project Highlights

Built an end-to-end Power BI solution for grocery sales and inventory analysis (2024–2025).
Consolidated and cleaned multi-source Excel datasets into a unified, analysis-ready model.
Designed an optimized star schema data model for efficient reporting.
Created interactive dashboards to track sales performance, inventory health, and reorder requirements.
Implemented DAX calculated columns, measures, and parameters for dynamic KPI analysis.
Identified top-performing products and categories driving the majority of revenue.
Highlighted low-stock and reorder-required items to reduce stock-out risk.
Detected slow-moving and overstocked products for inventory optimization.
Enabled time-based analysis (monthly, yearly trends) using date parameters.
Delivered actionable insights to support data-driven retail and inventory decisions.
<img width="1192" height="632" alt="Screenshot 2026-01-19 003922" src="https://github.com/user-attachments/assets/5beae331-dc55-44ad-a0e1-13cbc112f390" />
<img width="1214" height="613" alt="Screenshot 2026-01-19 003943" src="https://github.com/user-attachments/assets/873862ea-92b9-46c2-820c-7e9397b2ba76" />
🔍 Key Insights

A small group of products contributes to a large portion of total revenue
Certain categories consistently outperform others
Several high-demand products frequently fall into Low Stock / Reorder Needed status
Some products show overstocking with low sales, indicating slow-moving inventory
Clear seasonal and monthly sales patterns were observed

✅ Conclusion

This project successfully converts raw grocery sales and inventory data into a powerful Power BI reporting solution. The dashboards provide clear visibility into sales performance, inventory health, and reorder requirements, supporting effective inventory optimization and demand planning.

The project demonstrates strong skills in data preprocessing, data modeling, DAX, and dashboard design, making it a solid portfolio project for Data Analyst / Business Intelligence roles.
