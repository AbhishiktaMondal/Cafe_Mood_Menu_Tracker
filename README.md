# ☕ Cafe Mood Menu Tracker

## 📊 Project Overview

**Cafe Mood Menu Tracker** is a data analytics project that analyzes café sales performance and customer purchasing behavior based on **weather conditions, customer mood, and time of day**.

The project combines **PostgreSQL for SQL-based analysis** with **Power BI for interactive data visualization**, transforming raw café transaction data into meaningful business insights and actionable recommendations.

---

## 🎯 Business Objective

The objective of this project is to analyze café operations and answer key business questions such as:

- Which menu items generate the highest revenue?
- Which menu categories are most popular?
- Which weather conditions generate the highest revenue?
- Which products are most popular during rainy weather?
- Which customer moods are associated with higher spending?
- Which time of day has the highest average spending?
- Who are the highest-value customers?
- Which menu categories perform best under different weather conditions?
- What percentage of total revenue comes from each menu category?

---

## 🗂️ Dataset

The dataset contains **2,000 café order records** with information about:

- Order details
- Customer information
- Menu items and categories
- Quantity and revenue
- Date and time
- Payment methods
- Dine-in / Takeaway
- Weather conditions
- Customer mood

---

## 🔍 SQL Analysis

The project includes **30 business-focused SQL queries** covering different levels of analysis.

### Basic Analysis

- Total number of orders
- Total revenue
- Average order value
- Most ordered menu items
- Highest-performing menu categories
- Most frequently used payment methods

### Sales Analysis

- Top 5 menu items by revenue
- Highest-revenue weather condition
- Highest-revenue payment method
- Monthly sales performance
- Day of the week with the highest revenue

### Weather & Mood Analysis

- Most popular item during rainy weather
- Most common customer mood during rainy weather
- Highest average order value by weather
- Menu items preferred by Happy customers
- Best-performing menu category under each weather condition

### Time Analysis

- Most active ordering hour
- Morning vs Afternoon vs Evening spending
- Most popular categories during morning
- Most popular categories during evening

### Advanced SQL

- Top 10 customers by spending
- Top-selling item for each weather condition
- Ranking menu items by revenue within each category
- Revenue contribution percentage by menu category
- CTEs and Window Functions

---

## 📊 Power BI Dashboard

The Power BI dashboard provides an interactive overview of café sales and customer behavior.

### Key Performance Indicators

- 💰 Total Revenue — ₹966.57K
- 🧾 Total Orders — 2,000
- 🛒 Total Items Sold — 5,014
- 💳 Average Order Value — ₹483
- 👥 Unique Customers — 300

### Dashboard Visuals

- Revenue Trend Over Time
- Revenue by Menu Category
- Top 5 Best-Selling Items
- Revenue by Weather Condition
- Average Spending by Time of Day
- Top 10 Customers by Total Spending
- Top-Selling Categories by Weather
- Popular Categories by Time of Day

### Interactive Filters

- Weather
- Time of Day
- Date Range

---

## 📸 Dashboard Preview

![Cafe Mood Menu Tracker Dashboard](Dashboard/cafe_dashboard.png)

---

## 🔍 Key Findings

- The café generated **₹966.57K in total revenue** from **2,000 orders**.
- A total of **5,014 items** were sold across the analyzed dataset.
- The café had **300 unique customers**.
- The overall **Average Order Value was approximately ₹483**.
- **Sunny weather generated the highest revenue**, followed by Cloudy and Rainy conditions.
- **Coffee** was the largest revenue-contributing menu category, accounting for approximately **26.3% of category revenue**.
- **Pasta** was the top-selling individual item based on quantity sold.
- **Evening customers had the highest average spending** among the three major time periods.
- Menu preferences varied across different **weather conditions and time periods**, creating opportunities for targeted promotions.
- The **Top 10 customers** represent high-value customers who could be targeted through loyalty and personalized marketing strategies.

---

## 💡 Business Insights

The analysis provides insights that can help café management:

- Optimize menu offerings based on customer demand.
- Promote specific products during different weather conditions.
- Design time-based promotional campaigns.
- Identify and retain high-value customers.
- Understand customer purchasing behavior.
- Improve revenue contribution from lower-performing categories.
- Make data-driven decisions for menu planning and marketing.

---

## 🚀 Project Outcome

- Built a complete **SQL + Power BI analytics solution** for café business analysis.
- Developed **30 business-focused SQL queries** using aggregation, filtering, CASE statements, date/time functions, CTEs, and window functions.
- Created an interactive Power BI dashboard with **KPIs, trends, rankings, and comparative analysis**.
- Transformed raw transaction data into **actionable business insights**.
- Demonstrated how data analytics can support **menu planning, customer targeting, promotional strategies, and sales optimization**.

---

## 🎯 Problems Solved

- Analyzed overall café sales and revenue performance.
- Identified top-performing menu items and categories.
- Evaluated the impact of weather on customer purchasing behavior.
- Analyzed customer mood and its relationship with menu preferences.
- Compared customer spending across different times of day.
- Identified high-value customers based on total spending.
- Identified opportunities for targeted promotions and menu optimization.

---

## 🛠️ Skills & Technologies

### Data Analysis
- SQL
- PostgreSQL
- Data Aggregation
- Data Filtering
- Date & Time Analysis

### Advanced SQL
- GROUP BY
- CASE Statements
- CTEs
- Window Functions
- RANK()
- Percentage Calculations

### Data Visualization
- Power BI
- DAX
- Dashboard Design
- Data Storytelling
- Business Intelligence

---


## 👤 Author
Abhishikta Mondal
Aspiring Data Analyst
