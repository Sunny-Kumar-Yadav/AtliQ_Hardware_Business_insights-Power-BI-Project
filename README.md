# 📊 AtliQ Hardware – Business Insights (Power BI Project)

## 🧾 Project Overview

This project focuses on building a comprehensive **Business Intelligence (BI) dashboard** for **AtliQ Hardware**, a fictional tech-product company. AtliQ operates across multiple **product categories** such as Networking, Storage, Desktop, and Notebook, and sells through **Direct, Distributor, and E-commerce** channels across various regions and markets.

The goal was to simulate a **real-world enterprise BI solution** with dynamic dashboards for Finance, Sales, Marketing, Supply Chain, and Executive Management, all built using **Power BI**.

---

## 🧠 Objective

- Deliver **department-wise insights** using clean and intuitive dashboards.
- Enable **data-driven decision-making** by visualizing KPIs, trends, forecasts, and profit/loss analysis.
- Simulate real-life business challenges such as stakeholder expectations, UAT testing, governance, and performance optimization.

---

## 📁 Dashboard Views & Insights

### 1. 🏠 Home View
- Created a central **navigation page** with clear sectioning for each dashboard view.
- Included **Info & Support tabs** using bookmarks.
- Added basic dataset and schema descriptions for user context.

---

### 2. 💰 Finance View
**Visuals Used:**
- New card visuals (with conditional formatting) for KPIs: Net Sales, Gross Margin %, Net Profit % (vs Target/LY).
- Matrix for full P&L Statement – Current Year, LY/Target, Change, % Change.
- Top/Bottom Products & Customers by P&L.
- Area chart showing trends over time.

**Key Insights:**
- **140–354% Net Sales growth** between 2019 and 2022.
- Despite growth, **net profit is negative** post-2019 due to **high OpEx** – likely from aggressive market expansion.

---

### 3. 📈 Sales View
**Visuals Used:**
- Scatter Chart: Net Sales vs Gross Margin % (Dynamic GM% toggling).
- Donut Charts: % Breakdown of Net Sales, Gross Margin, Pre/Post Invoice Deductions, COGS.
- Matrix: Customer & Product-level Net Sales & Profitability.

**Key Insights:**
- In 2022, **Notebook** dominated product sales with **42.5% share**.
- **Amazon** topped customer Net Sales at **$496.88M**, while **Relief** showed higher GM%.

---

### 4. 📢 Marketing View
**Visuals Used:**
- Toggle-enabled Scatter Chart: GM% or NP% vs Net Sales.
- Waterfall Chart: Gross Margin → Operational Expense → Net Profit.
- Pie Chart: Gross Margin % and COGS %.
- Matrix: Segment & Market Sales Performance.

**Key Insights:**
- All regions showed **negative profitability** in 2022, primarily due to **OpEx exceeding GM**.

---

### 5. 🚚 Supply Chain View
**Visuals Used:**
- New card visuals for Forecast Accuracy %, Net Error, ABS Error.
- Matrix breakdown by Customer & Product.
- Line/Column charts for forecast metrics.

**Key Insights:**
- December 2021 had the **highest net error** with forecast accuracy at **81.5%**.
- FY2021 had the **highest absolute forecast error (~$10M)**.

---

### 6. 🧑‍💼 Executive View
**Visuals Used:**
- Composite cards for major KPIs with conditionally colored growth indicators.
- Column/Line/Area/Ribbon/Bar Charts for multi-year trends and comparisons.
- Matrix: Sub-region performance and Top/Bottom Products/Customers.

**Key Insights:**
- **Retailers contributed 70.5%** of revenue; **P&A Division** contributed ~49.9%.
- Despite losses, **6% market share** captured by 2022 due to strategic growth.

---

## 🛠️ Technical Work & Implementation

### 🔗 Data Connectivity & Preparation
- Connected **MySQL** database to Power BI (local connection).
- Verified data integrity, cleaned data, created **fact/dimension tables**.
- Built date dimension table with Fiscal Year & Fiscal Month columns.
- Performed **data validation** using cross-tab checks and UAT.

### ⚙️ Data Modeling
- Built **snowflake schema** using one-to-many relationships.
- Disabled unnecessary table data loads to optimize performance.
- Created YTD/YTG columns to analyze sales progression.

### 📐 DAX Measures
Created 25+ custom DAX Measures:
- KPIs: `Net Sales`, `Gross Margin`, `Net Profit`, `Forecast Accuracy`, `Net Error`, `ABS Error`.
- P&L Analytics: `P&L YoY Change %`, `Operational Expense`, `Revenue Contribution %`.
- Benchmark Variants: `vs LY`, `vs Target`.
- UX Enhancements: Dynamic Titles, Slicer Labels, Toggle Measures, Quarter Calculations.

### 🧰 Power BI Features & Tools Used
- **DAX Studio**: For model optimization & file size improvement.
- **Bookmarks**: For toggle views, Info tabs, and visual interactivity.
- **Dynamic Slicers**: Benchmarks, Product/Customer Segments.
- **Power BI Service**: Published report, set up **gateway**, enabled **data refresh**, created **App workspace**, and validated with **Live Excel file**.

### 📈 Advanced Visuals Used
- Waterfall Chart, Ribbon Chart, Area & Line Charts
- KPI Card with Conditional Formatting
- Matrix with Dynamic Column Names
- Tooltips for deep dive metrics

---

## 🎓 Learnings & Takeaways

- Real-world experience simulating **stakeholder interactions**, **UAT processes**, and **BI best practices**.
- Gained deep understanding of **Power BI's data modeling**, **performance tuning**, and **visual design** capabilities.
- Mastered DAX techniques to support **advanced business metrics** and interactivity.

---

## 🙌 Acknowledgment

**Special thanks to:**
- [Dhaval Patel](https://www.linkedin.com/in/dhavalsays)
- [Hemanand Vadivel](https://www.linkedin.com/in/hemvad)
- and the [**Codebasics**](https://www.linkedin.com/company/codebasics) team.

For their incredible guidance and Power BI teaching – this project wouldn’t have been possible without their structured, real-world-oriented approach. 🙏

---

## 🔗 Project Files & Dataset Access

Due to file size limitations (over 100MB), the Power BI reports and associated datasets are hosted externally.

👉 **[Access the project files here (Google Drive)](https://drive.google.com/drive/folders/1_r4dTAvjTHuGIN6jur0cGObQBpReCRcu?usp=sharing)**  

---

## 📎 Tools & Technologies

| Tool        | Purpose                          |
|-------------|----------------------------------|
| Power BI    | Data Modeling, Visualization     |
| DAX         | Metrics, KPIs, and Interactivity |
| Power Query | Data Transformation              |
| MySQL       | Source Data Connection           |
| Excel       | UAT & Validation                 |
| DAX Studio  | Model Optimization               |

---

## 📌 Author

**Sunny Kumar Yadav**  
📍 Delhi, India  
📧 sunnykryadav71432@gmail.com  
🔗 [GitHub](https://github.com/Sunny-Kumar-Yadav) | [LinkedIn](https://www.linkedin.com/in/sunnykumaryadav/)

---

## 📁 Project Status

✅ Completed – Deployed to Power BI Service  
📅 Last Updated – May 2025  
🔄 Includes dynamic data refresh and Excel Live integration

---

## 🔖 Tags

`#PowerBI` `#DataAnalytics` `#BusinessIntelligence` `#DAX` `#FinanceDashboard` `#SupplyChain` `#MarketingAnalytics` `#BIProjects` `#SQL` `#Codebasics`
