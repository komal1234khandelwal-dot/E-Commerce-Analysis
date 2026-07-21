# E-Commerce-Analysis


An end-to-end analysis of an e-commerce dataset (customers, orders, sales, products, payments, and delivery) using MySQL for querying and Python (pandas, matplotlib, seaborn) for visualization. The project covers loading raw CSVs into a database and then answering 15 business questions using SQL, from basic aggregations to window functions and retention analysis.

Project Structure

csv_to_sql.py — Loads CSVs into MySQL and builds the database
python_ecommerce.ipynb — Runs SQL queries and visualizes the results
README.md

What's Inside

csv_to_sql.py — Data Loading
Reads 6 CSV files (customers, orders, sales, products, delivery, payments) and loads them into a MySQL database. For each file, it replaces NaN values with SQL-compatible NULLs, cleans up column names, figures out the right SQL data type for each column automatically, creates the table if it doesn't exist, and inserts all the rows.
python_ecommerce.ipynb — Analysis and Visualization
Connects to the database and answers the  business questions

SQL techniques used include joins across multiple tables, group by aggregations, CTEs, window functions like dense rank and lag, moving averages, and correlation analysis using numpy.
