
# Ecommerce Company Sales Analysis-Dashboard

### Dashboard Link : https://app.powerbi.com/view?r=eyJrIjoiOTZiZWFiZjktNDllZC00ZGUyLWIyZDgtODBiYWY4MTdjMjIxIiwidCI6ImRmODY3OWNkLWE4MGUtNDVkOC05OWFjLWM4M2VkN2ZmOTVhMCJ9


## Dashboard Overview

This dashboard provides a comprehensive analysis of sales data for an ecommerce company from the years 2012 to 2015. It utilizes three CSV files: Orders, Returns, and People, to analyze various aspects of sales performance including total sales, quantity sold, average delivery days, return orders, sales by segment and market, top customers, top profitable and loss-making products, and sales by region.


## Data Sources

- Orders.csv: Contains information about orders placed, including  order date, customer ID, product ID, quantity, sales amount, delivery date, and region.
- Returns.csv: Contains data on returned orders, including return date, order ID, return reason, and return quantity.
- People.csv: Provides details about customers, including customer ID, name, email, and market segment.


### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : Clean the data by removing null values, unwanted columns and errors.
- Step 5 : when It was observed that in none of the columns errors & empty values were present load the data.


## KPIS Performed

- Total Sales: Sum of sales amount from 2012 to 2015.
- Quantity:Total quantity of products sold during the specified period.
- Average Delivery Days: Average number of days taken to deliver orders to customers.
- Return Orders: Number of orders that were returned by customers.
- Sales by Segment:Sum of sales amount categorized by market segment (e.g., retail, wholesale).
- Sales by Market:Sum of sales amount categorized by market (e.g., North America, Europe).
- Top 10 Customers: List of top 10 customers based on their total purchase amount.
- Top 5 Profit Products: List of top 5 most profitable products based on sales revenue.
- Top 5 Loss Products: List of top 5 products with the highest return rates, resulting in loss.
- Sales by Region: Sum of sales amount categorized by geographical region.


## Snapshot of Dashboard 

![Screenshot 2024-04-22 001540](https://github.com/Laasikayasalapu0105/Ecommerce-Company-Sales-Analysis/assets/167681389/ee782b39-df6b-44db-ba99-3eb01d620ee3)

           
## Insights and Recommendations

- The dashboard reveals insights into the company's sales performance across different segments, markets, and regions.

- It highlights top-performing customers and products, which can inform targeted marketing and sales strategies.

- The analysis of return orders and loss-making products provides valuable insights into areas for improvement in product quality, customer service, or marketing strategies.

- Understanding sales performance by region can help optimize inventory management and distribution strategies to meet demand more effectively.
  

## Conclusion:

This sales analysis dashboard provides actionable insights derived from comprehensive data analysis, enabling the ecommerce company to make informed decisions to improve sales performance and customer satisfaction.
