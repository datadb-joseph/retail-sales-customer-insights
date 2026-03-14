# 🛒 Retail Sales & Customer Insights Analysis

## Project Overview

This project simulates a consulting engagement where a business seeks actionable insights from its retail sales data. The primary goal is to **analyze customer behavior, product performance, and revenue trends** to inform strategic decisions.

As a **Data Analyst**, the project focuses on answering key business questions, generating recommendations, and providing a complete analytics workflow using SQL Server.

Key objectives include:

* **Customer Behavior Analysis** – Understanding demographics, purchase frequency, and high-value segments
* **Product Performance** – Evaluating top-performing and underperforming products
* **Customer Value Analysis** – Identifying the most valuable customers by revenue contribution
* **Customer Purchase Behavior** – Studying patterns and preferences
* **Category Dominance & Ranking** – Ranking product categories and top products by sales and quantity
* **Revenue Contribution Analysis** – Determining the contribution of customers and products to overall revenue

---

## Dataset

* **Source:** Kaggle and publicly available retail datasets
* **Format:** CSV (`retail_sales.csv`)
* **Number of Records:** 1,000 retail transactions
* **Columns:**

| Column           | Description                               |
| ---------------- | ----------------------------------------- |
| Transaction ID   | Unique identifier for each sale           |
| Date             | Date of transaction                       |
| Customer ID      | Unique customer identifier                |
| Gender           | Customer gender                           |
| Age              | Customer age                              |
| Product Category | Category of product purchased             |
| Quantity         | Number of units purchased                 |
| Price per Unit   | Price of a single unit                    |
| Total Amount     | Calculated as `Quantity × Price per Unit` |

---

## Tools & Technologies

* **SQL Server** – Used for all data storage, querying, and analysis
* **SQL Scripts (T-SQL)** – All analysis queries are written in Transact-SQL (T-SQL).
* **SQL Server Management Studio (SSMS)** – Used to write, run, and test SQL queries.
* **Excel / Power BI** – Optional for visualization of query results
* **GitHub** – Project organization and version control

---

## Project Contents

| File / Folder                       | Description                                                                             |
| ----------------------------------- | --------------------------------------------------------------------------------------- |
| `README.md`                         | Project overview, objectives, dataset description, business questions, recommendations  |
| `Dataset/retail_sales.csv`          | Raw dataset used for analysis                                                           |
| `SQL Scripts/`                      | Folder containing all SQL queries used to analyze business questions                    |
| `SQL Scripts/revenue_analysis.sql`  | Queries for revenue performance and contribution analysis                               |
| `SQL Scripts/customer_analysis.sql` | Queries for customer behavior, value, and demographics                                  |
| `SQL Scripts/product_analysis.sql`  | Queries for product performance, top-selling items, and category ranking                |
| `SQL Scripts/time_trends.sql`       | Queries for time-based sales trends (daily, weekly, monthly)                            |
| `Results/`                          | Folder containing exported query results (CSV or Excel) for reference and visualization |
| `Visualizations/`                   | Optional folder for charts, dashboards, or reports derived from query results           |

---

## Key Business Questions

**Customer Behavior Analysis**

* What is the distribution of customers by age and gender?
* Which customers are the most frequent buyers?
* How do purchasing habits vary across demographic segments?

**Product Performance**

* Which products and categories generate the highest revenue?
* Which products have the highest quantity sold?
* Are there underperforming products that need attention?

**Customer Value Analysis**

* Who are the top customers by total revenue contribution?
* What is the average revenue per customer segment?
* Which customer segments are most profitable?

**Customer Purchase Behavior**

* Are there patterns in product combinations purchased together?
* How does quantity per transaction vary across segments?
* What are the repeat purchase trends?

**Category Dominance & Ranking**

* Which product categories dominate total revenue?
* What are the top-ranked products in each category by revenue and quantity sold?

**Revenue Contribution Analysis**

* How much does each product or customer segment contribute to overall revenue?
* Which periods show the highest revenue contribution?

---

## Recommendations

Based on insights from the analysis, a business could consider:

* **High-Value Customer Retention:** Target top customers with loyalty programs or personalized offers.
* **Product Strategy:** Promote top-performing products and reassess low-performing items.
* **Category Optimization:** Focus marketing and inventory strategies on dominant categories.
* **Purchase Behavior Insights:** Use bundling or cross-selling strategies to maximize basket value.
* **Revenue Growth:** Plan seasonal campaigns based on peak sales periods and trends.

---

## How to Use This Project

1. **Load the Dataset** into SQL Server.
2. **Run the SQL Scripts** to analyze revenue, customers, products, and trends.
3. **Export Results** into CSV or Excel for visualization or reporting.
4. **Generate Insights** and recommendations to support business decisions.
