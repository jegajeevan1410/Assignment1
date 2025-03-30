# Assignment1
Customer Behaviour Analysis 
Project Overview: Customer Behavior Analysis Using SQL and Python
This project focuses on analyzing customer behavior for ShopEasy, an online retail business, using SQL (SQL Workbench) and Python (Jupyter Notebook). The goal is to uncover insights into customer engagement, purchase patterns, and marketing effectiveness to help improve conversion rates and customer retention.

🔹 Steps Followed in the Project
1️⃣ Data Collection & Preprocessing
The dataset consisted of multiple CSV files containing customer information, purchases, reviews, journey data, and engagement activities.

These files were loaded into SQL tables using Python (pandas & MySQL-connector).

Data Cleaning:

Removed duplicates and null values to ensure data consistency.

Merged tables using JOIN operations to create a unified dataset (merged_data).

2️⃣ Customer Journey & Purchase Behavior Analysis
Finding Customers Who Purchased Multiple Products

Used SQL queries to count distinct ProductID for each customer.

Identified customers who purchased more than one product.

Identifying Customers Who Did Not Purchase

Used a LEFT JOIN to find customers with no purchases but who interacted with products.

Finding Products Viewed but Not Purchased

Filtered Action = 'View' but with no corresponding Purchase.

3️⃣ Customer Engagement Insights
Drop-off Points in the Customer Journey

Analyzed customer actions at different stages (Homepage, ProductPage, Checkout) to find where customers disengage.

Common Actions Before Purchase

Identified the most frequent customer actions leading to successful purchases.

Average Duration per Stage

Calculated the average time spent by customers at different stages before buying.

4️⃣ Sales & Marketing Performance
Repeat vs. First-Time Buyers

Counted purchases per customer and categorized them as first-time buyers or repeat buyers.

Customer Retention Rate Calculation

Measured the percentage of returning customers over time.

Best Performing Products Per Region

Identified the highest-rated and most-reviewed products in each region.

Found top-selling products in different locations.

🔹 Tools & Technologies Used
SQL (SQL Workbench): Data storage, querying, and analysis.

Python (Jupyter Notebook): Automating SQL execution, data manipulation (pandas), and visualization.

Libraries: pandas, MySQL-connector, matplotlib (for visualization).

🔹 Key Takeaways & Business Insights
Understanding Drop-off Points helped optimize customer journeys by reducing abandonment.

Repeat vs. First-Time Buyer Analysis guided marketing strategies for retention.

Top Products per Region helped tailor promotions to specific demographics.

Customer Engagement Insights helped improve website experience and ad targeting.

Conclusion
This project successfully provided data-driven insights to help ShopEasy improve customer retention, boost conversions, and optimize marketing efforts. By leveraging SQL and Python together, we automated complex analysis and derived actionable business strategies. 
