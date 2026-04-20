# 🛍️ Brazilian E-Commerce: Customer Behavior & Sales Insights
### Exploratory Data Analysis | Python · Pandas · Matplotlib · Seaborn

---

## 📌 Project Overview

This project performs a full end-to-end Exploratory Data Analysis (EDA) on 100,000+ real transactions from **Olist**, Brazil's largest e-commerce marketplace (2016–2018).

The goal is to uncover actionable patterns in customer behavior, product performance, revenue distribution, and seasonality — skills directly applicable to Data Analyst and Data Scientist roles.

---

## 📂 Dataset

**Source:** [Brazilian E-Commerce Public Dataset by Olist — Kaggle](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

The dataset spans **9 relational CSV files** covering orders, customers, products, payments, reviews, sellers, and geolocation.

| File | Description |
|---|---|
| `olist_orders_dataset.csv` | Order status and timestamps |
| `olist_order_items_dataset.csv` | Items, prices, freight per order |
| `olist_customers_dataset.csv` | Customer location and IDs |
| `olist_products_dataset.csv` | Product metadata and categories |
| `olist_order_payments_dataset.csv` | Payment method and value |
| `olist_order_reviews_dataset.csv` | Customer review scores |
| `olist_sellers_dataset.csv` | Seller location |
| `olist_geolocation_dataset.csv` | ZIP code coordinates |
| `product_category_name_translation.csv` | Portuguese → English categories |

---

## 🔍 Analysis Sections

| # | Section | Focus |
|---|---|---|
| 1 | Data Loading | Merging all 9 CSVs into one master dataframe |
| 2 | Data Quality Check | Missing values heatmap, duplicates, summary |
| 3 | Data Cleaning | Datetime parsing, status filtering, category translation |
| 4 | Monthly Sales Trends | Revenue, order volume, average order value over time |
| 5 | Top Products & Categories | Revenue and order share by product category |
| 6 | Customer Segmentation | RFM analysis — Champions, Loyal, At Risk, Lost |
| 7 | Seasonality Patterns | Day-of-week, hour-of-day, monthly heatmap |
| 8 | Repeat vs New Customers | Retention rate, revenue split by customer type |
| 9 | Revenue Distribution | Pareto analysis — cumulative curve + decile breakdown |
| 10 | Geographic Analysis | State-wise revenue and order distribution |

---

## 💡 Key Business Insights

- 📈 **Revenue grew ~300% YoY** from 2017 to 2018, with a strong acceleration in Q1 2018
- 🔁 **Repeat purchase rate is only ~3–5%** — the platform's biggest retention gap
- 💰 **Top 10% of customers generate ~50%+ of total revenue** — Pareto principle confirmed
- 🗓️ **Peak buying time: Mondays, 10AM–2PM** — optimal window for promotions and campaigns
- 🗺️ **São Paulo (SP) accounts for ~40% of revenue** — top 3 states cover ~60% combined
- 🏷️ **Bed, Bath & Table + Health & Beauty** are the dominant revenue categories

---

## 🛠️ Tools & Libraries

```
Python 3.x
├── pandas        — data manipulation and merging
├── numpy         — numerical operations
├── matplotlib    — custom visualizations
├── seaborn       — statistical plots and heatmaps
└── jupyter       — interactive notebook environment
```

---

## 🚀 How to Run

```bash
# 1. Clone the repository
git clone https://github.com/yourusername/brazilian-ecommerce-eda.git

# 2. Install dependencies
pip install pandas numpy matplotlib seaborn jupyter

# 3. Download the dataset from Kaggle and place all CSVs in the project folder
# https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce

# 4. Launch Jupyter
jupyter notebook olist_eda.ipynb
```

> Update `DATA_DIR` in Cell 2 to the folder path where your CSVs are located.

---

## 📁 Project Structure

```
brazilian-ecommerce-eda/
│
├── olist_eda.ipynb        ← Main analysis notebook (with outputs)
├── README.md              ← This file
└── data/                  ← Place Kaggle CSVs here (not included in repo)
```

---

## 👤 Author

**Siddhant Sakharkar**  
B.Tech — Computer Science & Business Systems | Pune, India  
[LinkedIn](https://www.linkedin.com/in/yourprofile) · [GitHub](https://github.com/yourusername)

---

*Dataset credit: Olist Store and André Sionek via Kaggle (CC BY-NC-SA 4.0)*
