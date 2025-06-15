# 🧾 Task 7: Basic Sales Summary using Python & SQLite

## 📌 Objective
Use SQL inside Python to extract basic sales information like total quantity sold and total revenue, and visualize it using a simple bar chart.

## 🧰 Tools Used
- Python
  - sqlite3
  - pandas
  - matplotlib
- SQLite (via Python — no extra setup)

## 🗂️ Dataset
A small SQLite database named `sales_data.db` containing a single table called `sales` with the following columns:
- `product` (TEXT)
- `quantity` (INTEGER)
- `price` (REAL)

## ✅ What I Did
1. Created a SQLite database `sales_data.db` with sample sales data.
2. Wrote an SQL query to calculate:
   - Total quantity sold per product
   - Total revenue per product (`quantity * price`)
3. Used Python (`sqlite3`) to run the query.
4. Loaded results into a pandas DataFrame.
5. Printed the summary to the console.
6. Plotted a bar chart using matplotlib to show revenue by product.

## 📊 Output
The output includes:
- Console print of the summary table
- A bar chart saved as `sales_chart.png`


