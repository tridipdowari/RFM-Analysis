# 🚗 Auto Sales Data Analytics Project

A full-cycle business analytics project on automobile sales data. This project walks through understanding, cleaning, analyzing, and visualizing sales data to uncover key trends, customer behavior, and regional performance, concluding with clear business insights and visuals.

---

## 📌 Table of Contents
- [Overview](#overview)
- [Objectives](#objectives)
- [Project Phases](#project-phases)
- [Key Visuals](#key-visuals)
- [Insights & Recommendations](#insights--recommendations)
- [Project Files](#project-files)
- [Tools & Technologies](#tools--technologies)
- [Author](#author)

---

## 📊 Overview

This project explores and analyzes historical auto sales transactions from multiple countries. The analysis uncovers which customers, products, and regions drive the most revenue, and helps identify actionable patterns from the data through visual storytelling.

---

## 🎯 Objectives

- Understand and explore the structure of auto sales data
- Clean, preprocess, and transform the dataset for analysis
- Perform visual exploratory data analysis (EDA)
- Derive actionable business insights and dashboards
- Present key conclusions with summary visualizations

---

## 🛠️ Project Phases

### ✅ Phase 1: Data Understanding
- Loaded `Auto Sales data.csv` into Pandas
- Identified key features: `ORDERDATE`, `SALES`, `CUSTOMERNAME`, `PRODUCTCODE`, `COUNTRY`, `DEALSIZE`, etc.
- Analyzed row/column counts and data types
- Explored initial distributions and value counts

---

### ✅ Phase 2: Data Cleaning & Transformation
- Converted `ORDERDATE` to datetime format
- Extracted `YEAR`, `MONTH`, and created `YEAR_MONTH` for time-based analysis
- Checked and confirmed absence of missing/null values
- Converted numerical and categorical columns to appropriate types

---

### ✅ Phase 3: Exploratory Data Analysis (EDA)
- Analyzed:
  - Sales over time
  - Sales by customer
  - Sales by product
  - Sales by country
  - Sales by deal size
- Generated multiple charts using Seaborn & Matplotlib

---

### ✅ Phase 4: Business Insights & Dashboarding
- Identified top customers and top-selling products
- Highlighted highest revenue-generating countries
- Analyzed market share by deal size
- Created a visual dashboard combining core metrics

---

### ✅ Phase 5: Conclusion & Summary Visualizations
- Visualized cumulative sales to show growth over time
- Created final summary plots:
  - Monthly Sales Trend
  - Cumulative Revenue Chart
  - Pie Chart of Deal Sizes
  - Top 5 Countries by Revenue
- These charts support strategic business conclusions

---

## 📈 Key Visuals

| Visualization                      | Description                                     |
|-----------------------------------|-------------------------------------------------|
| 📊 Monthly Sales Trend            | Tracks revenue over time                        |
| 🏆 Top 10 Customers               | Highest contributing customers by total sales   |
| 📦 Top 10 Products                | Best-selling product codes                      |
| 🌍 Sales by Country               | Geographic performance breakdown                |
| 📌 Deal Size Pie Chart            | Market distribution by deal size category       |
| 📈 Cumulative Sales               | Growth in revenue over the entire time period   |

> All visuals are generated with `Matplotlib` and `Seaborn` using clean, readable formatting.

---

## 💡 Insights & Recommendations

### 🔍 Insights
- Sales peaked during [insert peak month/year]
- Customer **X** contributed the most revenue (~$Y)
- Product **Y** was the top seller in terms of total units/sales
- **USA**, **France**, and **Australia** were top-performing countries
- Majority of deals fall in the **Medium** size range

### ✅ Recommendations
- Prioritize large deals in high-performing regions
- Focus marketing on top customer segments
- Expand inventory for best-selling product categories
- Consider region-specific pricing strategies based on demand

---

## 📁 Project Files

| File                            | Description                                  |
|---------------------------------|----------------------------------------------|
| `Auto Sales data.csv`           | Raw data file                                |
| `auto_sales_analysis.ipynb`     | Main analysis and visualization notebook     |
| `README.md`                     | Project documentation                        |

---

## ⚙️ Tools & Technologies

- **Python** (Pandas, Matplotlib, Seaborn)
- **Jupyter Notebook**
- **CSV Files** for input

---

## 👤 Author

**Tridip Dowari**  
Data Analyst | Python Developer  
📧 tridipdowari75@gmail.com 
🔗 [GitHub](https://github.com/tridipdowari)
🔗 [LinkedIn](www.linkedin.com/in/tridipdowari)

---

