# 📊 Regional Sales Analysis

A data-driven project that uncovers key insights from five years of sales data across U.S. regions. This project leverages exploratory data analysis (EDA) and an interactive Power BI dashboard to support strategic decision-making for marketing, sales, and operations teams.

---

## 📌 Problem Statement

Businesses face inconsistent revenue and profit performance across U.S. regions with limited visibility into:

- Seasonal sales swings
- Top-performing SKUs
- Channel profitability

> **Objective**: Identify growth levers and optimize sales strategy using 5 years of historical sales data.

---

## 🔍 Business Question

How can we empower sales teams with clear, data-backed insights into regional performance to identify high-growth opportunities and optimize resource allocation?

---

## 🧭 Approach

### Phase 1 – Exploratory Data Analysis (EDA)
- Cleaned and merged multiple unlinked tables: Sales, Products, Customers, Regions, States, and Budgets
- Engineered features such as `profit` and `profit_margin_pct`
- Visualized monthly trends, product performance, customer segmentation, and sales distribution

### Phase 2 – Power BI Dashboard
- Built a live, interactive dashboard for business users
- Enabled slicing by time, product, region, and channel
- Highlighted trends, outliers, and actionable insights

---

## 🔄 Project Workflow

1. 📥 Load & Explore Raw Data  
2. 🧹 Data Cleaning & Preprocessing  
3. 🛠️ Feature Engineering  
4. 📊 Exploratory Data Analysis  
5. 📌 Key Insights & Recommendations  
6. 📈 Dashboard Design in Power BI  

---

## 🗃️ Final Dataset Structure

| Type        | Columns Included |
|-------------|------------------|
| Identifiers | `order_number`, `order_date`, `customer_name`, `channel`, `product_name` |
| Financials  | `quantity`, `unit_price`, `revenue`, `cost`, `profit`, `profit_margin_pct` |
| Calendar    | `order_month_name`, `order_month_num` |
| Geography   | `state`, `state_name`, `us_region`, `lat`, `lon` |
| Planning    | `budget` (2017) |

---

## 📈 Key Insights

- **Monthly Revenue Cycle**:Revenue stays stable between ≈ 23M -26.5M across 2014–2017, with no consistent seasonal spikes. Sharpest drop (≈$21.2M) occurs in early 2017, indicating a possible one-time disruption. 
- **Channel Mix**: Wholesale: 54%. Distributors: 31%. Exports: 15% — opportunity to scale international presence.  
- **Top Products (Revenue)**: Product 26:118M ; Product 25:110M; Product 13:78M. Mid -tier:68–75M; bottom performers: $52–57M.
- **Profit Margins:**:Profit margins range broadly from ≈18% to ≈60%, with no strong correlation to unit price. Dense horizontal bands suggest standardized pricing strategies across tiers.
- **Seasonal Volume:**: No strong monthly pattern, but slight volume uptick appears around May–June. Early 2017 dip (≈$21.2M) may require investigation.

---

## 📊 Dashboard Preview

| Page | Overview |
|------|----------|
| **1** | Excutive Overview & trends  |
| **2** |Product & Channel Performance |
| **3** |Geographic & Customer Insights |

> 📌 Built using **Power BI** for interactive, real-time insights.

---
## 📌 Deliverables

- 📓 `EDA_Analysis.ipynb`: Full Python code with step-by-step EDA
- 🖼️ Power BI Dashboard (3 Pages)
- 📊 Project Presentation: `PPT - Regional Sales Analysis.pptx`
  
---

## 📁 Tools Used

- **Python** – Data Cleaning & EDA  
- **Pandas, Matplotlib, Seaborn** – Data Visualization  
- **Power BI** – Dashboard Creation  
- **Excel** – Initial Data Exploration

---

## ✅ Conclusion

This end-to-end analysis reveals critical sales insights, enabling better strategic planning. The dashboard equips stakeholders to explore trends independently and adapt swiftly to market dynamics.

---

