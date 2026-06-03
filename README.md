# Regional Sales Performance Tracker

## 📌 Project Overview
This repository contains a dynamic, enterprise-grade Power BI dashboard tailored for Fast-Moving Consumer Goods (FMCG) distribution tracking. Transforming raw operational data into interactive visuals, it equips stakeholders to identify primary revenue drivers, track regional velocity, and isolate sales seasonality.

## 📊 Key Insights & Analytics
* **Macro Metrics:** Consolidates 298.10M in Total Sales Value, 676.32 Total Sales Tons, and a calculated average price of 440.77K per ton.
* **Portfolio Dominance:** Showcases brand market share via donut charts, revealing that the *DIPLOMA* brand controls 60.76% (181.13M) of total revenue, followed by *HAPPY COW* at 10.42%. 
* **Categorical Drivers:** Pinpoints *MILK* as the primary revenue category, generating over 219.87M, heavily outpacing *CRACKERS* (24.23M) and *BISCUITS* (19.68M).
* **Geographic Distribution:** Ranks performance across local operational territories, identifying key high-volume zones including Feni, Cumilla, Bahaddarhat (17.54M), and Banasree (15.61M).
* **Temporal Patterns:** Line graphs map out daily sales throughout December, highlighting a recurring weekly cyclical rhythm and an aggressive end-of-month volume spike driven by the *MILK* category.

## 🛠️ Technical Implementation
* **Data Layer:** Multi-dimensional transactional datasets spanning area, category, brand, and territory hierarchies.
* **BI Architecture:** Built using Microsoft Power BI Desktop, utilizing dynamic multi-select slicers for fluid data drilling.
* **Calculations:** Structured through custom DAX measures for cross-filtering, category running totals, and volumetric conversion formulas.

## 📈 How to Use
1. Clone the repository and open the `.pbix` file in Power BI Desktop.
2. Use the left-side filter pane to slice by specific `area_name` or `brand_name`.
3. Hover over the line charts to view daily performance changes during the December sales cycle.
