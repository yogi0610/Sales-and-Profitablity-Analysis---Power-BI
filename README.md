# Sales-and-Profitablity-Analysis---Power-BI

## About the Project
I created this Power BI project to understand how sales and profit are performing across different products, countries, and business segments. I used Microsoft's **Financial Sample Dataset** and built an interactive dashboard where the user can easily check the overall sales, profit, profit margin, units sold, and product performance.

## Dataset
For this project, I used the **Microsoft Financial Sample Dataset**.
The dataset contains details such as:
* Country
* Segment
* Product
* Units Sold
* Sales
* Profit
* Date
* Discounts
* Sale Price
* Manufacturing Price

## Tools I Used
* Power BI
* Power Query
* DAX

## What I Did
First, I imported the dataset into Power BI and checked the data using Power Query.
I checked the column data types, empty values, and data quality before using the data for visualization.
Then I created some DAX measures for the main calculations.

### DAX Measures
1. Total Sales:
Total Sales = SUM(financials[Sales])

2. Total Profit:
Total Profit = SUM(financials[Profit])

3. Total Units Sold:
Total Units Sold = SUM(financials[Units Sold])

4. Profit Margin:
Profit Margin =
DIVIDE(
    SUM(financials[Profit]),
    SUM(financials[Sales]),
    0
)

## Dashboard
In the dashboard, I created:

* Total Sales
* Total Profit
* Profit Margin
* Total Units Sold
* Profit Trend Over Time
* Profit by Country
* Profit by Product
* Profit by Segment
* Profit by Product Treemap
* Top 5 Products by Profit
* Country filter

The dashboard can be filtered using the Country slicer, which makes it easier to explore the data based on different countries.


## What I Learned

Through this project, I learned how to:

* Import and check data in Power BI
* Use Power Query for basic data preparation
* Create DAX measures
* Create different Power BI charts
* Use slicers for filtering
* Build an interactive dashboard
* Analyze sales and profit from business data



