📊 Alt Mobility Customer Behavior Analysis
🛠 Project Overview
This project analyzes customer orders and payment behaviors for Alt Mobility using SQL, Python (pandas, matplotlib, seaborn), and data visualization techniques.

The goal is to uncover patterns such as repeat ordering, customer retention trends, payment issues, and to recommend strategies to improve customer experience and retention.

🧠 Approach and Methodology
1. Data Extraction
Connected to the SQLite database (alt_mobility_data.db).

Queried necessary tables such as customer_orders and payments.

Extracted key fields like order_id, customer_id, order_date, payment_status, and amount_paid.

2. Data Analysis with SQL
Order Status Analysis: Counted orders by their status.

Monthly Sales Analysis: Aggregated total sales amounts month-wise.

Repeat Customers: Identified customers with more than one order.

New Customers: Counted customers who placed their first order in each month.

Payment Status Analysis: Analyzed number of completed, failed, and pending payments.

Payment Failure Rate: Computed failure rate for each month.

Full Order Details Report: Merged orders and payment information for detailed reporting.

3. Data Cleaning and Processing
Converted dates into proper datetime formats.

Created new columns like order_month and cohort_month for cohort-based analysis.

Created new aggregated DataFrames for trends and retention patterns.

4. Visualizations
Created clear and clean graphs using matplotlib and seaborn:

Bar charts for payment status counts.

Line graphs for monthly sales trends.

Cohort heatmaps for customer retention.

Ensured every plot has proper titles, axis labels, and color palettes for readability.

5. Customer Retention (Cohort Analysis)
Measured retention rates over months after a customer's first order.

Visualized the trend of customer drop-off over time.

6. Key Findings
Found high payment failure and pending rates.

Identified a sharp decline in customer retention after the first month.

Observed clear customer segmentation based on ordering frequency.

