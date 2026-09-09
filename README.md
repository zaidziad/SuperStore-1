# 🛒 Superstore Retail Sales & Profitability Analysis (Power BI)

## 📌 Project Overview
An interactive executive Business Intelligence dashboard designed and developed using **Microsoft Power BI** to analyze retail store performance across the United States. The report tracks key financial KPIs, regional profitability, product category margins, and customer segment contributions to optimize retail operations and drive bottom-line growth.

---

## 📷 Dashboard Preview
<img width="1652" height="926" alt="SuperStore 1" src="https://github.com/user-attachments/assets/e8598438-0b77-4595-8fd7-88d136cf4254" />


---

## 📊 Key Executive KPIs & Insights

* **Total Revenue:** **$2.23M** in cumulative net sales.
* **Total Profit:** **$283.29K** generated across all orders.
* **Profit Margin:** **12.70%** overall operating profit margin.
* **Average Discount:** **15.62%** average promotional discounting rate.

### 🔍 Core Findings:
1. **Category Performance:**
   - **Technology** generates the highest profitability (**$143.87K / 50.78%** of total profit) with strong margins.
   - **Office Supplies** contributes **$120.8K (42.64%)** of profits.
   - **Furniture** represents high sales volume but yields the lowest profitability (**$18.62K / 6.57%**), largely impacted by steep discounts and elevated logistics costs.

2. **Customer Segmentation:**
   - **Consumer Segment** drives the majority of revenue (**$1.28M** sales).
   - Followed by **Corporate ($0.78M)** and **Home Office ($0.45M)**.

3. **Regional Dynamics:**
   - **West** and **East** regions are the primary profit drivers, outperforming Central and Southern territories.
   - High geographic density of orders concentrated in states like California and New York.

---

## 🛠️ Tech Stack & Skills Demonstrated
* **Tool:** Microsoft Power BI Desktop
* **Data Source:** Sample Superstore Dataset (`.xlsx`)
* **ETL & Data Cleaning:** Power Query (Column formatting, null handling, type transformation)
* **Data Modeling:** Star Schema architecture (Fact Orders + Dimension Tables)
* **DAX Formulas Applied:**
  - `Total Sales = SUM(Orders[Sales])`
  - `Total Profit = SUM(Orders[Profit])`
  - `Profit Margin = DIVIDE([Total Profit], [Total Sales], 0)`
  - `Avg Discount = AVERAGE(Orders[Discount])`
* **Visualization & UX:**
  - Executive KPI Cards
  - Geospatial US Choropleth Map (State-level performance)
  - Donut & Bar breakdown charts
  - Year-over-Year monthly trend lines
  - Dynamic slicers (*Category, Region, Segment, State, Date Range*) with a "Clear all slicers" reset functionality.

---

## 🚀 How to Run Locally

1. Clone or download the repository:
   ```bash
   git clone [https://github.com/zaidziad/superstore-sales-analysis.git](https://github.com/zaidziad/superstore-sales-analysis.git)
