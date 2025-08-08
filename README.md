# Sales-Dashboard

### Dashboard Link : https://app.powerbi.com/groups/e849017f-7ec0-4756-847f-14eea533b642/reports/23de0a97-74b7-4d3d-9138-31a7f02a1d14/d36f604b168f4ae18ff5?experience=power-bi

## Problem Statement

Analyze store sales performance and promotional effectiveness using the provided dataset, which includes customer details, product information, promotions, and transaction records. The goals are:

Evaluate total and net sales across products, cities, and time.

Assess promotion impact on sales: Which promotions drive the most sales? Which products are most affected?

Identify top customers and products by sales volume and net revenue.

Enable interactive slicing by time, product, location, etc., to support business decisions.

### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : Inspect and Clean the Data Using Power Query Editor for:

  Removing trailing spaces and fixing column header names.
  Setting correct data types (Date, Numeric, Text).
  Removing unnecessary columns and ensuring consistency..
- Step 5 : Define Relationships
  Link tables in the Model view:
  Transactions ↔ Customers (CustomerID),
  Transactions ↔ Products (Product ID),
  Transactions ↔ Promotions (PromotionID).
- Step 6 : Build Visualizations:- 
  Product Sales Analysis: Bar and pie charts to show total
  sales  by product line and top-selling products.
  Geographical Insights: Visualizations of sales by city and state.
  Promotion Analysis: Charts comparing sales under various    promotions (Summer Sale, Diwali, etc.).
  Time Series: Line chart showing net sales trend over months/years.
  Top Contributors: Tables listing top customers and top products.

- Step 7 : Add Slicers for Interactivity
  Filters for Date, Product Line, City, Promotion type to  enable dynamic exploration
- Step 8 : Format and Refine
  Improve aesthetics: Titles, axis labels, data colors.
  Add tooltips and context details.
- Step 9 : Publish or Share
  Save and optionally publish the report to the Power BI Service. 

# Snapshot of Dashboard (Power BI Service)

## Overview
#### Dashboard provides a comprehensive overview of sales data analysis across various dimensions:

* Geographical Distribution: A map titled "Sales by City" displays sales concentration in major Indian cities such as Delhi, Mumbai, Bangalore, Chennai, Kolkata, and others, each represented by blue circles, indicating relative sales activity per city.

* Order Volume: The center panel reports a total of 3,510 orders, giving a snapshot of overall sales activity.

* Promotion Insights: The bar chart "Average of Discount by Promotion Categories" shows that the highest average discounts were given during "Weekend Flash Sale" (23K), followed by "Clearance Sale" (18K), "Summer Sale" (7K), "New Year Special" (3K), and "Festive Diwali" (0K), indicating the effectiveness and frequency of various promotional efforts.

* Profitability: The "Profit VS Net Sales" scatterplot displays a strong positive linear relationship, showing that increases in profit generally correspond with increases in net sales. Each point likely represents a sales instance or period.

* Sales Trend Analysis: The "Sales Trends By Period" chart (2020–2024) visualizes net sales over time, with regular peaks. Labeled spikes (e.g., 0.54M, 0.49M, 0.41M, 0.43M, 0.65M) suggest notable sales surges during certain periods, potentially aligning with promotional events or seasonal trends.

