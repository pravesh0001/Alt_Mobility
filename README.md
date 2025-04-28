📊 Alt Mobility Customer Behavior Analysis
🛠 Project Overview
This project analyzes customer orders and payment behaviors for Alt Mobility using SQL, Python (pandas, matplotlib, seaborn), and data visualization techniques.

The goal is to uncover patterns such as:

Repeat ordering

Customer retention trends

Payment issues

and to recommend strategies to improve customer experience and retention.

🧠 Approach and Methodology
1. Data Extraction
Connected to the SQLite database (alt_mobility_data.db).

Queried necessary tables such as customer_orders and payments.

Extracted key fields like:

order_id

customer_id

order_date

payment_status

amount_paid

2. Data Analysis with SQL
Order Status Analysis: Counted orders by their status.

Monthly Sales Analysis: Aggregated total sales amounts month-wise.

Repeat Customers: Identified customers who placed more than one order.

New Customers: Counted new customers by the month of their first order.

Payment Status Analysis: Analyzed the number of completed, failed, and pending payments.

Payment Failure Rate: Calculated monthly payment failure rates.

Order Details Report: Merged order and payment data for detailed reporting.

3. Data Cleaning and Processing
Converted order_date fields to proper datetime formats.

Created new columns:

order_month (month of order)

cohort_month (month of first purchase)

Generated additional DataFrames to capture monthly trends and retention patterns.

4. Visualizations
Created clean and clear visualizations using matplotlib and seaborn:

📊 Bar charts for payment status counts.

📈 Line graphs for monthly sales trends.

🔥 Cohort heatmaps for customer retention analysis.

Ensured every plot had:

Proper titles

Labeled axes

Attractive and readable color palettes

5. Customer Retention (Cohort Analysis)
Measured how many customers made repeat purchases in subsequent months after their first order.

Visualized customer retention drop-off trends over time.

📌 Key Findings
High rates of payment failure and payment pending transactions were observed.

Sharp decline in customer retention after the first month.

Clear customer segmentation was visible based on order frequency.

Seasonal spikes in sales were observed during certain months.
