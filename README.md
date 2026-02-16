📊 Customer Behavior Analysis
📌 Overview

This project focuses on analyzing customer purchasing behavior to uncover patterns, segment customers, and evaluate the impact of discounts on sales.

The analysis was performed using Python for data cleaning and EDA, MySQL for structured querying, and Power BI for building an interactive dashboard and business report.

The objective of this project is to demonstrate end-to-end data analytics workflow from raw dataset to business insights.

📂 Dataset

The dataset contains customer-level transactional data including:

Customer ID

Product purchased

Previous purchase count

Discount applied (Yes/No)

Purchase amount

Category and other attributes

The dataset is processed and structured for analysis using Python and MySQL.

🛠 Tools & Technologies Used

Python (Pandas, NumPy) – Data cleaning & EDA

MySQL – Data storage & SQL analysis

SQL – Aggregations, CASE statements, CTEs

Power BI – Interactive dashboard & reporting

SQLAlchemy – Connecting Python to MySQL

🔄 Project Workflow
1️⃣ Data Loading & Cleaning (Python)

Loaded dataset using Pandas

Handled missing values

Checked duplicates

Standardized column formats

Prepared dataset for SQL upload

2️⃣ Exploratory Data Analysis (EDA)

Purchase distribution analysis

Discount impact analysis

Customer segmentation logic

Aggregation & grouping analysis

3️⃣ SQL Analysis (MySQL)

Created structured database

Loaded cleaned dataset into MySQL

Ran analytical queries using:

GROUP BY

CASE statements

CTE (Common Table Expressions)

Aggregations & percentage calculations

4️⃣ Power BI Dashboard

Connected MySQL to Power BI

Built interactive dashboard including:

Customer segmentation

Discount rate analysis

Top products analysis

Purchase trends

5️⃣ Business Report

Generated insights report summarizing:

Customer types (New, Returning, Loyal)

Discount effectiveness

High-performing product categories

Strategic recommendations

📈 Dashboard Highlights

Customer segmentation breakdown

Top 5 products by discount rate

Revenue insights

Purchase frequency distribution

Interactive filters & slicers

📊 Key Results

Identified high-discount dependency products

Segmented customers into actionable categories

Measured discount impact on purchase behavior

Built a business-ready interactive dashboard

▶ How to Run This Project
Step 1: Clone Repository
git clone <repository-link>

Step 2: Install Required Python Libraries
pip install pandas numpy sqlalchemy pymysql

Step 3: Set Up MySQL Database

Create database in MySQL

Update connection credentials in the script

Step 4: Run Python Script

Clean data

Upload dataset to MySQL

Step 5: Open Power BI File

Connect to MySQL server

Refresh data

Explore dashboard
