# 🐦‍🔥 Delivery Performance Analytics

## 📌 Project Overview
This project analyzes food delivery operations using SQL, Python, Excel, and Power BI to uncover insights related to delivery performance, customer behavior, and operational efficiency.

The goal is to simulate a real-world data analytics workflow and provide actionable insights that can improve business decisions.

## 🎯 Objectives

* Analyze delivery time efficiency and delays

* Identify high-value customers (Pareto Analysis)

* Evaluate rider performance and waiting time

* Build interactive dashboards for business insights

* Apply data analytics + AI concepts in one project

## 🧠 Skills & Tools Used

🔹 Programming & Analysis

    Python (Pandas, NumPy)

    SQL (Joins, Aggregations, KPI queries)

🔹 Data Visualization

    Power BI (Interactive Dashboard)

    Excel (Formulas, KPI calculations)

🔹 Concepts Applied

    Data Cleaning & Preprocessing

    KPI Metrics (Delivery Time, Revenue, Ratings)

    Pareto Analysis (Top 20% Customers)

    Business Insight Generation

## 📂 Dataset Description
* orders → order details, revenue, delivery time, rider performance & waiting time
* customers → customer behavior & segmentation
* weather → external factors affecting delivery

## 📁 Project Structure

├── Analysis/  
├── Data/      
├── Dashboard/                   
├── notebooks/                             
└── README.md

## 🔄 Project Workflow
1️⃣ Data Collection

* Multiple datasets combined from different sources
* Includes orders, customers, delivery performance, and weather data

2️⃣ Data Cleaning & Preprocessing

* Handled missing and inconsistent values
* Converted time-related columns into proper formats
* Standardized column names and data types
* Removed duplicates and irrelevant records

3️⃣ Exploratory Data Analysis (EDA)

* Analyzed order distribution and revenue trends
* Studied delivery time patterns across different conditions
* Identified peak hours and demand fluctuations

📁 Notebook: [02_demand_analysis.ipynb](notebooks\02_demand_analysis.ipynb)

4️⃣ Operational Performance Analysis

* Compared food preparation time vs rider waiting time
* Identified delivery bottlenecks
* Calculated delay percentages

📁 Notebook: [03_operational_analysis.ipynb](notebooks\03_operational_analysis.ipynb)

5️⃣ Customer Behavior Analysis

* Calculated:
  - Total orders per customer
  - Average order value
  - Customer ratings
  - Performed Pareto Analysis (Top 20% customers)

📁 Notebook: [04_customer_analysis.ipynb](notebooks\04_customer_analysis.ipynb)

6️⃣ SQL Business Analysis

* Revenue aggregation
* Customer frequency analysis
* Delivery KPIs using SQL queries

📁 Notebook: [05_sql_business_analysis.ipynb](notebooks\05_sql_bussiness_analysis.ipynb)

7️⃣ Machine Learning (Basic AI Layer)

* Built a simple model to analyze:
* Delivery delay patterns
* Key influencing factors
* Feature selection from operational + weather data

📁 Notebook: [06_ML_analysis.ipynb](notebooks\06_ML_analysis.ipynb)

8️⃣ Weather Impact Analysis 🌦️

* Studied how weather affects:
* Delivery time
* Order volume
* Integrated external dataset for real-world simulation

📁 Notebook: [07_Weather_Impact_Analysis.ipynb](notebooks\07_Weather_Impact_Analysis.ipynb)

9️⃣ Dashboard Development (Power BI)

* Created interactive dashboard with:
* KPIs (Revenue, Orders, Delay %)
* Slicers (time, customer segment)
* Visual insights for decision-making

📁 Folder :[Dashboard/](Dashboard\Dashboard.pbix)

![Dashboard](dashboard\dashboard_main.png)
![Dashboard](dashboard\weather_impact_analysis.png)

## 📊 Key Insights

* 📉 High delivery delays during peak hours
* 💰 Top 20% customers contribute majority revenue
* ⏱️ Rider waiting time significantly impacts delivery speed
* ⭐ Better-rated orders correlate with faster delivery
* 🌡️ Delivery delay increases with tempreature
* 🌧️ Rainy conditions significantly increase delivery time and decrease revenue 
* 📉 Order volume drops during extreme weather

## 📌 Dashboard Features
* Interactive slicers (city, time, customer segment)
* KPI cards (Revenue, Orders, Delay %)
* Trend analysis charts
* Customer segmentation visualization

## 💡 About This Project

This project demonstrates:

* End-to-end data analytics workflow
* Business-focused problem solving
* Multi-tool expertise (Python + SQL + BI)
* Ability to generate actionable insights

### ⭐ Final Note

This is not just a visualization project — it reflects how data can be used to drive real business decisions. 

### 👨‍💻 Author
Pranay Shete