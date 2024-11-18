# Ecommerce Website 

E-commerce Website Sales and Performance Analysis
Prepared by: [Yousef Emad]
Date: [17/11/2024]

Executive Summary 📝
This report examines the e-commerce performance of a company headquartered in São Paulo, Brazil, over the past 2–3 years. The primary objectives were to analyze sales trends, understand customer demographics, and identify operational efficiencies. Using Power BI and MySQL Workbench, the findings offer insights into customer behavior, product demand, and geographical sales distribution to guide strategic decision-making for business growth.

Project Objectives and Scope 🎯
The analysis aimed to uncover trends and key performance indicators (KPIs) beneficial to stakeholders, including data analysts, marketing, and operations teams.

Objectives:
Tracking sales performance through KPIs like total revenue, average order value, and customer purchase frequency.
Analyzing customer demographics and segmentation to inform targeted marketing.
Identifying product demand patterns by category to support inventory management.
Assessing operational efficiency metrics, like delivery times and freight costs, to improve service delivery.
Scope:
The data covers approximately 2–3 years, focusing on general trends across various seasons without specific promotional events.

Data Sources and Preparation 📂
Data Sources:
Sales and Customer Databases: Order history, product categories, customer information, and payment types.
Web Analytics: Data on customer engagement and website traffic.
Data Preparation Steps:
Standardizing Location Names: Enhanced map readability in Power BI using lookup tables with state abbreviations and full names.
Categorizing Unclassified Products: Products without categories were labeled as "Others" to ensure data completeness.
Removing Invalid Payment Types: Excluded cancelled orders labeled “invalid” to maintain data quality.
Correcting Typos and Translations: Fixed misspellings and untranslated terms for consistency.
Eliminating Duplicates: Removed duplicate entries across datasets for accurate analysis.
Calculating State Distances: Created a custom distance table using MySQL for geographical insights.
Transition to MySQL for Performance: Leveraged MySQL for efficient processing and real-time updates in Power BI.
Key Metrics and Analytical Approach 📊
Key Metrics:
Customer Lifetime Value (CLV): Identifying long-term customer value.
Average Purchase Frequency: Gauging customer return rates.
Average Delivery Time: Assessing delivery efficiency.
Business Volume Metrics: Customer count, seller count, and total order value.
Analytical Approach:
Time-Series Analysis: To identify sales trends and peak periods.
Customer Segmentation: Based on location and purchasing habits.
Geographical Analysis: Examining the impact of distance from São Paulo on sales, freight costs, and delivery times.
Visualizations and Insights 📈
Sales Metrics:
Monthly Revenue and Average Revenue per Customer: Averaging $136 per customer, with seasonal sales peaks suggesting high-return advertising periods.
Product Category Demand: "Beauty and Health" emerged as the top category, guiding inventory and marketing strategies.
Customer Demographics:
Customer Location and Distance Impact: São Paulo dominates customer and seller locations. Sales taper off significantly in distant areas like the northern Amazon.
New vs. Returning Customers: 93.62% of customers are new, highlighting a need for improved retention strategies.
Payment Preferences: Credit cards dominate, suggesting potential for targeted promotions.
Operational Efficiency:
Delivery Performance: 92.13% on-time delivery; minor delays were primarily distance-related.
Freight Cost Analysis: Higher costs for distant locations underline the need for optimized logistics solutions.
Peak Activity and Customer Behavior:
Order Times: Peak activity occurs between 10 AM and 4–5 PM, presenting opportunities for time-targeted advertising.
Conclusion and Recommendations ✅
Recommendations:
Targeted Inventory and Marketing: Focus on high-demand categories like Beauty and Health during peak periods.
Credit Card Promotions: Offer discounts or rewards for credit card users to boost sales and retention.
Geographic Expansion: Consider regional warehouses to reduce delivery times and costs for distant customers.
Customer Retention Strategies: Launch loyalty programs and personalized marketing to improve customer retention.
Optimized Delivery Scheduling: Expand delivery capacity during peak order hours for timely service.
Appendix 📂
DAX Calculations: Includes sample formulas for CLV, average revenue per customer, and order frequency.
Data Transformation Documentation: Details on translations, MySQL queries, and data cleaning.
Additional Visualizations: Charts for geographical sales distribution, payment methods, and cart abandonment insights







