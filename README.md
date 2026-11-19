# 🛒 E-Commerce Executive Analytics Dashboard

An end-to-end interactive **E-Commerce & Logistics Executive Dashboard** built in **Microsoft Excel**. This project consolidates **24 monthly e-commerce order files** (**39,743 records**) alongside logistics and product master data into a robust **9-relationship Star Schema**, delivering actionable executive insights into revenue, profitability, and fulfillment performance.

---

## 🎯 Project Objectives
- **Automated Multi-File Consolidation:** Combine 24 separate monthly CSV/Excel order logs into a single clean, unified dataset using Power Query.
- **Enterprise Data Modeling:** Design a scalable Star Schema linking transactional order data with customer, product, calendar, and logistics dimension tables.
- **Profitability & Cost Analysis:** Move beyond top-line revenue by engineering custom DAX measures for **Contribution Margin**, **Net Revenue**, and fulfillment costs.
- **Executive Decision Support:** Provide leadership with an interactive dashboard featuring dynamic slicers to monitor KPIs across time, product categories, and shipping regions.

---

## 🛠️ Tools & Technical Stack
- **Microsoft Excel:** Primary analytical platform and executive UI/UX dashboard design.
- **Power Query (ETL):** Automated folder-level ingestion of 24 monthly files, data type standardization, null handling, and transformation pipelines.
- **Power Pivot & Data Modeling:** Constructed a **9-relationship Star Schema** connecting fact sales/logistics tables to lookup dimensions for optimal query performance.
- **DAX (Data Analysis Expressions):** Engineered dynamic KPIs including:
  - Total Gross & Net Revenue
  - Contribution Margin & Margin %
  - Average Order Value (AOV)
  - Total Orders & Fulfillment / Delivery SLA Metrics
  - Month-over-Month (MoM) & Year-over-Year (YoY) Growth

---

## 📈 Key Insights & Analytical Highlights
- **Scale & Consolidation:** Successfully unified **39,743+ order records** spanning two full years (24 months) without manual copy-pasting, enabling instant refresh capabilities.
- **Margin Optimization:** Isolated high-revenue vs. high-margin product categories using **Contribution Margin** analysis to identify profit drivers and logistics cost bottlenecks.
- **Operational & Logistics Visibility:** Tracked order fulfillment efficiency and shipping performance alongside sales trends to highlight regional delivery delays and cost variances.

---

## 🎛️ Dashboard Features
- **Executive KPI Scorecards:** Instant visibility into Total Revenue, Contribution Margin, Total Orders, and Average Order Value (AOV).
- **Dynamic Slicers & Timelines:** Interactive filtering by **Year/Month**, **Product Category**, **Region**, and **Order/Delivery Status**.
- **Trend & Profitability Visuals:** Multi-series charts illustrating monthly revenue trajectories, margin breakdowns, and top-performing product segments.
- **Logistics Performance View:** Visual tracking of shipping modes, delivery timelines, and fulfillment rates.

