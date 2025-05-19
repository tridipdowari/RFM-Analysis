# 🚗 Auto Sales Data Analytics Project

A complete end-to-end data analytics project to extract business insights from historical auto sales data. This project focuses on real-world data cleaning, exploration, visualization, and strategic reporting to support data-driven decision making.

---

## 📌 Table of Contents
- [Overview](#overview)
- [Objectives](#objectives)
- [Phases](#phases)
- [Key Visualizations](#key-visualizations)
- [Insights & Recommendations](#insights--recommendations)
- [Files Included](#files-included)
- [Technologies Used](#technologies-used)
- [Author](#author)

---

## 📊 Overview

This project analyzes a structured dataset containing thousands of auto sales transactions. It focuses on deriving meaningful business insights related to customers, products, geography, deal sizes, and time-based sales performance — with all findings supported by clean, clear visualizations.

---

## 🎯 Objectives

- Analyze monthly, geographic, and categorical sales performance
- Identify top customers and top-selling products
- Visualize patterns across countries and deal sizes
- Deliver data-driven business recommendations
- Present findings in a well-documented and visual format

---

## 🛠️ Phases

### ✅ **Phase 1: Data Understanding**
- Loaded and reviewed structure of `Auto Sales data.csv`
- Dataset had 2,747 rows and 20 columns
- Key features: `ORDERDATE`, `SALES`, `CUSTOMERNAME`, `PRODUCTCODE`, `COUNTRY`, `DEALSIZE`

---

### ✅ **Phase 2: Data Cleaning**
- Converted `ORDERDATE` to datetime
- Created new column: `YEAR_MONTH` for time series analysis
- Checked for missing values (none found)
- Ensured correct data types for analysis

---

### ✅ **Phase 3: Data Transformation**
- Grouped sales by:
  - `YEAR_MONTH` (monthly trends)
  - `CUSTOMERNAME` and `PRODUCTCODE` (ranking)
  - `COUNTRY` (regional insights)
- Created cumulative metrics (e.g., cumulative sales over time)
- Converted categorical columns into consistent formatting

---

### ✅ **Phase 4: Exploratory Data Analysis (EDA)**
- Used Seaborn and Matplotlib to visualize:
  - Monthly sales trends
  - Top 10 customers and products
  - Sales distribution across countries
  - Deal size breakdown

---

### ✅ **Phase 5: Summary Visualizations (Conclusion Focused)**
- Cumulative Sales Over Time
- Deal Size Distribution (Pie chart)
- Top 5 Countries by Sales
- Final visuals to support business conclusions

---

### ✅ **Phase 6: Dashboarding & Visualization**
Created a complete static dashboard using Seaborn/Matplotlib:

#### 📈 Monthly Sales Trend
Shows overall trend over time.
![Monthly Sales](assets/monthly_sales.png)

#### 🏆 Top 10 Customers by Total Sales
Highlights most valuable clients.
![Top Customers](assets/top_customers.png)

#### 📦 Top 10 Products by Total Sales
Displays best-selling products.
![Top Products](assets/top_products.png)

#### 🌍 Sales by Country
Breakdown of revenue by geography.
![Sales by Country](assets/sales_by_country.png)

#### 📊 Deal Size Distribution
Understanding the market segmentation.
![Deal Size](assets/deal_size.png)

---

### ✅ **Phase 7: Report & Documentation**
- Summarized full process from data collection to insights
- Provided visual evidence for conclusions
- Offered actionable business recommendations

---

## 📌 Key Insights & Recommendations

### 📍 Insights:
- Peak sales occurred in **[e.g., November 2004]**
- Customer **[e.g., Euro+ Shopping Channel]** contributed the most revenue
- Product **[e.g., S10_1949]** was the highest-selling item
- **USA** was the top contributing country
- Majority of deals were in the **Medium** size category

### ✅ Recommendations:
- Invest in customer loyalty programs for top clients
- Optimize inventory for high-selling products
- Expand in top-performing regions (e.g., USA, France, Australia)
- Upsell small-to-medium deal clients to larger packages

---

## 📁 Files Included

| File Name                  | Description                                |
|---------------------------|--------------------------------------------|
| `Auto Sales data.csv`     | Raw dataset                                |
| `auto_sales_analysis.ipynb` | Main analysis notebook (cleaned and visualized) |
| `auto_sales_dashboard.py` | (Optional) Streamlit dashboard script      |
| `README.md`               | Project summary and documentation          |
| `assets/` folder          | Exported charts (for GitHub/portfolio use) |

---

## 🧰 Technologies Used

- **Python 3.10+**
- **Pandas**
- **Matplotlib**
- **Seaborn**
- (Optional: Streamlit for interactive dashboards)
- Jupyter Notebook for development

---

## 🙋 Author

**Your Name**  
Data Analyst | Python & BI Enthusiast  
[GitHub Profile](https://github.com/yourusername)  
[LinkedIn Profile](https://linkedin.com/in/yourprofile)

---

