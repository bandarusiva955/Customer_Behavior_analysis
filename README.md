📊 Customer Behavior Analytics (SQL + Python + Power BI)
📌 Project Overview

This project analyzes customer purchasing behavior to identify high-value customer segments and sales patterns using SQL and Python.
Key performance indicators (KPIs) such as total revenue, average order value, and purchase frequency were calculated and visualized using Power BI dashboards to support business decision-making.

🎯 Business Problem

Businesses need to understand:
Which customers contribute most to revenue
What purchasing patterns exist
How often customers return
Which products drive sales
The goal of this project is to use historical transaction data to:
Segment customers based on purchasing behavior
Identify high-value customers
Discover sales trends and patterns
Provide insights that can help improve marketing and retention strategies

🗂 Dataset

Source: Public customer transaction dataset
Records: Customer ID, Product, Quantity, Price, Date
Size: (rows is (3900), columns is (18))
Data Issues: Missing values, inconsistent date formats, duplicates

🔧 Tools & Technologies

SQL (MySQL) – Data querying, aggregation, KPI calculation
Python (Pandas, NumPy, Matplotlib, Seaborn) – Data cleaning and EDA
Power BI – Interactive dashboard and visualization
GitHub – Version control and project documentation

🔄 Project Workflow
1️⃣ Data Cleaning

Removed duplicate records
Handled missing values
Converted date columns into proper datetime format
Standardized categorical values

2️⃣ SQL Analysis

Calculated key KPIs:
Total Revenue
Average Order Value (AOV)
Purchase Frequency
Grouped customers based on total spend
Identified top-performing products and customers

3️⃣ Python Exploratory Data Analysis (EDA)

Analyzed revenue trends
Visualized customer segmentation
Identified product-wise sales patterns
Checked distribution of order values

4️⃣ Power BI Dashboard

The dashboard includes:
Revenue trends over time
Top customers and products
Customer segmentation
Sales pattern visualizations

📊 Key Insights

A small percentage of customers contribute a large portion of total revenue
Certain product categories generate consistently higher sales
Repeat customers have significantly higher average order value
Sales show noticeable seasonal patterns

💡 Business Recommendations

Focus marketing campaigns on high-value customer segments
Promote top-performing products more aggressively
Design loyalty programs for repeat customers
Plan inventory based on seasonal demand trends

📁 Project Structure
Customer_Behavior_analysis
│
├── data
│   ├── raw_data.csv
│   └── cleaned_data.csv
│
├── sql
│   └── analysis_queries.sql
│
├── notebooks
│   └── eda.ipynb
│
├── powerbi
│   └── dashboard.pbix
│
└── README.md

🚀 How to Run the Project

Clone the repository
Open the Python notebook and run the data cleaning and EDA
Load the cleaned data into MySQL
Execute the SQL queries
Open the Power BI file and connect it to the cleaned dataset

📌 Resume Description

Customer Behavior Analytics (SQL + Python + Power BI)
Analyzed customer purchasing behavior using SQL and Python to identify high-value segments and sales patterns.
Built KPIs and visualized insights using Power BI dashboards to support business decision-making.

📝 Notes

This project demonstrates:
End-to-end data analytics workflow
Business-focused problem solving
SQL + Python + visualization skills
Clear communication of insights


