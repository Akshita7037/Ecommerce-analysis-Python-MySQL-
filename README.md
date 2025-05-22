# 🛒 E-commerce Data Analysis Project

This project demonstrates a full-stack data analysis workflow for an e-commerce business using Python, SQL (MySQL), and data visualization libraries such as Matplotlib and Seaborn. The project covers data ingestion, cleaning, querying, visualization, and advanced analytics to derive key business insights.

## 📦 Data Ingestion
All files were ingested into a **MySQL database (`ecommerce_db`)** using Python’s `pandas` and `SQLAlchemy`:
- Structured tables include:
  - customers
  - orders
  - order_items
  - products
  - sellers
  - payments
  - geolocation


## 🧾Data Analysis with SQL queries and Python visualizations

### 🔹 Basic Queries
1. Listed all unique cities where customers are located  
2. Counted the number of orders placed in 2017  
3. Calculated total sales per product category  
4. Calculated the percentage of orders paid in installments  
5. Counted the number of customers from each state  

### 🔸 Intermediate Queries
1. Counted number of orders per month in 2018  
2. Computed average number of products per order by customer city  
3. Calculated each product category’s contribution to total revenue  
4. Found correlation between product price and purchase frequency  
5. Ranked sellers by total revenue generated  

### 🔺 Advanced Queries
1. Calculated moving average of order values per customer  
2. Computed cumulative monthly sales for each year  
3. Measured year-over-year total sales growth  
4. Calculated customer retention rate (repeat purchases within 6 months)  
5. Identified top 3 highest-spending customers for each year  

---

## 📊 Visualizations
- Bar plots showing customer distribution by state  
- Monthly trend analysis of orders in 2018  
- Category-wise revenue share  
- Top seller revenue chart  
- Customer spending trend per year



## 🔧 Technologies Used

- **Python (pandas, numpy, matplotlib, seaborn)**
- **MySQL** (via PyMySQL and SQLAlchemy)
- **Jupyter Notebook**
- **Data Ingestion** with `pandas` and `SQLAlchemy`
- **Data Analysis** with SQL queries and Python visualizations

---

## 📚 Data Resources & Their Use
Download the Dataset from the below link.

Dataset Link-https://www.kaggle.com/datasets/devarajv88/target-dataset?select=products.csv.

The dataset comprises seven structured CSV, each representing a key component of an eCommerce business. These files were loaded into a MySQL database using Python and PyMySQL, then analyzed using SQL and Python (pandas, matplotlib, seaborn).
Structured CSV files include:
  - customers
  - orders
  - order_items
  - products
  - sellers
  - payments
  - geolocation


## 🎯 Goal
To build strong analytical skills by solving real business problems through SQL, Python, and data storytelling — preparing for a career in data analytics.
