# zepto_inventory_SQL_Analysis
SQL-based analysis of Zepto's product catalog covering pricing, stock availability, discounts and customer savings using PostgreSQL
# 🛒 Zepto Product & Inventory Analysis

## 📌 Project Overview
This project performs an end-to-end SQL analysis of Zepto's product catalog.
It covers data exploration, data cleaning, and answers 10 key business questions
related to pricing, stock availability, discounts, and customer savings.

---

## 🛠️ Tools Used
- PostgreSQL
- Excel (for raw dataset)

---

## 📁 Dataset
| Column | Description |
|---|---|
| category | Product category/department |
| name | Product name |
| mrp | Original price (in rupees) |
| discountpercent | Discount percentage |
| discountedsellingprice | Final price after discount |
| outOfStock | Whether product is available |
| availablequantity | Quantity available |
| weightingms | Product weight |
| quantity | Quantity details |

---

## 📂 Project Structure
```
zepto-sql-analysis/
│
├── zepto_analysis.sql    -- All SQL queries (exploration, cleaning, analysis)
├── README.md             -- Project documentation
└── dataset/
    └── zepto_data.xlsx   -- Raw dataset
```

---

## 🔍 Project Sections

### 1. Data Exploration
- Viewing sample data
- Counting total records
- Checking categories
- Stock vs out of stock count

### 2. Data Cleaning
- Null value check
- Duplicate detection
- Removing invalid/unrealistic data
- Converting prices from paisa to rupees

### 3. Business Analysis (10 Questions)

| # | Question |
|---|---|
| Q1 | Which products give customers the best deals? |
| Q2 | Which products are currently unavailable? |
| Q3 | Which category has the most products? |
| Q4 | What is the price range in each category? |
| Q5 | How much are customers saving per product? |
| Q6 | Which category has the worst stock problem? |
| Q7 | Which products have mid-range discounts? |
| Q8 | Which category holds the most inventory value? |
| Q9 | Which categories are critically understocked? |
| Q10 | Top discounted products within each category? |

---

## 💡 Key SQL Concepts Used
- Aggregate functions: `COUNT`, `SUM`, `AVG`, `MIN`, `MAX`
- Filtering: `WHERE`, `HAVING`
- Grouping: `GROUP BY`
- Window functions: `DENSE_RANK()`, `RANK()`, `PARTITION BY`
- CTEs: `WITH ... AS`
- Data manipulation: `UPDATE`, `DELETE`
- Null safety: `NULLIF()`
- Type casting: `::numeric`

---

## 👤 Author
Mehwish Nisha Khan  
www.linkedin.com/in/mehwish-nisha-khan-056509279 | [GitHub](https://github.com/mehwishkh09)
