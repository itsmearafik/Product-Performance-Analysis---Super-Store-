# SuperStore Sales Performance

Exploring Profitability accross products, segments and regions.

---

!["Landing Page Banner/Image"](https://github.com/itsmearafik/Product-Performance-Analysis---Super-Store-/blob/main/images/dashboard.png)

## Background

---

As a Product Analyst for a Superstore based in the US, I conducted an Exploratory Data Analysis (EDA) on product performance to uncover underperforming areas accross regions, market segments and product categories. The goal was to identify weak areas and provide data-driven recommendations to improve sales, increase profit and enhance regional strategies.

## Target Audience

---

This project is designed to provide valuable insights relevant for decision-making, performance monitoring and strategic planning across various roles.

1. Business Stakeholders (Product Managers, Sales Managers, Regional Managers, etc):

* Identifying underperforming products, loss-making states and profit drivers guide actionable improvements in pricing, inventory and regional sales strategies.

2.Data and Business Analysts (Business Intelligence Analysts, Customer Experience (CX) Analysts):

* This case study offers an effective approach to exploratory data analysis (EDA), visual storytelling and deriving business-relevant insights from insights from retail data, valuable for benchmarking and learning.

3.Executives and Strategy Teams (C-Level executives, Strategic Planners)

* This project provides performance and Key Performance Indicators (KPI's) breakdowns to support strategic decisions on market focus, product investment and profitability optimization.

## Business Needs

---
![](https://github.com/itsmearafik/Product-Performance-Analysis---Super-Store-/blob/main/images/profit_by_segment.png)


The insights from this project will serve strategic and operational needs as outlined below:

1. Assess Overall Business Performance:
Understand total orders, revenue, profit, and average discounts at a glance.
Evaluate the geographical spread and volume of operations across 49 states and 531 cities.
2. Identify High and Low Performing Products:
Detect top-grossing sub-categories and those consistently generating losses.
Determine which product categories contribute most to total sales and profit.
3. Uncover Regional and State-Level Weaknesses:
Map revenue and profit contribution across US states.
Pinpoint underperforming states to inform regional sales strategies.
4. Evaluate Segment and Customer Group Performance:
Compare revenue and profit by customer segment (Consumer, Corporate, Home Office).
Identify the most and least profitable segment-product combinations.
5. Understand the Impact of Discounts and Order Volumes:
Analyze how average discount levels affect profitability across product categories.
Flag areas where excessive discounting leads to losses.
6. Optimize Shipping Mode and Logistics Strategy
Assess how shipping mode (e.g., Standard, First Class) affects profit margins.
7. Support Data-Driven Decision-Making:
Provide actionable insights to guide pricing, regional targeting, and logistics.
Empower business managers to optimize strategies for profitability and growth.

## Key Questions Answered
![](https://github.com/itsmearafik/Product-Performance-Analysis---Super-Store-/blob/main/images/top_profit_products.png)
---

* What are the overall sales and profit figures?
* Which segments and product categories drive or drag performance?
* Which states or cities are underperforming or excelling?
* How do product sub-categories differ in terms of sales and profit?
* Which shipping modes is most utilised?
* What are the most and least profitable products?
* Where are we losing money despite high order quantity/product movement?
* How can shipping and pricing strategies be optimized?


![](https://github.com/itsmearafik/Product-Performance-Analysis---Super-Store-/blob/main/images/order_by_ship_mode.png)


## Skills Applied

---

* Data Validation in Power Query
* Defining & Computing KPIs
* Power BI DAX Concepts: Calculated Measures
* Data Visualization and Visual Storytelling.
* Power BI Dashboarding
* Filters and Slicers
* Tooltips

## Data Source Info

---

The dataset comprises a single table with 9,994 rows and 13 columns, representing detailed product order and sales records from a fictitious U.S.-based Superstore. It includes transactional data across various: States, Market segments (e.g., Consumer, Corporate, Home Office), Product categories and sub-categories. Each record provides insights into key business metrics such as: Sales and Profit, Quantity and Discount, Region Details, Ship mode. The dataset was gotten from [The Spark Foundation_GRIP](https://bit.ly/3i4rbWl).

## Defining Key Performance Indicators (KPIs)

---
The following metrics were identified as essential Key Performance Indicators (KPIs) to provide the business user with insights into the effectiveness of each campaign, and Identify opportunities for optimization:

Provided KPIs (Available in the dataset)

* Total Orders: Number of units sold per order (Indicates product demand volume by segment or region.)
* Total revenue: Total dollar value of products sold (Tracks gross revenue generation across categories, segments, and states).
* Profit: Net earnings from product sales after cost deductions (Measures business profitability, helping to identify profitable or loss-making areas).
* Discount: The percentage reduction offered on products sold (Helps assess discounting practices and their potential impact on profit margins).

These KPIs were used throughout the dashboard to enable interactive exploration and comparison across states, market segments, and product categories — supporting informed business decisions and targeted recommendations.

## Exploratory Data Analysis (EDA)

---
The dataset was imported into Power BI’s Power Query for data validation and cleaning. The column profiling was changed from ‘based on Top 1000 rows’ to ‘based on entire dataset’. ‘Column quality’ and ‘Column distribution’ checkboxes were selected to get a summary information about each column for effective cleaning/Preprocessing. The data table was fairly clean and required minimal transformation, which was carried out as follows:

Column datatypes were validated appropriately - Columns that contain financial data such as the `Sales`,`Profit`, and `Discount` were changed to Currency Type.
There were no missing values, empty cells or duplicates. All datapoints were checked and made system ready for a reliable analytical insights.

With the data now transformed and cleaned, I proceeded to explore it in order to:

Analyze sales performance, profitability, discount patterns, and order volume across product segments, categories, and geographic locations.
Provide insights into which product groups and customer segments drive or drain profit.
Identify opportunities to improve operational efficiency and maximize profitability, addressing the core business need of uncovering weak areas and guiding strategic decisions.
I approached the analysis with a structured, insight-driven workflow focused on uncovering profitability patterns and performance gaps across products, segments, and regions. Specifically, I:

Aggregated key metrics such as Total Sales, Total Profit, Profit Margin, Order Quantity, and Average Discount to assess performance at various business levels.
Evaluated profitability trends to identify underperforming product lines and states, with special attention to combinations of high discounts and low or negative profit margins.
Implemented interactive slicers in Power BI to enable dynamic filtering and drill-down by: Customer Segment, Product Category, State, and Region.
This approach enabled a comprehensive and flexible exploration of the dataset, equipping business users with targeted insights for data-driven decision-making.

## KPI Visualization/Presentation Dashboard Visuals

---
I begin by establishing a baseline understanding of product and sales performance across customer segments, categories, and regions - `what’s working and where do we stand?` We observed, from interacting with the visual, that the the highest demand (order quantity) is in the Consumer segment, with the Technology category, generating the highest sales and profit across the business. This reveals a core strength worth reinforcing through marketing and product focus. Interestingly, while the Home-Office segment records the highest profit, it receives the fewest orders. This suggests an opportunity to scale, by increasing volume without sacrificing profitability.

!["Landing Page Banner/Image"](https://github.com/itsmearafik/Product-Performance-Analysis---Super-Store-/blob/main/images/dashboard.png)

However, When we shift attention to the profit patterns, to uncover where we’re at risk, how discounting strategies impacts performance, and what needs attention, it becomes evident that high discount doesn’t always equate to higher profits. Certain product sub-categories, like Tables and Bookcases, despite high order quantity, return little to no profit due to deep discounting. This signals potential issues with pricing strategy or over-reliance on promotions.

## Key Insights

---
The dashboard analysis yielded several important business insights:

### High Performers

* The Consumer Segment and Technology Category had the highest overall revenue and profit contribution.
* The Home Office Segment showed the highest profit returns despite having the lowest order volume.
* Technology is the top-selling category
* Phones and Chairs are the leading sub-categories
* Standard Class is the most used shipping mode
* Profit peaks in the October–December months.

### Profit Leakage & Risks

* A significant number of least profitable products, such as Tables and Bookcases were associated with high average discounts.

## Recommendations

Based on the analysis, the following strategic actions are recommended:

* Scale High-Performing Areas: Increase investments in the Consumer segment and Technology category through targeted promotions, bundled offerings, and wider product availability.
* Leverage the Home Office Segment: Though order quantity is lowest, its profitability is highest. Efforts should focus on increasing sales volume while maintaining or improving the profit.
* Reevaluate Discounting Strategy: Implement a review process for discount approvals, especially for low-performing product lines where high discounts are negatively affecting profit.
* Explore similar products in the best-selling category to drive growth.
* Aim for higher revenue and profit by optimizing sales trends.
* Focus on exceptional service and shipping strategies to meet customer preferences.

## Conclusion

This project provided a data-driven overview of sales and profit performance across a US-based Superstore’s product segments, categories, and regions. The analysis identified top and bottom product performers, profit risks tied to discounting, and under-leveraged segments with strong profit margin potential. With clear visualizations and actionable insights, the dashboard equips business leaders to:

* Make informed product, pricing, and marketing decisions.
* Improve profitability through optimized discounting.
* Align regional strategies based on revenue and profit contribution. Future analysis opportunities include drilling deeper into customer behavior, time series trends, and integrating supply chain cost data for full profitability analysis.

