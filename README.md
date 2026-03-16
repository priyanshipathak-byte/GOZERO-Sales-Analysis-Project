GO ZERO Ice Cream – Sales Analysis
Project Background

GO ZERO is a fast-growing Indian low-calorie and zero-added-sugar ice cream brand operating in the consumer packaged food industry. The company primarily sells through quick-commerce and food delivery platforms such as Instamart, Zepto, Blinkit, Swiggy, Zomato, and BigBasket.

As a data analyst at the company, the objective of this project is to evaluate sales performance across products, platforms, cities, and time periods to identify the key drivers of revenue and demand.

The analysis focuses on the following key business metrics:

Total Revenue

Units Sold

Average Order Size (AOS)

Platform Performance

Customer Ratings

Insights and recommendations are provided on the following key areas:

Category 1: Product Performance
Category 2: Platform Contribution
Category 3: Demand & Seasonality Trends
Category 4: Geographic Demand Distribution

The SQL queries used to inspect and clean the data for this analysis can be found here [link].

Targeted SQL queries regarding various business questions can be found here [link].

An interactive Tableau dashboard used to report and explore sales trends can be found here [link].

Data Structure & Initial Checks

The company's sales dataset contains order-level records capturing product sales across multiple platforms and cities over a one-year period.

The dataset consists of one main sales table containing transactional information including:

Sales Table

Key columns include:

Date

Platform

City

Product / Flavor

Units Sold

Revenue

Discount

Rating

Review Count

Time of Order

Initial data checks included:

Sorting and validating date sequences

Correcting negative revenue values

Standardizing city names

Handling missing rating values

Verifying consistency of discount rates across platforms

Executive Summary

Three major insights emerge from the analysis.

First, a small set of products drives a large share of revenue, with only five flavors contributing roughly 45% of total sales, indicating strong product concentration.

Second, platform distribution plays a major role in revenue, with Swiggy generating the highest revenue among all platforms, while BigBasket contributes the lowest despite strong unit sales.

Third, demand shows clear seasonal and behavioral patterns, with peak sales occurring during summer months and during late evening hours.

These insights highlight opportunities for product focus, platform partnerships, and targeted marketing during peak demand periods.

Insights Deep Dive
Category 1: Product Performance
Main Insight 1

Cone ice creams represent the best performing product category, generating approximately 23K units sold annually, significantly outperforming most other product types.

Main Insight 2

Revenue is highly concentrated: 7 out of 30 flavors contribute nearly 40% of total revenue, indicating strong customer preference toward a limited set of products.

Main Insight 3

Chocolate-based products such as Hazelnut Chocolate Bar and Madagascar Chocolate Bar generate some of the largest revenue shares, making them core revenue drivers.

Main Insight 4

Certain flavors such as Roasted Almond and Belgian Dark Chocolate consistently underperform across the year, indicating weak product demand.

Visualization:
Product Revenue Contribution Chart (Pareto Chart)

Category 2: Platform Contribution
Main Insight 1

Swiggy generates the highest total revenue, contributing approximately ₹33M, making it the company’s most important sales channel.

Main Insight 2

BigBasket records the lowest revenue (~₹21M) among all platforms, suggesting weaker demand or lower visibility on the platform.

Main Insight 3

Despite lower revenue, BigBasket shows high unit sales, suggesting smaller order values or lower product pricing.

Main Insight 4

Across the top three revenue generating cities, the majority of sales occur through Swiggy and Zomato, highlighting the importance of food-delivery platforms in urban markets.

Visualization:
<img width="655" height="356" alt="image" src="https://github.com/user-attachments/assets/fe8831a0-10fd-4da4-813e-cb0e882b5481" />


Category 3: Demand & Seasonality
Main Insight 1

Ice cream demand is strongly seasonal. Summer months (March–June) generate approximately 40% of total annual revenue, indicating significant seasonal concentration.

Main Insight 2

Customer purchasing behavior peaks during evening hours (7 PM – 11 PM), contributing around 48% of total units sold.

Main Insight 3

This pattern suggests that ice cream consumption is largely driven by late-evening dessert or impulse purchases.

Main Insight 4

Seasonal demand patterns suggest significant opportunities for targeted summer marketing campaigns and promotional bundles.

Visualization:
<img width="624" height="323" alt="image" src="https://github.com/user-attachments/assets/a1394efc-b9fd-4fbb-8d1d-adaded0e9fb1" />


Category 4: Geographic Demand
Main Insight 1

Bengaluru is the strongest performing market, contributing roughly 25% of total revenue, indicating strong brand penetration.

Main Insight 2

Pune generates comparatively lower revenue, suggesting weaker demand or lower market penetration.

Main Insight 3

Across the highest performing cities, Hazelnut Chocolate Bar and Madagascar Chocolate remain consistently popular, indicating universal flavor preference.

Main Insight 4

Approximately 55% of total revenue comes from just four cities, highlighting strong geographic concentration.

Visualization:
<img width="605" height="296" alt="image" src="https://github.com/user-attachments/assets/7f07082a-5313-4a7a-9106-ae61cf46c81e" />
<img width="677" height="348" alt="image" src="https://github.com/user-attachments/assets/842f5ff6-3593-424b-bb3a-09998daff7d8" />


Customer Experience Insights
Main Insight 1

Top-rated products include:

Butterscotch

Simply Sitaphal

Butterscotch Caramel Cone

Jamun Sriracha Pop

Main Insight 2

Customer ratings across products are very consistent, mostly between 3.8 – 4.0, indicating generally positive customer satisfaction.

Main Insight 3

No strong relationship is observed between ratings and sales volume, suggesting demand is influenced more by flavor popularity and product format.

Main Insight 4

Kulfi and Fruit Pop categories have the highest average ratings (~3.92) while ice cream bars have slightly lower ratings (~3.8).

Recommendations

Based on the analysis, the following actions are recommended:

1. Focus on high performing product lines

Since five flavors drive nearly half of total revenue, the company should prioritize these flavors in marketing campaigns, inventory allocation, and promotional placements.

2. Strengthen partnerships with high-performing platforms

Given Swiggy and Zomato generate the highest revenue in major cities, the company should consider exclusive promotions, visibility boosts, and advertising partnerships on these platforms.

3. Optimize marketing around seasonal demand

Because 40% of annual revenue occurs during summer months, targeted seasonal campaigns and product launches during this period could significantly increase revenue.

4. Expand presence in high-demand cities

With Bengaluru contributing 25% of total revenue, the company should deepen its presence in similar urban markets through localized marketing strategies.

5. Reevaluate underperforming products

Products such as Roasted Almond and Belgian Dark Chocolate should be reviewed for possible reformulation, repositioning, or removal from the catalog.

Assumptions and Caveats

During the analysis, several assumptions were made due to limitations in the dataset.

Some missing rating values were excluded from rating analysis.

Revenue values that appeared negative due to formatting issues were corrected during data cleaning.

Discount rates remained relatively constant across platforms (~10%), limiting the ability to evaluate the impact of discounting on sales.
