Introduction:
	I have built a simple, single-sheet dashboard for ShopNest, a leading departmental store in Portugal’s e-commerce market. The platform connects small businesses from various regions across Portugal, streamlining operations through a single point of contact.
	This dashboard provides an in-depth and interactive analysis of delayed orders, frequently used payment types, seasonal sales patterns, monthly comparisons between delayed and on-time orders, revenue analysis, state-wise sales, top product category sales, and the best and worst reviewed products. It also highlights key performance indicators (KPIs) such as total revenue, total price, total sales, and average order value (AOV). Let us Breakdown the dashboard and understand the analysis that went into each visual chart.

Menu Bars:
	Screenshot attached below is the menu bars that is Delayed, Payment, Product, State Wise Sales and Revenue Analysis. On-click on each button, it displays corresponding visualizations. 
 
Filters:
	Below are the filters that are available in filter menu at the left side of the dashboard. These filters are used in the dashboard.
Back Button:
	Back button here is used to navigate back to home page from any of the other page. 
 
Product category:	It contains the entire product category used in the departmental store.
Quarter and Year: It contains the year and quarter based breakdown.
Type of Delivery: Delay or On Time, sort’s charts and KPI based on selected condition
Payment Type: It contains payment type details like credit card, debit card vouchers etc. and it does not affect the other charts except Product rating analysis chart as other charts has no relationship with payment mode.
Review Score: It contains reviews from 1 to 5 and sorts data based on the review.
These filters acts as slicers in the dashboard and on select of any data, it dynamically changes the view of each chart.
KPI – Key Performance Index/Indicators:
 
Above are the some of the KPI’s used in the dashboard just to highlight the overall performance of ShopNest store.
Total Price: Total Price calculated as SUM of price of all products.
Total Revenue: Sum of (Price + Freight Value) of all products.
Total Sales: Count of number of Orders Placed.
AOV (Average Order Value): Total Revenue/Total Sales.
Top Categories by Total Price:
Question Statement: Identify and visually represent the top 10 products by total price
Visualization:
 
Explanation: health_beauty is the product category with highest price with 1.26M and garden_tools with least 0.49M. Bar chart has been used to represent this data.
Delayed Order Analysis:
Question Statement: Determine the number of delayed orders in each category. An order is considered delayed if the actual delivery date is later than the estimated delivery date.
Visualization:
 
Explanation:  This column chart represents the entire product category with the most number of delayed orders. For ex: bed_bath_table has the highest number of delayed orders with count of 5122, security_and_services has only two orders, and both are delayed.
Monthly Comparison of Delayed and On-time Orders:
Question: Create a dynamic visual that compares the number of delayed orders to the number of orders received earlier for each month. Utilize the drill through cross-report feature to provide a detailed analysis of late and on-time deliveries.
Visualization
 

Explanation: This chart shows the comparison between Delay and On-time orders month wise and as mentioned in question, to show the drill drown of quarters, I have used it as tooltip.
 

Payment Method Analysis:
Question: Analyse the most frequently used payment methods by customers using a visually appealing representation, such as a pie chart or other suitable visuals.
Visualization:
 
Explanation: As mentioned in question, I have used Pie chart to represent the frequently used payment mode. There was some 3 rows mentioned not_defined, to avoid the discrepancies of the data, I have changed it to offline. 

Product Rating Analysis:
Question: Determine the top 10 highest-rated products and the bottom 10 lowest-rated products using a bar or column chart.
Visualization: I have first taken the average review score and then compared it with Product category (question was asked for each product but as there is a code for each product and not actual product name, I have taken product category only to represent data).
 
Explanation:
State Wise Sales Analysis:
Question: Identify and visually represent states with high and low sales, providing a clear understanding of regional sales performance.
Visualization:
 
Explanation: I have used map to represent state wise total sales and also bar chart and line chart to represent Total Sales over Total Revenue for each state. Sao Paulo state has the highest sales and revenue
Seasonal Sales Pattern:
Question: Investigate and visualize any seasonal patterns (Quarterly) or trends in sales data over the course of the year.
Visualization:
 
Explanation: I have used line and column chart to represent this analysis and it is evident that across 3 years, Qtr. 2 has been high performing quarter and even sales are increased during this period.
Revenue Analysis:
Question: Determine the total revenue generated by ShopNest Store and analyse how it changes over time (Yearly). Represent this information through suitable visuals to highlight trends and patterns.
Visualization:
 
Explanation: I have used stacked area chart to represent revenue, price and total sales details and we are seeing that sales was less for all the 2016 Qtr. 1 and correspondingly Revenue was less. 
 
For 2018 Qtr. 1, total sales was 18499, correspondingly Revenue is also high, and again it decreases gradually for second and third Qtr. respectively.

