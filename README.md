# Sales & Profit Trends Dashboard | Tableau

## Project Overview

As a Data Analyst within the Analytics Team, I was tasked with designing and building an interactive Sales Dashboard to give the business a centralized view of its sales performance. The team identified a gap in how year-over-year performance was being tracked — reports were manual, fragmented, and slow to produce — and needed a scalable, self-service solution.

This dashboard delivers a comprehensive overview of sales metrics and trends across a 4-year period (2020–2023), enabling year-over-year performance analysis across sales, profit, and quantity — helping stakeholders make faster, more informed business decisions.

The primary stakeholders include sales managers, business analysts, and executives responsible for monitoring revenue growth, identifying performance gaps, and optimizing product strategy.

---

## The Task

The Analytics Team was approached by sales leadership who lacked visibility into year-over-year performance trends. Existing reports were manually compiled in spreadsheets, making it difficult to spot patterns quickly or drill into specific products and regions. As the analyst assigned to this project, I was responsible for translating the business requirements into a fully interactive dashboard.

The business required a centralized Sales Dashboard that addressed the following needs:

**KPI Overview**
- Display a summary of Total Sales, Profit, and Quantity for the current year and the previous year
- Show year-over-year % change for each KPI

**Sales Trends**
- Present monthly data for each KPI for both the current and previous year
- Identify months with the highest and lowest sales and make them easy to recognize

**Product Subcategory Comparison**
- Compare sales performance by product subcategory for the current and previous year
- Include a comparison of sales with profit to identify margin performance

**Weekly Trends for Sales & Profit**
- Present weekly sales and profit data for the current year
- Display average weekly values
- Highlight weeks above and below average to draw attention to performance

---

## Data Structure

- **Orders:** Order Date, Sales, Profit, Quantity, Product ID
- **Products:** Category, Subcategory, Product Name, Product ID
- **Location:** Region, State, City, Postal Code

---

## Tools Used

- Tableau Public (Desktop)

---

## Skills Applied

- Data Connection and Joining across multiple tables
- Calculated Fields for dynamic KPI computation
- Parameter-driven dynamic year filtering (SELECT YEAR)
- Dual Axis and Sparkline chart design
- Interactive Dashboard Design and Layout
- Business Intelligence Storytelling
- Insight Extraction and Performance Interpretation

---

## Data Analysis Process

- Data Modeling: Establish relationships between order, customers, product and location
- Calculated Field: Calculate KPIs such as total sales, total profit and total quantity
- Dashboard Design: Create interactive visuals for easy insight exploration
- Insight Extraction: Identify trends, growth difference, subcategories Sales and profit

---

## Dashboard Preview

<img src="Sales%20Dashboard%20(6).png" alt="Sales Dashboard">


🔗 [View Live on Tableau Public](https://public.tableau.com/app/profile/sanni.saheed/viz/SalesDashboard_17728782444670/SalesDashboard)

---

## Executive Summary

Analyzing performance from 2020 to 2023, the business has shown strong and consistent revenue growth — total sales increased from **$484K in 2020 to $733K in 2023**, representing a **~51% increase over four years**. However, a deeper look reveals important nuances in profitability, subcategory performance, and weekly sales patterns that require strategic attention.

| Year | Total Sales | Total Profit | Total Quantity | Sales vs PY |
|------|------------|--------------|----------------|-------------|
| 2020 | $484K | $50K | 8K | — |
| 2021 | $471K | $62K | 8K | -2.8% |
| 2022 | $609K | $82K | 10K | +29.5% |
| 2023 | $733K | $93K | 12K | +20.4% |

---

## Key Insights

- **Sales Growth Accelerated After the Baseline Year**;
The business grew revenue by 51% over four years but profit margins are under pressure**
From 2020 to 2023, sales grew from $484K to $733K.

- **A Few Products Drive Most Revenue**;
Subcategories generating the highest sales and profit consistently across all years include Phones, Copiers, Binders, and Storage. The business relies heavily on a small number of high-performing products that act as the primary revenue engine. Copiers in particular stand out — they deliver a large profit relative to their sales volume, making them the highest-margin subcategory in the portfolio.

- **Some Products Reduce Overall Profitability**;
Several subcategories generate very low or negative profit including Machines, Supplies, Fasteners, and Labels. Machines is the most concerning — it generates notable revenue but posted a loss in 2023 while also declining in sales vs the prior year. Supplies has shown persistent losses across all four years. These products reduce overall business profitability despite generating revenue.

- **Strong Seasonal Demand**;
Sales patterns across all years show consistently higher sales toward the end of the year, with Q4 being the peak period. The lowest sales months are typically January and February. This indicates seasonal purchasing behavior likely driven by holiday demand, year-end business purchasing, and promotional campaigns.

- **High Weekly Sales Volatility**;
Weekly sales fluctuate significantly, with occasional large spikes pushing sales far above the average weekly level. This suggests the business is heavily influenced by promotional campaigns, bulk orders, and seasonal demand fluctuations — and lacks consistent sales distribution throughout the year. Several weeks across all years also dip into negative profit territory, which is being masked by strong peak weeks.

---

## Business Recommendations

- **Prioritize High-Profit Products**;
Products such as Phones and Copiers should receive increased business focus. Recommended actions include increasing marketing investment, prioritizing inventory allocation, and introducing product bundles. Copiers in particular deserve greater strategic attention given their consistently high margins — scaling their volume would have an outsized positive impact on overall profitability.

- **Reevaluate Low-Profit Product Lines**;
Products that generate low or negative profit — particularly Machines and Supplies — should be analyzed further. Possible actions include renegotiating supplier contracts, increasing product pricing, and reducing or eliminating unprofitable items. Machines requires urgent review given it is both loss-making and declining in sales. Supplies has been a multi-year loss-maker and should be considered for phase-out.

- **Prepare for Seasonal Demand Peaks**;
Since demand consistently increases toward the end of the year, the business should increase inventory before peak months, plan marketing campaigns earlier in Q3, and optimize supply chain readiness. This ensures the company can fully capture peak demand without stock shortages or margin-eroding last-minute procurement.

- **Stabilize Revenue Throughout the Year**;
To reduce weekly sales volatility and reliance on seasonal spikes, the company could implement customer loyalty programs, subscription or recurring purchase models, and consistent mid-year promotional campaigns. These strategies can help create more predictable revenue streams and reduce the risk of loss-making weeks.



---

## How to Use This Dashboard

1. Download the `.twbx` file or open the Tableau Public link above
2. Use the **SELECT YEAR** parameter to switch between 2020, 2021, 2022, and 2023
3. Use the **filter panel** (toggle button, top right) to filter by Category, Sub-Category, Region, State, or City
4. Review KPI banners for a high-level summary, then drill into subcategory and weekly views for deeper analysis

---

## Acknowledgement

> 📌 The dashboard design requirements for this project were guided by **[Data with Baraa](https://www.datawithbaraa.com)**. The analysis, insights, and recommendations are my own.
