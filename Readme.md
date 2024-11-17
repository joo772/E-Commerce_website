# Ecommerce Website 

E-commerce Website Sales and Performance Analysis
Prepared by: [Yousef Emad]
Date: [17/11/2024]

Executive Summary
This report examines the e-commerce performance of a company headquartered in São Paulo, Brazil, over the past 2-3 years. The main objectives were to analyze sales trends, understand customer demographics, and identify operational efficiencies. Using Power BI and MySQL Workbench, the findings provide insights into customer behavior, product demand, and geographical sales distribution, guiding strategic decision-making for business growth.

Project Objectives and Scope
The analysis aimed to uncover trends and key performance indicators (KPIs) beneficial to stakeholders, including data analysts, marketing, and operations teams. Objectives included:

Tracking sales performance through KPIs like total revenue, average order value, and customer purchase frequency.
Analyzing customer demographics and segmentation to inform targeted marketing.
Identifying product demand patterns by category to support inventory management.
Assessing operational efficiency metrics, like delivery times and freight costs, to improve service delivery.
The data covers approximately 2-3 years, focusing on general trends across various seasons without specific promotional events.

Data Sources and Preparation

The analysis utilized data from:

Sales and Customer Databases: Datasets on order history, product categories, customer information, and payment types.
Web Analytics: Data on customer engagement and website traffic.
Data Preparation involved the following steps:

Standardizing Location Names: We used ChatGPT to create a lookup table with state abbreviations and full names, enhancing map readability in Power BI through VLOOKUP.

Categorizing Unclassified Products: Products without categories were labeled "Others," ensuring data completeness.

Removing Invalid Payment Types: Payment records from cancelled orders, labeled “invalid,” were excluded to maintain data quality.

Correcting Typos and Translations: Misspellings and untranslated terms like “polleto” were corrected for consistency.

Eliminating Duplicates Across Dataset: Duplicate entries in the geolocation table and across other tables were removed, ensuring streamlined data for accurate analysis.

Calculating State Distances: A custom distance table was created with ChatGPT's help, and MySQL was used to calculate distances, enhancing geographical insights.

Transition to MySQL for Performance: Given the dataset’s size, MySQL improved processing efficiency, allowing real-time updates in Power BI.

Key Metrics and Analytical Approach

Key metrics included:

Customer Lifetime Value (CLV): To identify long-term customer value.
Average Purchase Frequency: To gauge customer return rates.
Average Delivery Time: To assess delivery efficiency.
Customer Count, Seller Count, and Total Order Value: Offering a complete view of business volume.
Our analytical approach involved:

Time-Series Analysis: To spot sales trends and peak periods.
Customer Segmentation: Based on location and purchasing habits.
Geographical Analysis: Examining how distance from São Paulo affects sales, freight costs, and delivery times.
Visualizations and Insights

Sales Metrics:

Monthly Revenue and Average Revenue per Customer: Averaging $136 per customer, with seasonal sales peaks suggesting high-return advertising periods.
Product Category Demand: "Beauty and Health" is the top category, indicating strong interest in personal care products, which could guide inventory and marketing strategies.
Customer Demographics:

Customer Location and Distance Impact: São Paulo dominates customer and seller locations, with sales tapering off with increased distance, particularly in the northern Amazon area.
New vs. Returning Customers: 93.62% of customers are new, while 6.38% are repeat customers, indicating an opportunity to improve retention strategies.
Payment Preferences: Credit cards are the dominant payment method, suggesting potential for promotions tailored to credit card users.
Operational Efficiency:

Delivery Performance: 92.13% on-time delivery, with minor delays primarily due to distance. 99.36% of deliveries were completed, indicating reliable service.
Freight Cost Analysis: Freight costs increase with distance, highlighting the potential benefit of optimized logistics solutions for distant customers.
Peak Activity and Customer Behavior:

Peak Order Times: Orders peak between 10 AM and 4-5 PM, suggesting that advertising during these hours may boost conversions.
Conclusion and Recommendations

Based on the analysis, the following recommendations can enhance business growth and operational efficiency:

Targeted Inventory and Marketing for Beauty and Health Products: Given high demand, consider allocating more resources to this category, especially around peak sales periods.

Credit Card Promotions: With most customers using credit cards, offer discounts or rewards for credit card purchases to increase sales and retention.

Geographic Expansion and Logistics: Sales drop with distance from São Paulo. Regional warehouses in key locations may reduce delivery times and costs for distant customers.

Customer Retention Strategies: Implement loyalty programs and personalized marketing to turn new customers into repeat buyers.

Optimized Delivery Scheduling: Enhance delivery capacity during peak order hours (10 AM to 5 PM) to maintain timely service.

Appendix

DAX Calculations: Sample formulas for CLV, average revenue per customer, and order frequency.
Data Transformation Documentation: Details on translating categories, handling MySQL queries, and managing data transformations.
Additional Visualizations: Supporting charts include geographical sales distribution, payment methods, and cart abandonment insights.
This streamlined report should clearly convey your findings and insights, with all sections working cohesively for effective presentation and strategic recommendations. Let me know if you’d like any more adjustments!







