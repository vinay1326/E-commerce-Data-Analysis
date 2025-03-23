Data Analytics Project: E-commerce Dataset
📌 Introduction
This project is a self-initiated endeavor utilizing skills in SQL, Python, Data Visualization, and Tableau to analyze an e-commerce dataset. The data used is sourced from public datasets (e-commerce dataset by Olist) on Kaggle, stored as an SQLite database.

Through this project, I aim to showcase my proficiency in data cleaning, analysis, and visualization by extracting meaningful insights and presenting them through an interactive Tableau dashboard.

✅ Thank you for viewing, and I welcome any suggestions for improvement!

📊 Dataset Overview
The dataset contains commercial transaction data from an e-commerce company in Brazil, including customer, product, and order details. The SQLite database consists of 11 tables:

customers: Customer information.

geolocation: Geographical coordinates for customer locations.

leads_closed: Closed leads data.

leads_qualified: Qualified leads data.

order_items: Details of items in each order.

order_payments: Payment information.

order_reviews: Customer reviews.

orders: Order-level details, including dates.

product_category_name_translation: Product categories translated to English.

products: Product-level details.

sellers: Seller information.

Data Analysis Process
The project follows the 5 phases of the Data Analysis Process:

1. Ask
Identify the business problem and define clear objectives.

Questions addressed:

Which products sell the most?

Which states have the highest sales?

What are the sales trends by year?

What insights can we extract from RFM segmentation?

2. Prepare
Loaded the dataset into SQLite using Python.

Reviewed the database schema and relationship between tables.

3. Process
Data Cleaning:

Handled NULL values in order_delivered_date by replacing them with values from order_estimated_delivery_date using COALESCE() in SQL.

Identified and retained potential outliers after visual inspection.

Feature Engineering:

Extracted year from order_date to analyze trends over time.

4. Analyze
Top 10 Best-Selling Products:

health_beauty

watches_gifts

bed_bath_table

sports_leisure

computers_accessories

furniture_decor

housewares

cool_stuff

auto

garden_tools

Top 10 States by Sales:

SP (São Paulo)

RJ (Rio de Janeiro)

MG (Minas Gerais)

RS (Rio Grande do Sul)

PR (Paraná)

SC (Santa Catarina)

BA (Bahia)

GO (Goiás)

DF (Distrito Federal)

PE (Pernambuco)

RFM Segmentation Insights:

Top Segment: "Should Not Lose" – customers with high-value purchases and positive reviews, but inactive for a while. Strategy: Re-engagement campaigns.

Champion Customers: Highly valuable and consistent customers.

No customers fall under the "Need Special Attention" segment, indicating a healthy customer base with good review scores.

5. Share
Created a Tableau Dashboard for interactive visualization:

Sales by product category.

Sales by state.

Yearly trends.

RFM segmentation insights.

Used box plots to visualize outliers and distribution patterns.

🛠️ Technologies Used
SQL: Data extraction, cleaning, and transformation.

Python: Data manipulation and analysis.

Pandas & Matplotlib: Data processing and visualization.

Tableau: Interactive dashboard creation.

SQLite: Database management.

🚀 Key Takeaways
The health_beauty category is the highest-selling product category.

São Paulo (SP) has the highest sales in Brazil.

RFM segmentation highlights the importance of re-engagement strategies for high-value but inactive customers.

Tableau dashboard offers an intuitive and dynamic presentation of the insights.

💡 Future Improvements
Enhance the dashboard with interactive filters for deeper exploration.

Implement predictive modeling to forecast future sales.

Perform sentiment analysis on customer reviews for better customer insights.

Explore time series analysis for sales trends forecasting.
