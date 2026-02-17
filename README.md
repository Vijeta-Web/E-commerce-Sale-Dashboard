# 📊 E-Commerce Sales Performance Dashboard

## 📌 Project Overview
This project focuses on building an interactive Sales Dashboard for a US-based E-Commerce company to analyze Year-to-Date (YTD) performance and generate actionable business insights.

The solution was developed using Excel, PostgreSQL, and Power BI, following an end-to-end data analysis workflow.

---

## 🎯 Problem Statement
The objective was to create a Sales Dashboard that provides:

- YTD Sales, YTD Profit, YTD Quantity Sold, and YTD Profit Margin
- Year-over-Year (YoY) growth comparison for each KPI
- Monthly sales trend using sparklines
- Sales performance by Category and Customer Segment
- Top 5 and Bottom 5 Products by Sales
- YTD Sales by Region and State
- Shipping Type performance analysis

---

## 🛠 Tools & Technologies Used

- **Excel** – Data cleaning and initial transformation  
- **PostgreSQL** – Database creation and structured data storage  
- **Power BI** – Data modeling, DAX calculations, and dashboard development  

---

## 🔄 Project Workflow

### 1️⃣ Data Cleaning (Excel & Power Query)
- Handled missing values  
- Standardized date formats  
- Removed duplicates  
- Ensured data consistency before database import  

### 2️⃣ Database Setup (PostgreSQL)
- Created database and defined table schema  
- Assigned appropriate data types  
- Imported structured data into PostgreSQL  

### 3️⃣ Data Modeling (Power BI)
- Built relational data model with 3 tables  
- Created custom Date table  
- Implemented Star Schema approach  

### 4️⃣ DAX & Time Intelligence
- Created measures for:
  - YTD Sales
  - YTD Profit
  - YTD Quantity
  - Profit Margin
- Implemented Time Intelligence functions:
  - TOTALYTD
  - SAMEPERIODLASTYEAR
- Calculated YoY growth percentage
- Used DAX functions like:
  - CALCULATE
  - SUMX
  - FILTER
  - DIVIDE
  - VAR

---

## 📈 Dashboard Features

- KPI Cards with dynamic YoY indicators  
- Monthly trend sparklines  
- Category-wise performance comparison  
- Region-wise sales distribution  
- Top & Bottom product analysis  
- Shipping mode contribution analysis  
- Interactive filters for customer segments  

---

## 📊 Key Insights

- Identified highest contributing region to overall sales  
- Detected declining categories using YoY comparison  
- Highlighted top-performing and underperforming products  
- Analyzed shipping method distribution trends  

---

## 🚀 Business Impact

This dashboard enables management to:
- Monitor real-time performance  
- Identify growth opportunities  
- Detect underperforming segments  
- Make data-driven decisions  

---

## 📌 Future Improvements

- Implement advanced SQL queries for deeper analysis  
- Add drill-through pages for detailed state-level insights  
- Optimize data model for scalability  
