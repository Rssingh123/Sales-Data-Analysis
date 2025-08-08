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
  Save and optionally publish the report to the Power BI Service  for sharing with stakeholders.

# Snapshot of Dashboard (Power BI Service)

### Overview

![Snap_1](https://github.com/Rssingh123/Sales-Data-Analysis/blob/d3cbeb6098ddfed3ceb12fc56de4dde6c717923f/Sales%20Snap1.png)

### Top/Bottom 5 Analysis        

![Snap_2](https://github.com/Rssingh123/Sales-Data-Analysis/blob/d3cbeb6098ddfed3ceb12fc56de4dde6c717923f/Sales%20Snap2.png)

### Comparison Sales/Profit/Quantity Selected
 
 ![Snap_3](https://github.com/Rssingh123/Sales-Data-Analysis/blob/d3cbeb6098ddfed3ceb12fc56de4dde6c717923f/Sales%20Snap3.png)

 
 ### Edit Interaction
 
 ![Snap_4](https://github.com/Rssingh123/Sales-Data-Analysis/blob/d3cbeb6098ddfed3ceb12fc56de4dde6c717923f/Sales%20Snap4.png)
 
 ### Table Visual
 
![Snap_5](https://github.com/Rssingh123/Sales-Data-Analysis/blob/d3cbeb6098ddfed3ceb12fc56de4dde6c717923f/Sales%20Snap5.png)
