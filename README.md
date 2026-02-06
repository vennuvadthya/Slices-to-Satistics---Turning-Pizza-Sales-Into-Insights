# 🍕 Pizza Sales Data Analysis | SQL & Power BI

## 📌 Project Overview
This project is an **end-to-end data analytics case study** on pizza sales data.  
The objective was to analyze sales performance, customer ordering behavior, and product trends using **SQL for data analysis** and **Power BI for visualization**.

The project demonstrates the complete data analyst workflow:
- Data cleaning and transformation
- KPI calculation using SQL
- Interactive dashboard creation
- Business insights and recommendations


## 🛠️ Tools & Technologies Used
- **SQL Server** – Data querying and analysis  
- **Power BI Desktop** – Data modeling and dashboard development  
- **Power Query** – Data cleaning and transformation  
- **Microsoft Excel** – Dataset understanding  
- **GitHub** – Version control and project documentation  


## 📂 Dataset Information
- **Time Period:** January 2015 – December 2015  
- **Data Type:** Transaction-level sales data  
- **Key Columns:**  
  - order_id  
  - order_date, order_time  
  - pizza_name, pizza_category, pizza_size  
  - quantity, total_price  


## 📊 Key KPIs (Calculated using SQL)

| KPI | Value |
|---|---|
| **Total Revenue** | **$817.86K** |
| **Total Orders** | **21,350** |
| **Total Pizzas Sold** | **49,574** |
| **Average Order Value** | **$38.31** |
| **Avg Pizzas per Order** | **2.32** |


## 📈 Power BI Dashboard Features
The interactive Power BI dashboard provides insights into:

- 📅 Daily and monthly sales trends  
- 🍕 Top and bottom selling pizzas  
- 📦 Sales distribution by pizza category and pizza size  
- ⏰ Busiest days and peak ordering times  
- 💰 Revenue contribution analysis  

**Dashboard Pages:**
- **Home:** Overall performance and trends  
- **Best/Worst Seller:** Product-level analysis  


## 🔍 SQL Analysis Performed
The SQL analysis includes:

### ✔ KPI Analysis
- Total revenue  
- Average order value  
- Total orders and total pizzas sold  
- Average pizzas per order  

### ✔ Trend Analysis
- Daily trend for total orders  
- Monthly trend for total orders  

### ✔ Product Performance
- Top 5 and Bottom 5 pizzas by:
  - Revenue  
  - Quantity sold  
  - Total orders  

### ✔ Category & Size Analysis
- Percentage of sales by pizza category  
- Percentage of sales by pizza size  

All SQL queries are available in the **sql/** folder.


## 💡 Key Business Insights
- 📈 Orders are highest on **Fridays and Saturdays**, especially during evenings.  
- 🍕 **Classic Deluxe Pizza** is the top performer in terms of revenue, quantity, and total orders.  
- 📦 **Large size pizzas** contribute the maximum revenue (~46%).  
- 📉 Some pizzas consistently perform poorly and can be reviewed for pricing, promotion, or removal.  
- 📆 **July and January** record peak monthly demand.  


## 🗂️ Project Structure
pizza-sales-data-analysis/
│
├── data/ # Raw dataset
├── sql/ # SQL queries
├── powerbi/ # Power BI report (.pbix)
├── screenshots/ # Dashboard images
├── insights/ # Business insights
└── README.md # Project documentation


## 🚀 How to Use This Project
1. Load the dataset into **SQL Server**  
2. Execute SQL queries from the `sql/` folder  
3. Open the Power BI report from the `powerbi/` folder  
4. Explore the dashboard and insights  

## 🎯 What This Project Demonstrates
- Strong SQL fundamentals  
- Data cleaning and transformation skills  
- Interactive Power BI dashboard design  
- Ability to convert data into business insights  
- End-to-end Data Analyst workflow

  
## 👤 Author
**V Vennela**  
Aspiring Data Analyst  
📊 SQL  | Power BI | Data Analysis
