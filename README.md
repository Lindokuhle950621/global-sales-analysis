# 📊 Global Sales Performance Analysis
### OptiCore Systems — Data Analytics Portfolio Project
**By Praisworth Lindokuhle Jonas**

![Dashboard Preview](images/dashboard-overview.png)

---

## 🧭 Project Overview

This is an end-to-end data analytics project that walks through the full analytics pipeline — from raw data and SQL queries, through data cleaning and modelling in Excel, all the way to an interactive dashboard and a formal business intelligence report.

The project simulates a real-world analytics engagement for a global retail business operating across 13 countries, 5 product categories, and 3 sales channels.

> **Data Source:** Publicly available sample dataset from [Kaggle](https://www.kaggle.com) (`real_world_sales_dataset_5000`). This project is for portfolio and demonstration purposes only. All analysis, findings, visualisations, and recommendations are original work by Praisworth Lindokuhle Jonas through OptiCore Systems.

---

## 🗂️ Repository Structure

```
global-sales-analysis/
│
├── README.md
├── sql/
│   └── SQL queries.sql            # Full SQL query package
├── excel/
│   └── Final Sales_Analysis.xlsx          # Full Excel workbook (5 sheets)
├── report/
│   └── Sales_Report_v3.docx      # Business Intelligence Report
└── images/
    ├── dashboard.png        # Full dashboard view
    └── dashboard.png        # Dashboard with active filters
```

---

## 📁 Excel Workbook — 5 Sheets

| Sheet | What It Contains |
|---|---|
| `SalesData (Raw)` | Original Kaggle dataset — 5,000 transactions, untouched |
| `SalesData (Cleaned)` | Cleaned and modelled data — formatted, typed, ready for analysis |
| `Pivot Tables` | Summaries by Country, Category, Channel, Product, and Month |
| `KPIs` | Headline metrics — Revenue, Profit, Margin, Orders, Customer Rating |
| `Dashboard` | Interactive dashboard with slicers and charts |

---

## 📈 Dashboard — What It Includes

**4 KPI Cards**
- Total Revenue · Total Profit · Total Orders · Profit Margin

**5 Interactive Slicers**
- Country · Order Date (monthly) · Payment Method · Product Category · Sales Channel

**5 Charts**
- Revenue by Country (bar chart)
- Revenue Trend by Month (line chart)
- Top 10 Products by Revenue (bar chart)
- Profit by Category (pie chart)
- Revenue vs. Profit by Category (bar chart)

![Dashboard Filtered View](images/dashboard-filtered.png)

---

## 🔍 Dataset at a Glance

| Attribute | Detail |
|---|---|
| Records | 5,000 transactions |
| Date Range | January 2023 – June 2025 |
| Markets | 13 countries |
| Sales Channels | Online, Retail Store, Mobile App |
| Product Categories | Electronics, Home & Living, Fashion, Beauty, Sports |
| Products | 19 individual products |
| Payment Methods | Credit Card, Bank Transfer, Debit Card, Cash on Delivery, PayPal |

---

## 💡 Key Findings

**1. Sales drop 42% in July and never recover**
The first half of the year (Jan–Jun) brings in 61% of all revenue ($15.3M). From July onwards, monthly revenue stays 40%+ below the January peak for the rest of the year. This is the biggest risk in the dataset.

**2. Three countries do almost half the work**
USA ($3.96M), India ($3.83M), and Pakistan ($3.78M) account for 46% of total revenue across 13 markets. Japan and Australia are the weakest markets despite being among the world's wealthiest consumer economies.

**3. Product portfolio is balanced but has no standout winner**
The Top 10 products all earn between $1.00M and $1.13M — a $130K spread. Sneakers (29.5%) and Tablet (29.2%) have the best profit margins but do not rank in the top 5 for revenue.

**4. Customer satisfaction is too low**
The average customer rating is 3.0 out of 5 across all channels. Customers at that score level are unlikely to return or recommend the business — a direct threat to long-term revenue.

---

## 🗃️ SQL Query Package

The `sql/sales_queries.sql` file covers:

- Table setup (CREATE TABLE, data types)
- Revenue and profit by country, category, channel, and product
- Monthly revenue trend analysis
- Top 10 products by revenue and margin
- H1 vs H2 revenue comparison
- Customer satisfaction analysis
- Payment method distribution
- Market classification (Top / Mid / Underperforming)

---

## 📄 Business Intelligence Report

The `report/OptiCore_Report_v3.docx` is a full client-style report that includes:

- Executive Summary with KPI snapshot
- About This Report (data source, scope, purpose)
- 5 Key Findings with data tables and insight callouts
- 5 Recommendations with specific targets and revenue estimates
- Final Thoughts with a 12-month growth projection ($2.5M–$3.7M)
- Appendix — full dataset and dashboard reference

---

## 🛠️ Tools Used

| Tool | How It Was Used |
|---|---|
| Microsoft Excel | Data cleaning, modelling, PivotTables, KPI formulas, Dashboard |
| SQL | Data exploration and aggregation queries |
| Microsoft Word | Business Intelligence Report |

---

## 👤 About

**Praisworth Lindokuhle Jonas**
Data Analyst | Founder, OptiCore Systems
📍 Hanover, Northern Cape, South Africa
🔗 [LinkedIn](https://www.linkedin.com/in/YOUR-LINKEDIN-HANDLE)
📧 your.email@example.com

---

*All analytical work, interpretations, visualisations, and recommendations in this project are original. Dataset sourced from Kaggle for demonstration purposes.*
