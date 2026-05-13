# 🛒 EDA Superstore Sales Analysis

## 📌 Project Overview

This project focuses on performing an in-depth Exploratory Data Analysis (EDA) on the Superstore Sales dataset. The dataset contains customer orders, shipping details, product information, sales, discounts, and profits.

The objective of this project is to clean messy data, handle inconsistencies, perform feature engineering, identify business insights, and create meaningful visualizations.

This project demonstrates practical data analysis skills using Python and helps understand real-world retail business performance.

---

# 🎯 Objectives

- Perform data cleaning and preprocessing
- Handle missing values and duplicates
- Normalize and validate date columns
- Perform feature engineering
- Detect and remove outliers
- Analyze customer behavior and profitability
- Understand shipping and regional performance
- Create business insights using visualizations
- Build a reusable EDA workflow

---

# 🧰 Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

# 📂 Dataset Features

The dataset contains 21 columns including:

- Order Details
- Customer Information
- Shipping Details
- Product Information
- Sales and Profit Data

Key columns:

| Column Name | Description |
|---|---|
| Order ID | Unique order identifier |
| Order Date | Date of order |
| Ship Date | Shipping date |
| Sales Price | Final selling price |
| Quantity | Units sold |
| Discount | Applied discount |
| Profit | Profit per quantity |

---

# 🔍 EDA Process

## 1. Data Loading & Exploration

- Loaded dataset using Pandas
- Checked data types and missing values
- Explored unique values and summary statistics

## 2. Data Cleaning

- Removed duplicate rows
- Standardized date formats
- Corrected inconsistent Order IDs
- Converted incorrect data types
- Fixed state abbreviations
- Protected PII using customer name masking

## 3. Missing Value Imputation

- Imputed Ship Mode using Days to Ship
- Imputed Quantity using statistical methods

## 4. Feature Engineering

Created new features such as:

- Days to Ship
- Original Price
- Total Sales
- Total Profit
- Discount Price
- Total Discount
- Shipping Urgency
- Days Since Last Order

## 5. Outlier Detection

Implemented custom `remove_outliers()` function using the 3×IQR method.

## 6. Customer Segmentation

- Customer Sales Quintiles
- Customer Profit Quintiles
- Cross-tab analysis

## 7. Visualization & Insights

Created visualizations for:

- Top profitable products
- Loss-making products
- Sales vs Profit correlation
- Shipping analysis
- Regional profitability
- Temporal trends
- Discount impact

---

# 📊 Key Insights

- Technology category generated the highest profit
- Heavy discounts negatively affected profitability
- Standard Class was the most used shipping mode
- Some high-sales customers generated low profits
- Certain states consistently underperformed

---

# 📈 Sample Visualizations

- Bar Charts
- Scatter Plots
- Heatmaps
- Violin Plots
- Line Charts
- Joint Plots
- Pivot Tables

---

# 🚀 How to Run the Project

## Clone Repository

```bash
git clone https://github.com/your-username/EDA-Superstore-Sales-Analysis.git
