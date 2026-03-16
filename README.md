# GO ZERO  Sales Analysis

## Project Background

GO ZERO is a fast-growing Indian low-calorie and zero-added-sugar ice cream brand operating in the consumer packaged food industry.

The objective of this project is to analyze sales performance across products, platforms, cities, and time periods to identify key drivers of revenue and demand.

**Note:** The dataset used in this project is simulated and created for portfolio purposes. It does not represent real company data.

Insights and recommendations are provided across the following areas:

- Product Performance
- Platform Contribution
- Demand & Seasonality
- Geographic Demand

All analysis and visualizations were performed using **Microsoft Excel**.

---

## Data Structure & Initial Checks

The dataset contains **order-level sales records** across multiple cities and delivery platforms over a one-year period.

Key columns include:

- Date
- Platform
- City
- Product / Flavor
- Units Sold
- Revenue
- Discount
- Rating
- Review Count
- Time of Order

Initial data checks included:

- Validating date sequences
- Correcting incorrectly formatted negative revenue values
- Standardizing city names
- Handling missing rating values
- Verifying discount consistency across platforms

---

## Executive Summary

Three major insights emerged from the analysis:

- A small number of flavors drive a large portion of total revenue.
- Sales performance varies significantly across platforms, with **Swiggy generating the highest revenue**.
- Demand shows strong **seasonal and behavioral patterns**, peaking during summer months and late evening hours.

These findings highlight opportunities for improved product focus, platform strategy, and seasonal marketing initiatives.

---

## Insights Deep Dive

### 1. Product Performance

- **Cone ice creams** are the best-performing category, generating around **23K units sold annually**.
- Revenue is highly concentrated, with **7 out of 30 flavors contributing nearly 40% of total revenue**.
- **Hazelnut Chocolate Bar** and **Madagascar Chocolate Bar** generate some of the highest revenue shares.
- Flavors such as **Roasted Almond** and **Belgian Dark Chocolate** show consistently weaker demand.

---

### 2. Platform Contribution

- **Swiggy** generates the highest revenue (~₹33M).
- **BigBasket** records the lowest revenue (~₹21M).
- BigBasket shows relatively **high unit sales but lower revenue**, suggesting smaller order values.
- Most orders in top cities occur through **food delivery platforms like Swiggy and Zomato**.

---

### 3. Demand & Seasonality

- Sales are highly **seasonal**, with **March–June contributing around 40% of annual revenue**.
- Order activity peaks between **7 PM and 11 PM**, accounting for nearly **48% of units sold**.
- This suggests purchases are largely driven by **late-evening dessert or impulse buying behavior**.

---

### 4. Geographic Demand

- **Bengaluru** is the strongest market, contributing roughly **25% of total revenue**.
- **Pune** shows comparatively lower revenue.
- **Hazelnut Chocolate Bar** and **Madagascar Chocolate** remain popular across major cities.
- Around **55% of total revenue comes from just four cities**, indicating geographic concentration.

---

## Recommendations

Based on the insights above:

- **Prioritize top-performing flavors** in marketing campaigns and inventory planning.
- **Strengthen partnerships with high-performing platforms** such as Swiggy and Zomato.
- **Leverage seasonal demand** with targeted summer promotions.
- **Expand presence in high-performing cities** like Bengaluru.
- **Review underperforming products** for possible repositioning or removal.

---

## Assumptions & Limitations

- Some missing rating values were excluded from analysis.
- Revenue values that appeared negative due to formatting errors were corrected.
- Discount rates were relatively consistent across platforms (~10%), limiting discount impact analysis.
