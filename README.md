 Coffee Sales Data Analysis
📌 Project Overview
This project analyzes coffee sales data from a vending machine to extract actionable insights into customer purchasing behavior, sales trends, and product performance. The dataset spans March to July 2024 and includes details such as purchase date and time, payment method, coffee type, and sales amount.

Through Exploratory Data Analysis (EDA), we answer key business questions:

What are the most popular coffee types?

When are the busiest hours and days for sales?

How do sales vary across months?

Which products generate the most revenue?

What are customers' preferred payment methods?

The insights from this analysis can help with inventory planning, promotional strategies, and operational improvements, and also provide a foundation for future predictive modeling.

📂 Dataset
Source: Internal vending machine transaction logs

Period Covered: March 2024 – July 2024

Columns:

date – Date of purchase

datetime – Exact date and time of purchase

cash_type – Payment type (card or cash)

card – Customer card ID (anonymized)

money – Transaction amount

coffee_name – Coffee product purchased

🛠️ Technologies Used
Python (Pandas, NumPy, Matplotlib, Seaborn)

Jupyter Notebook for analysis and visualization

Excel (optional for validation and manual review)

📊 Key Steps in the Project
Data Cleaning

Removed unnecessary columns (e.g., card)

Handled missing values in card (cash transactions)

Converted date and datetime columns to datetime format

Standardized coffee_name entries

Created new features: hour, weekday, month

Exploratory Data Analysis (EDA)

Most popular coffee products

Hourly sales trends

Weekday sales patterns

Monthly sales trends

Revenue by product type

Payment method preferences

📈 Key Insights
Top Sellers: Americano with Milk and Latte dominate sales volume.

Revenue Leader: Latte generates the most revenue, indicating higher price per sale.

Peak Hours: Strong sales peaks at 10:00 AM and 7:00 PM.

Busiest Day: Tuesday records the highest number of transactions.

Monthly Trends: Significant sales surge in May; steady performance thereafter.

Payment Preferences: Over 92% of transactions are card-based.

📌 Conclusion
The analysis reveals clear patterns in customer preferences and purchasing behavior, enabling better decision-making for product stocking, promotional timing, and payment system optimization.

🔮 Future Scope
Implement time series forecasting to predict sales trends.

Integrate external factors like weather, events, and holidays.

Develop customer segmentation for targeted marketing.

Create real-time dashboards for monitoring sales performance.

📷 Visualizations
The project includes clear and concise charts for:

Product popularity

Hourly and weekly sales trends

Monthly growth patterns

Revenue contribution by product

Payment method distribution
