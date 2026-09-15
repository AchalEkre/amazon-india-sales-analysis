# Amazon India Sales Analytics Dashboard

## Project Objective 

To analyze Amazon India e-commerce sales data and identify important sales trends across products, time periods, states, order statuses, and fulfilment methods using python and Power BI.

## Tools Used 
-Python
-Pandas
-Power BI
-DAX

## Dataset 

The project uses an Amazon India e-commerce sales dataset containing order, product, sales, fulfilment, customer location, and order status information.

## Data Cleaning

The dataset was cleaned and preapred using Python and Pandas.

The main cleaning steps included:

-Checked the dataset structure, columns, and data types.
-Checked missing values in important columns.
-Converted the 'Date' column into datetime format.
-Created 'Year', 'Month', 'Month_Number', and 'Day' columns from the Date column.
-Handled missing values in selected columns such as 'Currency', 'Amount', 'Courier Status', and shipping related fields.
-Investigated missing sales amounts and reviewed their relationship with order status.
-Checked the quantity ('Qty') distribution and reviewed zero-quantity records.
-Checked unique orders and order-level data.
-Prepared a cleaned dataset for further analysis and Power BI visualization.

## Analyisis Performed

The cleaned data was analyzed using Python and Pandas to understand sales performance.

The analysis included:

-Total sales analysis
-Sales by product category
-Monthly sales trend 
-Sales by state 
-Sales by fulfilment method 
-Top-selling SKUs
-B2B vs non-B2B sales analysis
-Total orders and quantity analysis
-Average Order Value (AOV)

These analyses helped identify the major sales categories, high-performing states, sales trends, and fulfilment patterns.

## Power BI Dashboard

An interactive Power BI dashboard was created to visualize Amazon sales performance.

### Key Performance Indicators

- Total Sales: 78.59M                                
- Total Orders: 120k
-Total Quantity: 116.649K
-Average Order Value: 652.88

### Dashboard Visualizations

-Sales by Category
-Monthly Sales Trend
-Top States by Sales
-Sales by Order Status
-Sales by Fulfilment

### Interactive Filters

-Month
-Category
-Fulfilment

## Key Insights

- **Set** was the highest-selling prodcut category.
- **April** recorded the highest monthly sales.
-**Maharashtra** was the top state by sales.
-**Amazon fulfilment** generated the majority of sales.
-The analysis provides an overview of sales performance across products, locations, time periods, order statuses, and fulfilment methods.

## Project Files

-[Python Analysis Notebook](DA_Project.ipynb)
-[Power BI Dashboard](Amazon_Sales_Dashboard.png)

