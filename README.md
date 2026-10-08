# 🛒 Zepto Inventory & Pricing Analysis using PostgreSQL

## 📌 Project Overview

This project focuses on analyzing **Zepto e-commerce inventory data using PostgreSQL** to uncover insights related to product pricing, discounts, inventory availability, stock status, and product categories.

The project follows a practical **Data Analyst workflow**, including data exploration, data cleaning, SQL analysis, and business-focused insight generation.

The goal is to understand product-level and category-level patterns that can support better **pricing, inventory, and product management decisions**.

---

## 🎯 Business Objectives

The analysis aims to answer questions such as:

* Which product categories have the most products?
* Which products offer the highest discounts?
* Which products have the highest MRP?
* How many products are currently out of stock?
* Which categories offer the highest average discount?
* Which expensive products have low discounts?
* What is the estimated potential revenue by category?
* Which products provide better value based on price per gram?
* How does inventory weight vary across categories?

---

## 📊 Dataset

The dataset contains Zepto product inventory information, including product names, categories, pricing, discounts, stock availability, and product weights.

### Dataset Features

| Column                   | Description                   |
| ------------------------ | ----------------------------- |
| `sku_id`                 | Unique product/SKU identifier |
| `name`                   | Product name                  |
| `category`               | Product category              |
| `mrp`                    | Maximum Retail Price          |
| `discountPercent`        | Discount percentage           |
| `discountedSellingPrice` | Selling price after discount  |
| `availableQuantity`      | Available inventory quantity  |
| `weightInGms`            | Product weight in grams       |
| `outOfStock`             | Stock availability indicator  |
| `quantity`               | Product/package quantity      |

---

## 🛠️ Tools & Technologies

* **PostgreSQL**
* **SQL**
* **pgAdmin**
* **Microsoft Excel / CSV**

---

## 🔄 Project Workflow

### 1. Database & Table Creation

Created a PostgreSQL table with appropriate data types for the Zepto inventory dataset.

### 2. Data Import

Imported the CSV dataset into PostgreSQL using pgAdmin.

### 3. Data Exploration

Performed exploratory analysis to understand:

* Total number of products
* Product categories
* Product pricing
* Discount patterns
* Stock availability
* Duplicate product entries
* Missing values

### 4. Data Cleaning

Performed data cleaning to improve data quality, including:

* Checking for NULL values
* Identifying duplicate records
* Identifying invalid pricing values
* Handling zero-value MRP and selling prices
* Converting price values into a consistent format

### 5. SQL Analysis

Used PostgreSQL to perform business-oriented analysis using:

* `SELECT`
* `WHERE`
* `GROUP BY`
* `HAVING`
* `ORDER BY`
* `CASE WHEN`
* Aggregate functions
* Subqueries
* CTEs
* Window functions
* Ranking functions

---

## 📈 Key Analysis Performed

### 🏷️ Product & Category Analysis

* Identified categories with the highest number of products
* Analyzed product distribution across categories
* Identified duplicate product names across different SKUs

### 💰 Pricing & Discount Analysis

* Found products with the highest discount percentages
* Identified high-MRP products
* Analyzed average discounts by category
* Identified expensive products with relatively low discounts
* Calculated price per gram for selected products

### 📦 Inventory Analysis

* Compared in-stock and out-of-stock products
* Identified high-value products that are out of stock
* Analyzed inventory quantity across categories
* Calculated total inventory weight by category

### 💵 Revenue Analysis

* Estimated potential revenue at the product/category level
* Compared revenue potential across different product categories

---

## 🔍 SQL Concepts Demonstrated

This project demonstrates practical knowledge of:

```text
Data Exploration
Data Cleaning
Filtering
Aggregation
GROUP BY
HAVING
CASE Statements
Subqueries
CTEs
Window Functions
Ranking
Business Analysis
```

---

## 📂 Project Structure

```text
zepto-inventory-analysis-postgresql/
│
├── data/
│   └── zepto_v2.csv
│
├── sql/
│   └── zepto_inventory_analysis.sql
│
├── screenshots/
│   └── dashboard.png
│
└── README.md
```

---

## 🚀 How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/zepto-inventory-analysis-postgresql.git
```

### 2. Open PostgreSQL / pgAdmin

Create a new database and connect to it.

### 3. Create the table

Run the table creation query from:

```text
sql/zepto_inventory_analysis.sql
```

### 4. Import the dataset

Import:

```text
data/zepto_v2.csv
```

into the PostgreSQL table.

### 5. Run the SQL queries

Execute the analysis queries to reproduce the results and insights.

---

## 📊 Dashboard

A Power BI dashboard can be created using the PostgreSQL analysis results to visualize:

* Total Products
* In-Stock Products
* Out-of-Stock Products
* Average Discount
* Category-wise Product Count
* Category-wise Pricing
* Discount Distribution
* Inventory Analysis

Dashboard screenshots will be added to this repository.

---

## 💡 Business Insights

The analysis helps understand:

* Product and category distribution
* Pricing and discount strategies
* Inventory availability
* High-value products
* Potential revenue opportunities
* Products that may require inventory attention

These insights can help e-commerce businesses make better **pricing, inventory, and product management decisions**.

---

## 🎓 Skills Demonstrated

**Technical Skills:**

`SQL` `PostgreSQL` `Data Cleaning` `Data Analysis` `Data Visualization` `Power BI`

**Analytical Skills:**

`Exploratory Data Analysis` `Business Analysis` `Problem Solving` `Data Interpretation`

---

## 👩‍💻 About Me

**Lahari Rongali**

B.Tech in Artificial Intelligence & Machine Learning
Interested in **Data Analyst,  AI/ML, and Python-related roles**.
I enjoy working with data to identify patterns, generate insights, and solve real-world business problems.

