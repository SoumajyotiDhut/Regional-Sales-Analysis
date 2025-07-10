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

- **Seasonality**: Revenue peaks in May-June, lowest in January  
- **Top SKUs**: Products 25 & 26 contribute ~25% of total sales  
- **Channel**: Wholesale dominates in volume, Export leads in margin  
- **Geography**: California leads in revenue; Northeast underperforms  
- **Customer Segmentation**: Top clients drive disproportionate revenue; margin opportunities exist in $6–9M accounts

---

## 💡 Recommendations

- 🎯 **Seasonal Promotions**: Target April slump & boost January campaigns  
- 🧪 **SKU Strategy**: Focus on top SKUs and eliminate underperformers  
- 🔄 **Channel Optimization**: Push Export for margins, Wholesale for volume  
- 🗺️ **Regional Expansion**: Replicate California model in Midwest & Northeast  
- ⚠️ **Margin Monitoring**: Flag and evaluate orders below 80% margin

---

## 📊 Dashboard Preview

| Page | Overview |
|------|----------|
| **1** | Performance Summary |
| **2** | Customer Segmentation |
| **3** | Revenue Scenarios |

> 📌 Built using **Power BI** for interactive, real-time insights.

---

## ✅ Conclusion

This end-to-end analysis reveals critical sales insights, enabling better strategic planning. The dashboard equips stakeholders to explore trends independently and adapt swiftly to market dynamics.

---

## 📁 Tools Used

- **Python** – Data Cleaning & EDA  
- **Pandas, Matplotlib, Seaborn** – Data Visualization  
- **Power BI** – Dashboard Creation  
- **Excel** – Initial Data Exploration

---

## 🙌 Acknowledgements

Thanks to the team for support and guidance throughout the project. Special mention to stakeholders and mentors who helped refine the approach and delivery.

---

## 📬 Contact

For queries or collaboration, feel free to connect via [LinkedIn](#) or email at [your-email@example.com](mailto:your-email@example.com).

