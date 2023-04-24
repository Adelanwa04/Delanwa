
# Sales Analysis Visualization

# by Taiwo Adelanwa

# Dataset
Sales analytics is the practice of generating insights from sales data, trends, and metrics to set targets and forecast future sales performance. Sales analysis is mining your data to evaluate the performance of your sales team against its goals. It provides insights about the top performing and underperforming products/services, the problems in selling and market opportunities, sales forecasting, and sales activities that generate revenue.

This dataset include 186848 rows with 6 columns data entries;

- Order ID - An Order ID is the number system that Amazon uses exclusively to keep track of orders. Each order receives its own Order ID that will not be duplicated. This number can be useful to the seller when attempting to find out certain details about an order such as shipment date or status.
- Product - The product that have been sold.
- Quantity Ordered - Ordered Quantity is the total item quantity ordered in the initial order (without any changes).
- Price Each - The price of each products.
- Order Date - This is the date the customer is requesting the order be shipped.
- Purchase Address - The purchase order is prepared by the buyer, often through a purchasing department. The purchase order, or PO, usually includes a PO number, which is useful in matching shipments with purchases; a shipping date; billing address; shipping address; and the request items, quantities

I did some wrangling which included:

- Dropping missing values
- Converting quantity ordered and price each to interger
- Calculating sales from quantity ordered and price each
- Extracting month from order date and converting to interger
- Extracting year from order date and converting to interger
- Extracting city from purchase address


What was the best Year for sales? How much was earned that Year? What was the best month for sales? How much was earned that month? What City had the highest number of sales? What time should we display adverstisement to maximize likelihood of customer's buying product? What products are most often sold together? What product sold the most? Why do you think it sold the most?

# Summary of Findings
I was able discover different trends and uncover insights when i analysed Sales dataset.The quaterly total sales analysis showed that we made considerable amount of sales in the 4th quater with over 11M with the 2nd quater looking great too with over 9M in sales. Uncovering more insights in our analysis, the monthly sales showed we made the most sales in December with over 4M, October and April was also impressive with us making over 3M.

As we have our products in almost all cities in United States, an analysis was done to show the city sales distribution which showed that San Francisco is the top of the pile making over 8M. Los Angeles , New York City, Boston and Atlanta also made sales of over 5M, 4M, 3M and 2M respectively. Strategies in advertisement can maximize the likelihood of customers buying our product. I was also able to get more insight from this analysis, we made more sales at 12pm and 7pm and this the best time to display advertisement for our products.

NB: Numbers associated with sales are in '$'

# Limitation
This analysis was limited as more analysis can be done to understand sales in each state and their differences in relation to time of advertisement for our products. The quaterly and monthly analysis of sales per state. The difference in prefernce of each products by state.

 
