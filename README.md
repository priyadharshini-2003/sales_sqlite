# sales_sqlite
Sales Data Analysis with SQLite and Python
Objective:
The goal of this project is to analyze a simple sales dataset stored in an SQLite database. The task includes running SQL queries to extract sales summaries such as total quantity sold and revenue per product, and visualizing the results in a bar chart using Python libraries like pandas and matplotlib.
_____________________________________________________________________________________________________________________________________________________________________________________________________________________
Tools and Libraries Used:
SQLite: A lightweight, serverless database used to store the sales dataset.
Python:
sqlite3: For connecting to and querying the SQLite database.
pandas: For data manipulation and loading query results into DataFrames.
matplotlib: For visualizing the results as a bar chart.
____________________________________________________________________________________________________________________________________________________________________________________________________________________
Dataset:
The dataset consists of the following columns:
id: Unique identifier for each sale (integer).
product: Name of the product sold (text).
quantity: Quantity of the product sold (integer).
price: Price per unit of the product (float).
Sample data includes sales records for products like Apple, Banana, Orange, etc.
____________________________________________________________________________________________________________________________________________________________________________________________________________________
#Steps:
1. Create SQLite Database:
The sales data is stored in an SQLite database file (sales_data.db). This database contains a table named sales, which stores product sales transactions, including the product name, quantity sold, and price per unit.
2. Query the Data:
A SQL query is used to calculate:
Total Quantity Sold: The sum of all quantities sold per product.
Revenue: The total revenue for each product (calculated by multiplying quantity by price).
The query result is then loaded into a pandas DataFrame for easy manipulation and display.
3. Visualize the Data:
Using matplotlib, the revenue per product is visualized as a bar chart. The chart displays products on the x-axis and their corresponding revenue on the y-axis.
4. Save and Display the Chart:
The chart is saved as an image file (sales_revenue_chart.png) and also displayed within the script.
_________________________________________________________________________________________________________________________________________________________________________________________________________________
 #Use case
Make informed decisions about inventory management (e.g., stocking more of high-performing products).
Identify opportunities for promotions or discounts on low-selling items.
Forecast demand based on historical sales performance.
 __________________________________________________________________________________________________________________________________________________________________________________________________________________
Conclusion:
This task demonstrates how to interact with an SQLite database, perform simple data aggregation with SQL, and visualize the results using Python. This is a fundamental workflow for analyzing structured data and generating insights in a business context.
