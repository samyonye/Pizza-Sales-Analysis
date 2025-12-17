# Pizza-Sales-Analysis

1. Introduction

This technical report presents a comprehensive analysis of pizza sales data visualized through an interactive Power BI dashboard. The purpose of the analysis is to evaluate sales performance, customer ordering behavior, product demand, and revenue distribution across different time periods, pizza categories, and sizes.

The dashboard consolidates key performance indicators (KPIs) such as total orders, total pizzas sold, total revenue, average order value, and average pizzas per order. By leveraging SQL for data extraction and Power BI for visualization, the report supports data-driven business decisions aimed at improving sales strategy and operational efficiency.

2. Story of the Data

The dataset represents transactional pizza sales records for the year 2015. Each record captures information related to customer orders, including order date, pizza type, category, size, quantity ordered, and revenue generated.

The data tells a clear business story:

Customers place orders throughout the year with noticeable daily and monthly variations.
Different pizza categories and sizes contribute unevenly to total sales and revenue.
Certain pizzas consistently outperform others, while some underperform across revenue, quantity, and order count.
The dataset enables management to understand customer preferences, identify best and worst sellers, and determine peak demand periods.

3. Data Splitting and Preprocessing

Data preparation was conducted to ensure accuracy and usability for analysis.

Data preprocessing steps:

Data extraction: Sales data was queried from a relational database using SQL.
Data cleaning:
Removal of duplicate orders
Handling of missing values
Standardization of date formats
Feature creation:
Total revenue calculated as price × quantity
Order-level aggregation for KPIs
Data splitting:
Independent variables: Order date, pizza category, pizza size, pizza name
Dependent variables: Total orders, quantity sold, revenue
The cleaned dataset was then loaded into Power BI for modeling and visualization.

4. Pre-Analysis

POTENTIAL ANALYSIS/QUESTION

1 Trends — How do sales vary by day, week, and month?

2 Peak Times — What are the busiest hours and days?

3 Customer Preferences — Which categories, sizes, and pizzas are most popular?

4 Revenue Drivers — Which pizzas bring in the highest revenue vs lowest?

5 Top Performers — What are the top pizzas by revenue, orders, and quantity?

6 Category Insights — Which pizza categories are most profitable vs most ordered?

7 Operational Needs — When do we need more staff or inventory

POTENTIAL INSIGHT

1 Sales Peaks → Orders may spike on weekends and evenings, showing when to allocate more staff.

2 Category Demand → Classic pizzas could drive the most orders, while Supreme pizzas bring in the most revenue.

3 Size Preference → Large and medium pizzas may dominate sales, while extra-large pizzas sell less but contribute more revenue per order.

4 Top Products → A small set of pizzas (top 5) might generate a large share of total revenue (80/20 rule).

5 Slow Movers → Some pizzas may have low sales and revenue, highlighting potential candidates for removal or discounting.

6 Seasonal Trends → Certain months may show higher demand (e.g., holiday periods).

7 Customer Spending → Average revenue per order could increase with premium pizzas or larger sizes

5. In-Analysis

INANALYSIS OBSERVATION

1 Sales peak on weekends and evenings.

2 December and holiday periods show higher monthly sales.

3 Classic pizzas drive the most orders, while Supreme pizzas bring in higher revenue.

4 Large and medium sizes dominate orders; extra-large adds higher revenue per order.

5 Top 5 pizzas account for a big share of revenue.

6 Some pizzas show low demand, dragging overall performance.

7 Peak times require better staffing and inventory planning.

INANALYSIS INSIGHT

1 Weekends & evenings are peak sales periods.

2 December & festive seasons drive higher sales.

3 Classic pizzas lead in orders; Supreme pizzas lead in revenue.

4 Large & medium sizes dominate sales; extra-large boosts profit per order.

5 Top 5 pizzas generate most of the revenue (80/20 effect).

Become a member
6 Several pizzas are low performers with weak demand.

7 Staffing & inventory must be optimized for peak times.

6. Post-Analysis and Insight

Post-analysis focused on extracting actionable insights from the dashboard visuals.

Sales Performance Insights:

Category performance:
The Classic category contributes the highest share of total sales.
Size performance:
Large-sized pizzas generate the highest revenue contribution.
Best sellers:
Thai Chicken Pizza leads revenue generation.
Classic Deluxe Pizza dominates quantity sold and total orders.
Worst sellers:
Brie Carre Pizza consistently ranks lowest in revenue, quantity, and order count.
These insights highlight product concentration and customer preference patterns.

7. Data Visualization and Charts

The Power BI dashboard includes multiple visualization types to communicate insights clearly:

KPI Cards: Display overall business performance metrics.
Press enter or click to view image in full size

Bar Charts:
Top 5 and Bottom 5 pizzas by revenue, quantity, and orders.
Press enter or click to view image in full size

Line and Area Charts:
Monthly and daily order trends.

Donut Charts:
Percentage contribution of sales by pizza category and revenue by pizza size.
Press enter or click to view image in full size

Slicers:
Pizza category and order date filters for interactive exploration.

These visuals enable stakeholders to quickly identify trends, outliers, and performance gaps.

8. Recommendation and Observation

OBSERVATIONS

1 Sales are highest on weekends and evenings, showing strong leisure-driven demand.

2 Holiday months (e.g., December) record peak sales, reflecting seasonal buying patterns.

3 Classic pizzas dominate in sales volume, while Supreme pizzas contribute more revenue.

4 Large and medium pizzas are customer favorites; extra-large sizes add higher profit per order.

5 A few pizzas (Top 5) generate the majority of revenue, while some show consistently low demand.

6 Peak sales periods highlight the need for better staffing and inventory management.

RECOMMENDATIONS

1 Boost staffing and inventory during weekends, evenings, and festive months.

2 Promote top-selling pizzas and reconsider low-demand items.

3 Focus on Classic pizzas for volume and Supreme pizzas for higher margins.

4 Stock more large & medium sizes, while upselling extra-large as a premium option.

5 Run seasonal promotions during holiday months.

6 Align purchasing with demand trends to cut waste and prevent stockouts.

7 Continuously monitor sales data to refine menu and operations.

9. Conclusion

This technical report demonstrates how SQL-driven data extraction and Power BI visualization can be used to analyze pizza sales performance effectively. The dashboard provides valuable insights into customer behavior, product performance, and seasonal demand trends.

The findings support strategic decision-making in pricing, promotions, inventory management, and product optimization. Continuous monitoring using this dashboard can further enhance operational and financial outcomes.

10. References and Appendices

References

SQL Database Documentation
Microsoft Power BI Documentation
Data Visualization Best Practices
Appendices

Press enter or click to view image in full size