![Snap_1](https://github.com/Rssingh123/Sales-Data-Analysis/blob/d3cbeb6098ddfed3ceb12fc56de4dde6c717923f/Sales%20Snap1.png)

## Top/Bottom 5 Analysis  

#### Dashboard provides a detailed analysis of product performance based on three key metrics: Sales, Quantity Sold, and Profit. The data is split into two main categories for each metric: the Top 5 and Bottom 5 products. Here is a breakdown:

Top 5 Products By Sales:
  1. Apple iPhone 14: Leading in sales with 21.4M.
  2. Apple MacBook Air: 19.6M sales.
  3. Sony Bravia 55" TV: 19.4M sales.
  4. Samsung Galaxy S21: 15.3M sales.
  5. HP Pavilion Laptop: 14.4M sales.

  Insight: High-value electronics dominate the top sales positions.

Bottom 5 Products By Sales:
  1. Tupperware Lunch Box: 0.26M.
  2. L’Oreal Shampoo: 0.17M.
  3. Nivea Body Lotion: 0.08M.
  4. Dove Soap Pack: 0.08M.
  5. Colgate Toothpaste: 0.02M.

Insight: Everyday consumer goods have the lowest sales figures.

Top 5 Products By Quantity Sold:
  1. Apple iPhone 14: 281 units.
  2. Raymond Suit: 274 units.
  3. Fossil Smartwatch: 269 units.
  4. Zara Casual Shirt: 269 units.
  5. IFB Microwave Oven: 259 units.

Insight: Mix of electronics, apparel, and appliances in high demand by quantity.

Bottom 5 Products By Quantity Sold:
  1. Nivea Body Lotion: 219 units.
  2. Tupperware Lunch Box: 215 units.
  3. Milton Thermos Flask: 214 units.
  4. FabIndia Kurta: 210 units.
  5. Borosil Glass Set: 203 units.

Insight: Lower quantities sold in personal care and household items.

Top 5 Products By Profit:
  1. Apple iPhone 14: 2.14M profit.
  2. Apple MacBook Air: 1.96M profit.
  3. Sony Bravia 55" TV: 1.94M profit.
  4. Samsung Galaxy S21: 1.53M profit.
  5. HP Pavilion Laptop: 1.44M profit.

Insight: High-ticket consumer electronics are also the most profitable.

Bottom 5 Products By Profit:
 1. Tupperware Lunch Box: 26K.
 2. L’Oreal Shampoo: 17K.
 3. Nivea Body Lotion: 8K.
 4. Dove Soap Pack: 8K.
 5. Colgate Toothpaste: 2K.

Insight: Low-value daily essentials yield the lowest profits.      

![Snap_2](https://github.com/Rssingh123/Sales-Data-Analysis/blob/d3cbeb6098ddfed3ceb12fc56de4dde6c717923f/Sales%20Snap2.png)

## Comparison Sales/Profit/Quantity Selected
#### dashboard provides a side-by-side comparison of sales performance over two different date ranges, with key business metrics summarized in bar charts. Here’s a detailed description of what you see:

Filters (Top Section)
Date Filter 1: Covers the period from 1/1/2020 to 12/26/2022.

Date Filter 2: Covers the period from 12/18/2021 to 12/31/2024.

Each filter is adjustable, allowing direct comparison of two different time frames.

KPI Comparison Charts (Bottom Section)
Three bar charts display the comparison between the two selected periods for the following metrics:

Total Sales

- Sales 1 (Purple Bar, Date Filter 1): 90M

- Sales 2 (Orange Bar, Date Filter 2): 62M

Insight: Sales are higher in the first period.

Total Profit

- Profit 1 (Purple Bar, Date Filter 1): 9.0M

- Profit 2 (Orange Bar, Date Filter 2): 6.2M

Insight: Profit aligns with higher sales in the first period.

Total Quantity Sold

- Quantity 1 (Purple Bar, Date Filter 1): 5.2K units

- Quantity 2 (Orange Bar, Date Filter 2): 3.7K units

Insight: More units sold during the first selected period.

 ![Snap_3](https://github.com/Rssingh123/Sales-Data-Analysis/blob/d3cbeb6098ddfed3ceb12fc56de4dde6c717923f/Sales%20Snap3.png)

 
## Edit Interaction
#### Dashboard presents a side-by-side comparison of core business metrics across two different date ranges, enabling users to quickly assess performance variation over time. Here's a detailed description:

Top Section: Date Filters
Date Filter 1 and Date Filter 2:

Both filters allow selection of a custom date range (default: 1/1/2020 to 1/1/2024).

Each date range is set using a slider and calendar picker.

This enables direct comparison between any two time periods of interest.

Middle and Bottom Sections: Key Metrics Visualization
Each metric is shown twice—once for each date filter—using clean, horizontal bar charts and numerical labels:

1. Total Sales
- Left Panel (Orange Bar): Represents Total Sales for Date Filter 1.

- Right Panel (Pink Bar): Represents Total Sales for Date Filter 2.

- Both show a value of 12.2M, indicating identical sales for the selected periods.

2. Total Profit
- Left Panel (Orange Bar): Shows Total Profit for Date Filter 1.

- Right Panel (Pink Bar): Shows Total Profit for Date Filter 2.

- Both have a value of 1.2M, signifying no change between periods.

3. Total Quantity Sold
- Left Panel (Orange Bar): Indicates Total Quantity Sold for Date Filter 1.

- Right Panel (Pink Bar): Indicates Total Quantity Sold for Date Filter 2.

- Both stand at 7.1K, again showing parity between the two periods.

Visual Design and Purpose
- Color Coding: Orange bars for Date Filter 1, pink for Date Filter 2, aiding clear side-by-side comparison.

- Consistency: Identical values across both periods for all metrics suggest that the same or very similar data ranges are selected, or business results have been steady.

- Intended Use: Great for high-level benchmarking, analyzing period-over-period changes, and presenting summary metrics in leadership or operational review meetings.
 
 ![Snap_4](https://github.com/Rssingh123/Sales-Data-Analysis/blob/d3cbeb6098ddfed3ceb12fc56de4dde6c717923f/Sales%20Snap4.png)
 
## Table Visual
#### Dashboard displays detailed, transactional-level sales data with interactive filtering capabilities at the top. Here’s a breakdown of what’s on screen:

Top Section: Interactive Filters

- Date 1: Dropdown to filter the table by a specific date or date range.

- Customer Name: Dropdown to filter by customer.

- Product Name: Dropdown to filter by product.

- Promotion Name: Dropdown to filter by promotion.

- All filters default to “All”, so all data is displayed unless a filter is applied.

Main Section: Data Table

- A scrollable table lists sales transactions by row, with each record including the following columns:

- CustomerID: Unique customer identifier.

- Order ID: Unique order transaction ID.

- Product ID: Identifier for the product sold.

- PromotionID: If applicable, the promotion linked to the transaction.

- Date: Date of the transaction, shown in day, date, and year format (e.g., “Thursday, January 30, 2020”).

- Discount: Value of any discount applied.

- Discount Percentage: Percent discount applied.

- Net Sales: Final sales amount after discount.

- Price Per Unit: Price for each unit sold.

- Profit: Profit earned on the transaction.

- Total Sales: Total sales value before discounts.

- Units Sold: Quantity of units in the transaction.

Features & Use Cases:

- Purpose: Enables users to drill down into granular sales activity, track individual orders, and analyze how discounts, promotions, or specific customers/products impact sales and profit.

- Interactive Analysis: Instantly filter the table by date, customer, product, or promotion to answer detailed business questions (e.g., “Which customers bought product P020 during Festive Diwali promotions?”).

- Summary & Auditing: Ideal for operational reporting, data export, or deeper analysis outside the dashboard.

Visual Style

- Clean, classic tabular format without charts/visuals, optimized for data review.

- Columns are clearly labeled for ease of reference.

- Scrollbar indicates a larger dataset viewable on demand.
 
![Snap_5](https://github.com/Rssingh123/Sales-Data-Analysis/blob/d3cbeb6098ddfed3ceb12fc56de4dde6c717923f/Sales%20Snap5.png)
