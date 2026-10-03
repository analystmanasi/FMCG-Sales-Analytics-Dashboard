# 🛒 FMCG Sales Analytics Dashboard

An interactive Power BI dashboard to track FMCG primary and secondary sales, target achievement, and distribution performance across states, channels, and the sales team.

---

# 📌 Short Description / Purpose

The FMCG Sales Analytics Dashboard is a Power BI project that analyzes sales across categories, brands, SKUs, states, channels, and the sales hierarchy (RSM, ASM, SO).

It helps users track primary vs secondary sales, sell-through, target achievement, and year-over-year growth in one place. The project was built to practice real-world FMCG reporting and MIS-style dashboards.

---

# 🛠️ Tech Stack

- 📊 Power BI Desktop – Main platform used to build the dashboard.
- 📂 Power Query – Data cleaning, transformation, and preprocessing.
- 🧠 DAX (Data Analysis Expressions) – Measures for CY vs PY sales, growth %, target achievement %, sell-through, and % outlets billed.
- 🔗 Data Modeling – Relationships between sales, product, geography, distributor, and sales team tables.
- 📈 Data Visualization – KPI cards, line chart, donut charts, matrix, scatter plot, map, and decomposition tree.
- 📁 File Format – `.pbix` for the dashboard and `.pdf` / `.png` for previews.

---

# 📂 Data Source

The dataset contains FMCG sales information such as:

- Primary and secondary sales
- Categories, brands, and SKUs (4 categories, 10 brands, 18 SKUs)
- State, city, zone, and distributor details
- Sales hierarchy: RSM, ASM, and SO
- Sales channels (General Trade, Modern Trade, Wholesale, E-Commerce)
- Units sold, selling price, and sales targets
- Monthly data from Jan 2025 to Jun 2026

The dataset was used for practicing real-world business analysis and dashboard creation in Power BI.

---

# ✨ Features / Highlights

## 📌 Business Problem

FMCG companies sell through many distributors, channels, and regions. With raw data alone, it is hard to quickly see:

- Which categories and brands drive revenue
- Whether sales targets are being met
- How primary sales compare with secondary sales (sell-through)
- Which states, distributors, and sales managers perform best
- Which channels contribute most to secondary sales

Without clear reporting, tracking performance and taking action becomes slow.

---

## 🎯 Goal of the Dashboard

- Turn raw sales data into clear, actionable insights
- Track targets, growth, and sell-through at a glance
- Compare performance across category, brand, state, channel, and sales team
- Practice MIS reporting and dashboard storytelling in Power BI

---

# 📊 Walkthrough of Key Visuals

## 🔹 KPI Cards
Show key business metrics:
- Primary Sales (359M)
- Secondary Sales (404.34M)
- Sell-through (113%)
- Target Achieved % (96.72%)
- YoY % Growth (217.26%)
- % Outlets Billed (70.31%)
- SKUs, Units Sold, Avg Selling Price, Brands, Categories

---

## 🔹 Revenue Trend
Line chart comparing current year vs last year by month.
- Shows monthly growth
- Highlights peak and low months

---

## 🔹 Category and Brand Analysis
Matrix and donut charts show:
- CY Sales, PY Sales, Growth, and Target Achievement % by category, brand, and SKU
- Primary sales share by category (Foods leads at 37.03%)
- Top brands by primary sales (Tulsi Tea, Swaad Masala, Chatpata Namkeen)

---

## 🔹 Units Sold Trend
Column chart of units sold by month across 2025 and 2026.
- Helps spot seasonal demand and peak months

---

## 🔹 Price vs Volume Analysis
Scatter plot of avg selling price, units sold, and primary sales by SKU and brand.
- Helps compare low-price high-volume SKUs with high-price low-volume SKUs

---

## 🔹 Channel Performance
Donut chart of secondary sales by channel:
- General Trade (46.97%)
- Modern Trade (20.3%)
- Wholesale (16.74%)
- E-Commerce (15.99%)

---

## 🔹 State and Region Insights
- State-wise matrix with drill-down: State → City → ASM → SO
- Map showing revenue by region (East, North, West, South)

---

## 🔹 Sales Team Performance
- ASM-wise table with CY Sales, PY Sales, Growth, Secondary Sales, and Target Achievement %
- Bubble chart of primary sales vs YoY growth by ASM and RSM
- Decomposition tree to drill secondary sales by RSM → Zone → Distributor → ASM → SO

---

## 🔹 Interactive Filters & Slicers
Users can filter the dashboard by:
- Brand
- State
- Financial Year (FY)

---

# 📈 Business Impact & Insights

- 📊 Tracks primary and secondary sales and sell-through in one view
- 🎯 Shows target achievement (96.72%) by category, brand, and ASM
- 📍 Identifies top states, distributors, and sales managers
- 🛒 Shows which channels drive secondary sales
- 💡 Supports data-driven decisions for sales planning and distribution
- 🚀 Shows practical use of Power BI for FMCG and MIS reporting

---

# 🌱 What I Learned

- Building multi-page dashboards in Power BI
- Data cleaning and transformation with Power Query
- Writing DAX for growth %, target achievement %, and sell-through
- Designing drill-down views and decomposition trees
- Understanding FMCG metrics like primary vs secondary sales
- Data storytelling and business-focused reporting

---

# 📸 Dashboard Preview

![Dashboard Screenshot](https://github.com/analystmanasi/FMCG-Sales-Analytics-Dashboard/blob/main/FMCG%20Sales%20Dashboard.png?raw=true)
[![Dashboard Page 2](https://github.com/analystmanasi/FMCG-Sales-Analytics-Dashboard/blob/main/Screenshot%202026-10-03%20140259.png)
[![Dashboard Page 3](https://github.com/analystmanasi/FMCG-Sales-Analytics-Dashboard/blob/main/Screenshot%202026-10-03%20140317.png)


