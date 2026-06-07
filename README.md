# 🛒 E-Commerce Sales Analysis Dashboard — Power BI

![Power BI](https://img.shields.io/badge/Tool-Power%20BI-F2C811?style=for-the-badge&logo=powerbi)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)

---

## 📌 Project Overview

This project transforms a raw Excel-based e-commerce dataset into a fully functional **E-Commerce Sales Analysis Dashboard in Power BI** — built end-to-end, from messy source data to polished, interactive business intelligence output.

E-commerce businesses generate high-volume, multi-dimensional sales data. Without proper analytics infrastructure, that data sits unused. This dashboard gives decision-makers instant visibility into **what's selling, where, when, and to whom** — and what's not.

---

## 🛠️ Tools & Techniques Used

| Tool / Feature | Purpose |
|---|---|
| Power BI Desktop | Primary development environment |
| Power Query (M language) | Data cleaning and transformation |
| DAX (Data Analysis Expressions) | Custom measures and calculated columns |
| Data Modeling | Table relationships and schema design |
| Interactive Visuals | Charts, maps, cards, slicers |
| Page Navigation | Multi-page report with button navigation |
| Bookmarks | Dynamic view switching |

---

## 🔢 How the Project Was Built

### Step 1 — Data Import & Assessment
Imported the raw Excel dataset into Power BI. Assessed the data structure for quality issues: inconsistent formats, blank rows, incorrect data types, merged cells from Excel.

### Step 2 — Data Cleaning in Power Query
Used Power Query to:
- Remove null and duplicate rows
- Standardize date formats for time intelligence functions
- Split combined columns (e.g., full name → first/last name)
- Trim whitespace and fix inconsistent category labels
- Promote headers and set correct column data types

### Step 3 — Data Modeling
Built a clean star schema:
- **Fact table** — sales transactions (order ID, revenue, quantity, date)
- **Dimension tables** — customers, products, geography, date table
- Defined relationships between tables with correct cardinality
- Created a dedicated Date Table for time intelligence support

### Step 4 — DAX Measures
Wrote custom DAX measures including:
- `Total Revenue`, `Total Orders`, `Average Order Value`
- `Revenue YTD`, `Revenue MoM %` (Month-over-Month growth)
- `Top Product by Revenue`, `Customer Count`
- Conditional measures for KPI card color indicators

### Step 5 — Dashboard Design & Navigation
Built a multi-page report:
- **Page 1 — Executive Summary**: KPI cards, revenue trend, top categories
- **Page 2 — Product Analysis**: Top/bottom performers, category breakdown
- **Page 3 — Geographic View**: Sales by region using map visual
- **Page 4 — Customer Insights**: Repeat vs. new customers, segment analysis
- Added button-based page navigation for smooth user experience

---

## 📊 What the Dashboard Tells Decision-Makers

| Business Question | Dashboard Answer |
|---|---|
| What is total revenue this month vs. last? | MoM revenue KPI card |
| Which product categories drive the most sales? | Category breakdown chart |
| Where are our highest-value customers located? | Geographic sales map |
| Which products are underperforming? | Bottom products visual |
| Is the business growing month over month? | Revenue trend line |
| What is the average order value? | AOV KPI measure |

---

## 💼 Real-World Applications

The analytical approach used here applies directly to:

- **Port revenue analytics** — cargo handling revenue by vessel type, berth, and period
- **Freight forwarding performance** — shipment volume and revenue by lane or client
- **Terminal operations reporting** — TEU throughput trends and operational KPIs
- **Logistics company sales tracking** — client account performance and growth monitoring
- **Any multi-product, multi-region business** needing consolidated sales visibility

---

## 📈 Decision-Making Value

This dashboard enables:
- **Faster decisions** — no more waiting for weekly manual reports
- **Product strategy** — identify which categories to scale and which to cut
- **Geographic expansion** — spot underserved high-potential regions
- **Pricing review** — AOV trends inform whether pricing adjustments are working
- **Inventory planning** — top product visibility supports stock replenishment decisions

---

## 🔍 What Could Be Improved

- **Forecasting layer** — add predictive sales forecast using Power BI's built-in AI visuals
- **Customer lifetime value (CLV)** — calculate long-term value per customer segment
- **Return/refund analysis** — include returns data to get net revenue accuracy
- **Live data connection** — replace static Excel source with SQL database or API feed
- **Mobile layout** — optimize report for Power BI mobile app viewing
- **RLS (Row-Level Security)** — restrict data visibility by regional manager

---

## 🎓 What I Learned

- The complete Power BI workflow: import → clean → model → measure → visualize
- Why a proper Date Table is non-negotiable for time intelligence in DAX
- How star schema modeling improves query performance and formula simplicity
- The difference between calculated columns and measures — and when to use each
- How navigation design affects whether a dashboard actually gets used

---



https://github.com/user-attachments/assets/f442e46f-e029-4e55-a250-97616b33992f
