🔹 Project Overview

A mini data analysis project that connects Python with SQLite, runs SQL queries to summarize sales, and visualizes the results with a bar chart.

🔹 Tech Stack

Python 3

SQLite (sqlite3)
Pandas
Matplotlib

🔹 What I Did

Created a small SQLite database sales_data.db.

Wrote SQL queries to calculate total quantity sold and revenue per product.

Loaded query results into Pandas DataFrame.

Generated a sales summary chart with Matplotlib.

🔹 Key SQL Query
SELECT product, 
       SUM(quantity) AS total_qty, 
       SUM(quantity * price) AS revenue
FROM sales
GROUP BY product;

🔹 Output

Sample Table

   product  total_qty  revenue
0   Apples         15     37.5
1  Bananas         20     24.0
2  Oranges        10     30.0


Sales Chart Output  

 

