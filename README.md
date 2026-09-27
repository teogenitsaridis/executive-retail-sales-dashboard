# 📊 Executive Retail Sales & Performance Dashboard (Excel)

An interactive, dark-themed executive sales dashboard built in **Microsoft Excel**, analyzing over **10,000 retail transactions** (2021–2024). The dashboard tracks sales performance against regional plans, visualizes monthly and quarterly trends, and features dynamic interactivity with slicers and a custom **Best vs. Worst Performing Cities** toggle.

---

## 📸 Dashboard Showcase

### Executive View – Top Performing Cities (Best Result)
<img width="100%"  alt="Screenshot 2026-09-27 182704" src="https://github.com/user-attachments/assets/20426ce1-1d78-4354-9c43-28ed889fcc6f" />


### Executive View – Bottom Performing Cities (Worst Result)
<img width="100%"  alt="Screenshot 2026-09-27 182725" src="https://github.com/user-attachments/assets/98648bd7-42fb-4d92-b4f5-199347148dce" />

---

## 🎯 Business Problem & Core Objectives
Corporate sales leadership needed a centralized Excel tool to monitor financial milestones across the United States:
* **Plan vs. Actual Performance:** Measure dynamic plan achievement rates across Central, East, South, and West regions.
* **Seasonality & Run-rate:** Monitor revenue progression across Quarters (Q1–Q4) and Months across a 4-year timeline.
* **Category & Sub-Category Mix:** Identify volume drivers (Technology, Furniture, Office Supplies) and granular product shares (Chairs, Phones, Storage).
* **Geographical Outliers:** Immediately toggle between top-producing cities and underperforming areas to optimize supply chain and regional marketing.

---

## ⚙️ Key Technical Features & Advanced Excel Techniques

* **Custom Speedometer (Gauge) Chart:** Engineered using layered Doughnut and Pie chart structures driven by dynamic target-tracking tables (0–100 scale, currently displaying 92% Plan Achievement).
* **Interactive Top/Bottom Toggle Buttons:** Form-control / formula switch displaying the **Top 10** (e.g., New York City, Los Angeles, Seattle) versus **Bottom 10** (e.g., Abilene, Elyria, Jupiter) revenue-generating cities with embedded in-cell data bars.
* **Dynamic Slicers & Cross-Filtering:** Interactive Slicer navigation panel synchronized across multiple Pivot Tables by **Region** (Central, East, South, West) and **Year** (2021–2024).
* **Dual-Metric Visual Scorecards:** KPI cards combining Doughnut shares with clustered column charts for Category and Segment distributions (Consumer: 51%, Corporate: 31%, Home Office: 19%).
* **Modern Dark UI Design:** Custom neon-accented dark interface optimized for executive presentations and clear visual hierarchy.

---

## 🏗️ Workbook Architecture

The project contains a clean separation between raw data, analytical calculations, and presentation layers:
* **`Orders`:** Raw transactional fact table containing ~10,000 order records (Order Date, Customer Segment, City, State, Region, Category, Sub-Category, Sales, Quantity).
* **`Sales plan`:** Benchmark targets by Region and Year used to compute corporate attainment percentages.
* **`Pivot Tables`:** The engine sheet containing dedicated Pivot Tables for monthly revenue, regional summaries, category breakdowns, and helper tables for the speedometer gauge.
* **`Dashboard` & `Dashboard (2)`:** The interactive front-end reporting interfaces housing visual charts, slicers, KPI scorecards, and city rankers.

---

## 📈 High-Level Business Insights (Sample)
* **Target Attainment:** Overall revenue reached **€2,756,640** across **37,873 goods sold** in **531 cities**, achieving **92%** of the corporate target plan.
* **Revenue Concentration:** Technology accounted for the highest single category revenue (**€1,003,384** / 36%), while Phones and Chairs represented 28% of total product volume.
* **Geographical Leaders:** New York City (**€307,642**) and Los Angeles (**€211,021**) lead domestic revenue generation.

---

## 🛠️ Tech Stack & Skills Demonstrated
* **Tool:** Microsoft Excel (Advanced)
* **Features:** Advanced Pivot Tables, Pivot Charts, Slicers, Custom Gauge Charts, Dynamic Data Bars, Target vs. Actual Variance Analysis, Dark UI/UX Design
