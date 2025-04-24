# ecommerce_data_SQL_Analysis
ecommerce_data_SQL_Analysis
# 🛍️ Task 3: E-Commerce Data Analysis | Elevate Labs Internship

**Intern:** Nikhil Kumar Nigam  
**Platform Used:** Google BigQuery  
**Dataset:** E-Commerce Data from Kaggle  
**Tools:** SQL (BigQuery Standard SQL)  

---

## 📌 Project Overview

This project is part of my data analyst internship at **Elevate Labs**, where I analyzed an e-commerce dataset from Kaggle using **BigQuery**. The goal was to perform SQL-based exploratory data analysis (EDA), uncover key business insights, and improve SQL proficiency by working with real-world transactional data.

---

## 📊 Dataset Description

The dataset contains **over 540,000 transactions** from a UK-based online retailer.  
Each record includes:

- **InvoiceNo** – Unique transaction ID  
- **StockCode** – Product identifier  
- **Description** – Product name  
- **Quantity** – Units purchased  
- **InvoiceDate** – Date and time of purchase  
- **UnitPrice** – Price per unit  
- **CustomerID** – Unique customer identifier  
- **Country** – Country of purchase

---

## 🔍 Key SQL Tasks & Insights

| # | Task | SQL Description | Key Insight |
|--|------|------------------|-------------|
| 1 | Total Revenue | SUM(Quantity × UnitPrice) | Snapshot of overall earnings |
| 2 | Top 10 Products | GROUP BY Description + SUM(Quantity) | Identified best-selling items |
| 3 | Monthly Trend | FORMAT_TIMESTAMP by month | Revealed sales peaks in Nov-Dec |
| 4 | Top Customers | GROUP BY CustomerID + SUM(Revenue) | Highlighted high-value customers |
| 5 | Revenue by Country | GROUP BY Country | UK leads revenue, EU potential |
| 6 | Peak Days | GROUP BY Day of Week | Orders peak mid-week |
| 7 | Sales by Hour | EXTRACT(HOUR) | Most orders placed between 9 AM–3 PM |

---

## ✅ Skills Demonstrated

- Data importing and schema setup in BigQuery  
- Writing and optimizing SQL queries  
- Using **GROUP BY**, **AGGREGATE FUNCTIONS**,
- Time-based trend analysis using `FORMAT_TIMESTAMP` and `EXTRACT`  
- Drawing actionable business insights from raw transactional data  
