# 🥤 Analytical Performance Dashboard — Brand & Region (FMCG 2025)

### 📊 Project Overview  
This Power BI project — **“Analytical Performance Dashboard: Brand and Region (FMCG 2025)”** — provides a comprehensive view of sales performance for a beverage company across multiple **brands**, **regions**, and **channels**.  
The goal is to help management teams track turnover, volume, gross margin, and cost distribution, while identifying key relationships between **brand performance** and **regional contribution**.

---

### 🧩 Data Source  
- **File:** `Data finance beer.xlsx`  
- **Type:** Excel workbook  
- **Scope:** FY2024 monthly sales and cost data by brand, region, and province  
- **Main variables:**  
  - `Turnover`, `Volume (HL)`, `COGS`, `Gross Profit`, `GBC`, `Marketing Expense`, etc.  
  - Hierarchies: `Region → Province → Channel → Brand`

---

### ⚙️ Data Preparation & Modeling  
**Tools used:**  
- **Power Query** — for cleaning, reshaping, and unifying Excel data (null removal, column transformations, type casting).  
- **Data Model Design:**  
  - Star schema with dimension tables for *Date*, *Region*, and *Brand*.  
  - Calculated relationships between sales, costs, and profitability metrics.  
- **DAX Measures:**  
  - `Turnover_sum`, `Volume_sum`, `GBC_total`, `TotalCost`, and key ratio indicators.  
  - Custom KPIs for **% of turnover**, **cost/revenue ratio**, **discount impact**, and **gross margin**.  

---

### 📈 Key Dashboards & Visuals  
1. **Sales Performance Overview**  
   - Monthly turnover and volume evolution (YoY trend).  
   - Channel and region-level contributions.  

2. **Profit & Loss Waterfall**  
   - From gross revenue to GBC (Global Business Contribution).  
   - Highlights the biggest impact items such as SST, COGS, and marketing investments.  

3. **Regional Performance**  
   - Interactive map by province with top 5 high and low turnover areas.  
   - Drill-down by *Region → Province → Brand*.  

4. **Brand Analysis**  
   - Turnover, volume, and GBC comparison by brand.  
   - Heatmap showing brand-region performance relationship.  
   - Margin and cost structure analysis.  

5. **Summary KPIs**  
   - 📦 **Volume:** 1.02M HL  
   - 💰 **Turnover:** 37.15T VND  
   - 📉 **GBC:** –2.14T VND  
   - 📊 **Total Cost:** 17.08T VND  

---

### 🧠 Business Insights  
- **North region** leads with ~45% of total turnover, followed by **Central (39%)** and **South (16%)**.  
- **Brand E** and **Brand F** are top contributors in both turnover and profitability.  
- High fixed and volume discounts significantly reduce gross margins in underperforming brands.  
- The heatmap analysis indicates regional dependency — e.g., Brand E dominates in North/Central, while Brand F is strong nationwide.  

---

### 💼 Use Case  
This dashboard was developed for **internal management reporting**, providing stakeholders with real-time insights into financial and commercial KPIs.  
It enables decision-makers to:  
- Monitor monthly business performance.  
- Detect underperforming brands or provinces.  
- Support budget reallocation and strategic planning.

---

### 🧰 Tech Stack  
| Tool | Purpose |
|------|----------|
| **Power BI Desktop** | Data visualization and DAX modeling |
| **Power Query (M language)** | Data cleaning and ETL |
| **Excel** | Source data preparation |
| **DAX** | Calculated measures and KPIs |

---

### 🚀 How to Use  
1. Open `PowerBI_reports_beverage.pbix` in **Power BI Desktop**.  
2. Ensure `Data finance beer.xlsx` is placed in the same folder (linked dataset).  
3. Refresh the model to update all metrics and visualizations.  
4. Navigate between report pages:  
   - **Sales Overview**  
   - **Performance by Region**  
   - **Performance by Brand**  
   - **Profit Breakdown**

---

### 🏁 Project Credits  
**Author:** *Nguyen Phuoc Bao Trung*  
**Role:** Data Analyst – responsible for data cleaning (Power Query), modeling (DAX), and dashboard design.  
**Year:** 2025  
