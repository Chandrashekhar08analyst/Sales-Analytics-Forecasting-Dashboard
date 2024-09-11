# Sales Analysis and Forecasting with Power BI

## Objective
This project is designed to leverage **data analysis techniques** and **time series forecasting** in **Power BI** to provide actionable insights and strategic recommendations for business growth. The interactive dashboard helps businesses track performance, understand customer behavior, and optimize sales strategies.

## Project Overview
The project analyzes sales data to create a comprehensive and interactive dashboard, offering:
- Insight into sales by category, region, and payment mode.
- Customer behavior trends and sales seasonality.
- Accurate **15-day sales forecasting** based on historical data, enabling businesses to anticipate future performance.

## Steps Involved:
1. **Data Import and Cleaning**:
   - Imported sales data from a CSV file.
   - Cleaned and processed the data: handled null values, replaced incorrect values, and adjusted data types to ensure accurate analysis.

2. **Dashboard Creation**:
   - **Bar Charts**: Visualized sales by category, subcategory, and shipping mode.
   - **Area Charts**: Compared monthly sales and profit trends across two years.
   - **Map Chart**: Displayed sales by state, using bubble size to represent sales volume and tooltips for profit.
   - **Pie Charts**: Illustrated sales by payment mode, segment, and region.
   - **Slicers**: Enabled interactive filtering by region and category for more granular analysis.
   - **KPIs**: Presented key metrics including total sales, total quantity sold, and total profit.

3. **DAX Calculations**:
   - Created a custom column for **average delivery days** using `DATEDIFF` to calculate the time between order date and shipping date.
   - Built a **DAX table** to support sales forecasting.

4. **Sales Forecasting**:
   - Implemented **15-day sales forecasting** using time series analysis, leveraging historical data to predict future sales trends.

## Key Insights:
- **Payment Mode**: 43% of customers prefer **Cash on Delivery**, followed by **Online Payment** (35%) and **Cards** (21%).
- **Top Region**: The **West** region is the highest-performing in terms of sales.
- **Sales Segment**: The **Consumer** segment contributes 48% of total sales, followed by the **Corporate** segment at 32%.
- **Top Categories**: The leading sales categories are **Office Supplies**, followed by **Technology** and **Furniture**.
- **Sales Trends**: Peak sales months are **September** and **December**, while the highest profits are recorded in **March**, **October**, and **December**.
- **Top State**: **California** leads in sales volume.

## Final Suggestion:
To increase sales in the next year, the business should focus on:
1. **Boosting Sales During High-Profit Months**: Since **March**, **October**, and **December** are high-profit months, targeted marketing campaigns during these months, especially for the **Consumer** segment, could enhance sales further.
2. **Expanding Online Payment Options**: With 35% of customers opting for online payments, improving online payment methods and providing incentives (e.g., discounts for digital transactions) could boost sales.
3. **Targeted Promotions in High-Sales Regions**: The **West** region has the highest sales. Implementing region-specific promotions or loyalty programs can maximize sales in this high-performing area.

## Conclusion:
This project demonstrates proficiency in **Power BI**, **DAX**, and **time series forecasting**. It delivers valuable insights into sales trends, customer behavior, and sales forecasting, helping businesses make informed decisions. The final suggestion provides actionable strategies for increasing sales in the coming year.

## Technology Used:
- **Power BI**: Data visualization, reporting, and interactive dashboard creation.
- **DAX (Data Analysis Expressions)**: Custom calculations and data manipulation.
- **Time Series Analysis and Forecasting**: Predictive analytics using historical sales data.
