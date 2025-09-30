# data-analytics-TASK-6
📊 Sales Trend Analysis (Excel Version)
📌 Objective

The goal of this task is to analyze monthly revenue and order volume using Excel instead of SQL. The task demonstrates how to group sales data by month/year, apply aggregations, and visualize sales trends.

🛠 Tools Used

Microsoft Excel (PivotTables, Charts, Data Model for distinct count)

📂 Dataset

The dataset contains an orders table with the following columns:

order_date → Date of the order

amount → Revenue from the order

order_id → Unique ID for each order

product_id → Product reference

🔎 Steps Performed
1. Data Preparation

Added helper columns:

Year → Extracted using =YEAR(order_date)

Month → Extracted using =TEXT(order_date,"MMMM")

2. PivotTable Creation

Inserted a PivotTable from the dataset.

Rows: Year, Month

Values:

SUM(amount) → Monthly Revenue

COUNT DISTINCT(order_id) → Order Volume (using Data Model option in PivotTable)

3. Sorting & Filtering

Sorted data by Revenue and Volume to identify top-performing months.

Filtered for specific years to analyze yearly trends.

4. Visualization

Created Line Chart for revenue trends.

Created Column Chart for order volume comparison.

📈 Outcome

Identified monthly revenue trends and fluctuations.

Found peak sales months by revenue and volume.

Learned how to use aggregations in Excel (SUM, COUNT DISTINCT) to replicate SQL analysis.
