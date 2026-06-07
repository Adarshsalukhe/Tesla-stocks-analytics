# 📈 Tesla Stock Trend Analysis 2010 – 2026

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)

## 📌 Project Overview

An end-to-end Data Analytics project analyzing **3,920 trading days** of Tesla (TSLA) stock data spanning **16 years (2010–2026)**. This project covers the complete data analyst workflow — from raw data cleaning to SQL analysis to an interactive Power BI dashboard revealing key stock performance insights.

**Business Problem:** Analyze Tesla's stock journey from a $1.59 stock in 2010 to a $488 peak in 2024, identify volatility patterns, trading volume trends, and determine the best/worst periods for investors.

---

## 🔗 Live Dashboard

👉 [View Interactive Dashboard on Power BI](https://app.powerbi.com/groups/me/reports/37941d41-941a-49ba-983e-b69f57253dca/57b09f4380101ded650b?experience=power-bi)

---

## 📊 Dashboard Preview

### Page 1 — Tesla Stock Performance Overview
- KPI Cards: All Time High, All Time Low, Max Price Range, Avg Volatility
- All Time Price Trend (2010–2026)
- Yearly High vs Low
- Average Volume by Year
- Closing Price by Month

---

## 🗂️ Project Structure

```
Tesla-Stock-Analysis/
│
├── data/
│   ├── raw/
│   │   └── Tesla_stock_data.csv              # Original dataset
│   ├── cleaned/
│   │   └── Tesla_stock_data_new.csv          # Cleaned dataset
│   └── queries/
│       ├── query_monthly_summary.csv
│       ├── query_Yearly_summary.csv
│       ├── query_yearly_volatility.csv
│       └── query_volume_Yearly.csv
│
├── dashboard/
│   └── Tesla_Stock_Dashboard.pbix            # Power BI dashboard file
│
└── README.md
```

---

## 🔄 Project Workflow

```
Raw Dataset (Kaggle)
      ↓
Data Cleaning (Python + Pandas)
      ↓
SQL Analysis (SQLite)
      ↓
Power BI Dashboard
      ↓
Stock Performance Insights
```

---

## 🧹 Phase 1 — Data Cleaning

**Tool:** Python (Pandas)

### Issues Found & Fixed

| Issue | Fix Applied |
|---|---|
| Date column stored as string | Converted to datetime format |
| No Year/Month columns | Extracted from Date column |
| No Null values | Dataset was clean ✅ |
| No Duplicate rows | Dataset was clean ✅ |

### Dataset Overview

| Property | Detail |
|---|---|
| Total Rows | 3,920 trading days |
| Columns | Date, Open, High, Low, Close, Volume, Year, Month |
| Date Range | June 2010 – January 2026 |
| Null Values | None |
| Duplicates | None |

---

## 🗃️ Phase 2 — SQL Analysis

**Tool:** SQLite (via Python)

### Queries Written

| Query | Business Question |
|---|---|
| Monthly Summary | What is avg close, high, low and volume per month? |
| Yearly Summary | How did Tesla perform each year by month? |
| Yearly Volatility | Which years had highest price swings? |
| Yearly Volume | Which years had most trading activity? |

---

## 📈 Phase 3 — Key Insights

### 1. Tesla's Incredible Price Journey
- **2010:** Stock price was only **$1.59**
- **2020:** Explosive growth — price jumped from $28 to $239 in one year
- **2024:** Hit all time high of **$488.54**
- **Total growth:** ~30,000% from 2010 to 2024

### 2. Volatility Trends
- **2010–2019:** Near zero volatility (stock price under $30)
- **2020:** Volatility exploded — COVID-era trading frenzy
- **2021:** Highest volatility year — avg daily swing of $11
- **2025:** Most volatile year ever at avg swing of $16

### 3. Volume Analysis
- **2020** had the highest avg daily trading volume — **226M shares/day**
- Volume spiked during major events (COVID, earnings announcements, product launches)
- Post-2021 volume stabilized at ~90M shares/day

### 4. Best Month to Buy
- **December** historically has the highest avg closing price ($124)
- **May** historically has the lowest avg closing price ($86)
- Q4 (Oct–Dec) consistently outperforms Q1–Q2

### 5. Worst Years for Investors
- **2022** had the largest price range — $294 swing from high to low
- Stock dropped from $402 high to $108 low in 2022

---

## 📦 Dataset

- **Source:** Kaggle — Tesla Historical Stock Data
- **Records:** 3,920 trading days
- **Time Period:** June 2010 – January 2026
- **Features:** Date, Open, High, Low, Close, Volume

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| Python (Pandas) | Data cleaning & transformation |
| SQLite | SQL analysis & querying |
| Power BI Desktop | Dashboard & visualizations |
| Power BI Service | Publishing & sharing |
| Google Colab | Development environment |

---

## 📊 Dashboard Visuals

| Visual | Type | Insight |
|---|---|---|
| All Time Price Trend | Line Chart | Tesla's 16 year journey |
| Yearly High vs Low | Clustered Column | Best and worst years |
| Avg Volume by Year | Bar Chart | Trading activity trends |
| Closing by Month | Column Chart | Seasonal patterns |
| KPI Cards | Cards | Key metrics at a glance |

---

## 👤 Author

**Adarsh Anay Salukhe**
- GitHub: [@AdarshSalukhe](https://github.com/AdarshSalukhe)
- LinkedIn: [Connect with me](www.linkedin.com/in/adarsh-salukhe-a0a44221a)

---

## ⭐ If you found this project useful, please give it a star!
