# Amazon-Sales-Revenue-Analysis
End-to-end Power BI &amp; SQL analysis of 1.2M+ Amazon E-commerce records. Featuring dynamic DAX 'What-If' scenario forecasting and executive-level dashboarding.
The highlight of this project is the What-If Scenario Analysis, which allows stakeholders to simulate various sales growth 'boosts' and visualize the impact on projected revenue in real-time.

🛠️ Technical Workflow
1. Data Engineering (SQL & Power Query)
Scalability: Optimized queries to handle and clean a massive dataset of 1.2M+ records without performance lags.

Data Cleaning: Used SQL to handle null values in 'Price' and 'Ratings', and removed duplicate 'ASIN' entries to ensure 100% data integrity.

Feature Engineering: * Categorized products into 5 Budget Buckets (SuperLow to Ultra High) based on price points.

Grouped discounts into 6 Strategic Buckets to analyze their direct impact on the bottom line.

2. Advanced Data Modeling (DAX)
Scenario Analysis: Created a dynamic 'What-If' parameter to simulate sales boosts (0% to 50%).

Projected Revenue: Wrote complex DAX measures to calculate how a sales boost would scale the current $4.65bn revenue up to a potential $6.98bn.

Time-Intelligence: Integrated measures to compare "Last Month" performance vs. Projected targets.

📊 Business Insights Discovered
The Revenue King: Kitchen & Dining emerged as the top-performing category, contributing over $267M in revenue.

The Rating Paradox: Data revealed that SuperLow Budget items have higher customer satisfaction (4.12 stars) compared to Ultra High Budget items (2.02 stars), suggesting a massive quality-gap in premium segments.

Discount Efficiency: Proved that products with "No Discount" actually drive the bulk of total revenue ($2.6bn), challenging the need for aggressive discounting in certain categories.

🖥️ Dashboard Architecture
Page 1: Executive Overview – High-level KPIs (Total Revenue, Total Products, Avg Rating).

Page 2: Category Deep-Dive – Treemaps and Bar charts for granular category and discount analysis.

Page 3: Future Scenarios – Funnel visualizations linked to the 'What-If' slider for strategic planning.

UX Features: Chevron-style page navigation, synchronized slicers, and interactive cross-filtering.

