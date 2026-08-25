# Vendor-Performance-Procurement-Analysis

# Vendor Performance & Inventory Analytics

## 📌 Project Overview

This project is an end-to-end **Data Analytics solution** designed to evaluate vendor performance, purchasing efficiency, sales contribution, inventory movement, and profitability.

The analysis combines **Python, SQL, SQLite, Pandas, NumPy, Seaborn, SciPy, Excel, and Power BI** to transform raw procurement, sales, inventory, pricing, and vendor invoice data into actionable business insights.

The primary objective was to answer:

> **Which vendors and products are driving sales and profitability, where is procurement risk concentrated, and where is working capital being locked in inventory?**

---

## 🎯 Business Objectives

The project focuses on the following business questions:

- Which vendors generate the highest sales?
- Which brands contribute the most revenue?
- How concentrated is procurement across vendors?
- Does bulk purchasing reduce unit purchase prices?
- Which vendors have low inventory turnover?
- How much capital is tied up in unsold inventory?
- Which low-sales products have relatively high margins?
- Are profit margins significantly different between high-sales and low-sales groups?
- Which areas should management prioritize for cost and inventory optimization?

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| **Python** | Data cleaning, EDA, feature engineering and statistical analysis |
| **Pandas** | Data manipulation and aggregation |
| **NumPy** | Numerical calculations |
| **Seaborn / Matplotlib** | Data visualization |
| **SciPy** | Statistical hypothesis testing |
| **SQL** | Data aggregation and transformation |
| **SQLite** | Data storage and querying |
| **Power BI** | Interactive dashboard and business reporting |
| **Excel** | Supporting analysis and data review |

---

## 📊 Dataset

The project uses six datasets covering different parts of the business:

1. `begin_inventory.csv` – Opening inventory data
2. `end_inventory.csv` – Closing inventory data
3. `purchases.csv` – Vendor purchase transactions
4. `purchase_prices.csv` – Product pricing and volume information
5. `sales.csv` – Sales transactions
6. `vendor_invoice.csv` – Vendor invoice and freight information

The datasets were consolidated into an analytical **Vendor + Brand level dataset containing 10,692 records**.

> **Note:** The raw CSV files are not included in this repository because the source data is very large and should not be unnecessarily committed to GitHub.

---

# 🔄 Project Workflow

```text
Raw CSV Data
      ↓
Data Ingestion
      ↓
SQLite Database
      ↓
SQL Aggregation & Joins
      ↓
Vendor-Brand Summary Dataset
      ↓
Data Cleaning
      ↓
Exploratory Data Analysis
      ↓
Feature Engineering
      ↓
Statistical Analysis
      ↓
Business Insights
      ↓
Power BI Dashboard
