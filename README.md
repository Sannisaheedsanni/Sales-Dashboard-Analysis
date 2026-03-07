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

Data Modeling: Establish relationships between order, customers, product and location
Calculated Field: Calculate KPIs such as total sales, total profit and total quantity
Dashboard Design: Create interactive visuals for easy insight exploration
Insight Extraction: Identify trends, growth difference, subcategories Sales and profit

---

## Dashboard Preview

> *Add dashboard screenshot here*
`![Sales Dashboard]()`

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

## Insights

**1. The business grew revenue by 51% over four years but profit margins are under pressure**
From 2020 to 2023, sales grew from $484K to $733K. However, in 2023, profit grew at only +14.2% compared to sales growth of +20.4% — indicating that the business is selling more but keeping less per sale. This margin compression warrants investigation into pricing, discounting, or rising costs.

**2. 2021 was a profitability turning point**
Despite a -2.8% decline in total sales in 2021, profit grew by +24.4%. This suggests the business improved its product mix or reduced discounting, focusing on higher-margin subcategories like Copiers and Accessories rather than volume-driven but low-margin products.

**3. 2022 was the strongest overall year**
2022 delivered the highest growth across all three KPIs simultaneously — Sales +29.5%, Profit +32.7%, Quantity +23.3%. Profit growing faster than sales indicates improved efficiency and margin management during this period.

**4. Machines is a persistent loss-making subcategory**
Machines generates notable sales volume but shows a loss bar in the profit view for 2023, and its sales declined vs the prior year. This pattern of high revenue with negative or near-zero profit makes Machines a key area of concern.

**5. Copiers consistently deliver the highest profit margin**
Across all four years, Copiers show a disproportionately large profit bar relative to their sales bar — indicating a high-margin product. Despite not being the top seller by volume, Copiers are one of the most valuable subcategories to the business.

**6. Phones drive the most revenue but with moderate margins**
Phones consistently rank as the top subcategory by sales volume across all years, but their profit bar is proportionally smaller than Copiers — suggesting heavy competition or discounting in this category.

**7. Weekly sales are concentrated with many below-average weeks**
The weekly trends chart shows that sales and profit are driven by a small number of high-performing weeks, with the majority of weeks falling below the average. This points to a reliance on seasonal spikes rather than consistent weekly performance.

---

## Recommendations

**1. Investigate and address Machines profitability**
Conduct a detailed review of the Machines subcategory — including pricing, discount rates, and cost of goods. Consider whether to reprice, reduce discounts, or deprioritize this subcategory in the product strategy.

**2. Protect and grow the Copiers category**
Given Copiers' consistently high profit margins, the business should invest in marketing and inventory for this subcategory to drive higher sales volume without sacrificing margins.

**3. Review discount strategy for Phones**
As the highest revenue subcategory with moderate margins, Phones may be subject to excessive discounting. A pricing strategy review could improve profitability without significantly impacting sales volume.

**4. Address margin compression in 2023**
With profit growing slower than sales in 2023, the business should audit its cost structure and discount patterns to prevent further margin erosion as revenue scales.

**5. Smooth out weekly performance**
Given the concentration of revenue in a small number of high-performing weeks, the business should explore mid-week or off-peak promotions to distribute sales more evenly and reduce revenue volatility.

**6. Build on the 2021 efficiency playbook**
The 2021 results — where profit grew despite lower sales — demonstrate that focusing on product mix and margin management is effective. This approach should be revisited when overall growth slows.

---

## How to Use This Dashboard

1. Download the `.twbx` file or open the Tableau Public link above
2. Use the **SELECT YEAR** parameter to switch between 2020, 2021, 2022, and 2023
3. Use the **filter panel** (toggle button, top right) to filter by Category, Sub-Category, Region, State, or City
4. Review KPI banners for a high-level summary, then drill into subcategory and weekly views for deeper analysis

---

## Acknowledgement

> 📌 The dashboard design requirements for this project were guided by **[Data with Baraa](https://www.datawithbaraa.com)**. The analysis, insights, and recommendations are my own.
