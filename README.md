# 📊 SQL Portfolio – Atliq Sales Analysis  

This repository contains my **SQL projects and practice work** based on the **Atliq Sales dataset**.  
It demonstrates real-world scenarios such as **sales performance, customer contribution, and forecast vs actual analysis** using **queries, views, functions, and stored procedures**.  

---

## 📂 Contents  

### 📑 Schema & Sample Data  
Scripts to create base tables such as:  
- `fact_sales_monthly`  
- `fact_forecast_monthly`  
- `dim_customer`  
- `dim_product`  

---

### 📦 Fact & Dimension Tables  
- **`fact_sales_monthly`** → Actual monthly sales (customers, products, markets, regions).  
- **`fact_forecast_monthly`** → Forecasted sales quantities.  
- **`dim_customer`, `dim_product`** → Master data for customers and products.  

---

### 👁 Views  
- **`gross_sales_view`** → Tracks gross sales before discounts.  
- **`net_sales_view`** → Calculates net sales after discounts.  
- **`discount_analysis_view`** → Summarizes discount trends by product and market.  

---

### ⚙️ Stored Procedures  
- **`sp_top_customers(year, n)`** → Returns top *n* customers by sales for a given year.  
- **`sp_top_products(year, n)`** → Finds best-performing products in terms of sales quantity or value.  
- **`sp_market_performance(year)`** → Summarizes sales by market and region.  

---

### 🧩 Functions  
- **`fn_fiscal_year(date)`** → Returns the fiscal year for a given date.  
- **`fn_fiscal_quarter(date)`** → Returns the fiscal quarter (Q1–Q4).  

---

### 📊 Analytical Queries  
- [**Customer Sales Share by Region**](https://github.com/Bharat-Dhankani/SQL-Business-Insights/blob/main/customer%20sales%20share%20within%20each%20region.sql) → Calculate each customer’s % contribution within their region using **CTEs + window functions**.  
- [**Actual vs Forecast Analysis**](https://github.com/Bharat-Dhankani/SQL-Business-Insights/blob/main/fact_actual_vs_forecast.sql) → Creates a combined fact table aligning actual sales with forecasted sales.  
- [**Top N Products**](https://github.com/Bharat-Dhankani/SQL-Business-Insights/blob/main/top_N_products_per_division.sql) → Finds the top N products per division using ranking functions.
- [**Forecast Accuracy by Customers**](https://github.com/Bharat-Dhankani/SQL-Business-Insights/blob/main/forecast_accuracy_by_customer.sql) → Evaluates forecast accuracy per customer using error metrics (absolute error, net error, % accuracy).

---

## 🔑 Highlights  
- Built **fact tables** combining actual and forecast sales for variance analysis.  
- Designed **views** for simplified reporting on gross, net, and discounted sales.  
- Created **stored procedures** to automate retrieval of business insights (top products, customers, market performance).  
- Developed **user-defined functions** for fiscal calculations.  
- Wrote **complex queries with CTEs + window functions** for advanced analytics.  

---

## 🛠 Tools & Technologies  
- **SQL Databases** → MySQL, SQL Server  
- **Clients** → SQL Workbench 
- **Dataset** → Atliq Sales (Direct,Retail & Distribution)  

---

## 📌 Author  
Created by **Bharat Dhankani**  
🔗 Connect with me on [LinkedIn](https://www.linkedin.com/in/bharat-dhankani-479441182/)  

