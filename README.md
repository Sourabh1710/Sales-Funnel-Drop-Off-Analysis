# 🛒 SQL Project : Sales Funnel Drop-Off Analysis

This project analyzes user behavior across an e-commerce sales funnel to uncover drop-offs at each stage, campaign performance, and conversion trends using SQL + Python + Visualizations.

---

## 📌 Project Objective

To identify:
- Where users drop off in the sales funnel
- Which traffic sources convert best
- How campaigns and cart behavior impact conversion
- Final conversion rates from Landing to Purchase

---

## 📂 Dataset

**Synthetic Funnel Dataset**  
- Structured into 4 tables: `landing_page_visits`, `product_page_views`, `add_to_cart`, and `purchases`
- Each record contains `user_id`, `timestamp`, and `campaign_id/source`

---

## 🧰 Tools & Technologies

| Tool            | Usage                          |
|------------------|-------------------------------|
| **Python (Pandas, SQLite)** | Data cleaning + SQL queries |
| **SQL (via SQLite)**         | Funnel analysis logic       |
| **Plotly & Seaborn**         | Visualization & storytelling |
| **Jupyter Notebook**         | Interactive analysis & documentation |

---

## 🧪 Analysis Steps

### 🔹 1. Database Setup
- Loaded `.csv` files into SQLite using Pandas
- Created 4 tables for each funnel stage

### 🔹 2. SQL Funnel Queries
- Total users at each stage
- Drop-off between stages
- Cart abandonment rate
- Campaign-level performance
- Source-wise conversion
- Users completing full funnel
- Repeated user sessions

### 🔹 3. Visual Insights
- 📊 Bar charts (Seaborn, Plotly)
- 📈 Line plot of purchases over time
- 🧩 Conversion comparison by source & campaign
- 🧠 Pie chart of users who completed full funnel

---

## 📊 Key Visuals

| Chart                                   | Description                                |
|----------------------------------------|--------------------------------------------|
| **Funnel Drop-Off (Bar)**              | User count per funnel stage                |
| **Cart Abandonment**                   | Split between purchasers and abandoners    |
| **Purchases Over Time**                | Line graph showing trend                   |
| **Conversion by Campaign**             | Horizontal bar of purchase rates           |
| **Top Duplicate Users**                | Repeated sessions for same user IDs        |
| **Funnel Completion Pie**              | Users who completed all 4 stages           |

📁 All images saved in `/charts` folder

---

## 📈 Sample Funnel Insights

- Only **40%** of users moved from landing to product page
- Cart abandon rate: ~30%
- Highest conversion rate came from `paid` traffic
- Only **15%** completed the full funnel journey

---



## ✅ Files

| File | Description |
|------|-------------|
| `Sales Funnel Drop-Off Analysis.ipynb` | Main analysis notebook |
| `/charts/` | Folder containing all saved `.png` visualizations |
| `README.md` | This documentation file |
| `datasets` | ![4 .csv files](https://github.com/Sourabh1710/Sales-Funnel-Drop-Off-Analysis) |

---

## 🧠 Skills Demonstrated

- SQL Joins, Aggregation, CTEs
- Funnel analysis logic
- Data storytelling
- Plotly charting
- Writing STAR-format project summaries

---

## Author

**Sourabh Sonker**
**Aspiring Data Scientist**

---

