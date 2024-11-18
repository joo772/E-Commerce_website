# E-commerce Website Sales and Performance Analysis
**Prepared by:** Yousef Emad  
**Date:** 17/11/2024

---

## Executive Summary 📝
This report examines the e-commerce performance of a company headquartered in São Paulo, Brazil, over the past 2–3 years. The primary objectives were to:
- Analyze sales trends.
- Understand customer demographics.
- Identify operational efficiencies.

Using Power BI and MySQL Workbench, the findings offer insights into:
- Customer behavior.
- Product demand.
- Geographical sales distribution.

These insights guide strategic decision-making for business growth.

---

## Project Objectives and Scope 🎯

### Objectives:
- Tracking sales performance through KPIs like:
  - Total revenue.
  - Average order value.
  - Customer purchase frequency.
- Analyzing customer demographics and segmentation to inform targeted marketing.
- Identifying product demand patterns by category to support inventory management.
- Assessing operational efficiency metrics, such as:
  - Delivery times.
  - Freight costs.

### Scope:
- The data covers approximately 2–3 years.
- Focuses on general trends across various seasons without specific promotional events.

---

## Data Sources and Preparation 📂

### Data Sources:
- **Sales and Customer Databases:** Order history, product categories, customer information, and payment types.
- **Web Analytics:** Data on customer engagement and website traffic.

### Data Preparation Steps:
- Standardizing location names for enhanced map readability in Power BI using lookup tables.
- Categorizing unclassified products as "Others" to ensure data completeness.
- Removing invalid payment types (e.g., cancelled orders labeled “invalid”).
- Correcting typos and translations for consistency.
- Eliminating duplicates for accurate analysis.
- Calculating state distances using MySQL for geographical insights.
- Transitioning to MySQL for:
  - Efficient processing.
  - Real-time updates in Power BI.

---

## Key Metrics and Analytical Approach 📊

### Key Metrics:
- Customer Lifetime Value (CLV) to identify long-term customer value.
- Average purchase frequency to gauge customer return rates.
- Average delivery time to assess delivery efficiency.
- Business volume metrics:
  - Customer count.
  - Seller count.
  - Total order value.

### Analytical Approach:
- **Time-Series Analysis:** Identify sales trends and peak periods.
- **Customer Segmentation:** Based on location and purchasing habits.
- **Geographical Analysis:** Examine the impact of distance from São Paulo on:
  - Sales.
  - Freight costs.
  - Delivery times.

---

## Visualizations and Insights 📈

### Sales Metrics:
- **Monthly Revenue and Average Revenue per Customer:** Averaging $136 per customer.
- **Seasonal Sales Peaks:** Suggest high-return advertising periods.

### Product Category Demand:
- "Beauty and Health" emerged as the top category, guiding inventory and marketing strategies.

### Customer Demographics:
- **Customer Location and Distance Impact:** São Paulo dominates customer and seller locations. Sales taper off in distant areas like the northern Amazon.
- **New vs. Returning Customers:** 93.62% of customers are new, highlighting a need for improved retention strategies.
- **Payment Preferences:** Credit cards dominate, suggesting potential for targeted promotions.

### Operational Efficiency:
- **Delivery Performance:** 92.13% on-time delivery; minor delays were distance-related.
- **Freight Cost Analysis:** Higher costs for distant locations underline the need for optimized logistics solutions.

### Peak Activity and Customer Behavior:
- **Order Times:** Peak activity occurs between 10 AM and 4–5 PM, presenting opportunities for time-targeted advertising.

---

## Conclusion and Recommendations ✅

### Recommendations:
- **Targeted Inventory and Marketing:** Focus on high-demand categories like "Beauty and Health" during peak periods.
- **Credit Card Promotions:** Offer discounts or rewards for credit card users to boost sales and retention.
- **Geographic Expansion:** Consider regional warehouses to reduce delivery times and costs for distant customers.
- **Customer Retention Strategies:** Launch loyalty programs and personalized marketing to improve customer retention.
- **Optimized Delivery Scheduling:** Expand delivery capacity during peak order hours for timely service.

---

## Appendix 📂

- **DAX Calculations:** Includes sample formulas for CLV, average revenue per customer, and order frequency.
- **Data Transformation Documentation:** Details on translations, MySQL queries, and data cleaning.
- **Additional Visualizations:** Charts for geographical sales distribution, payment methods, and cart abandonment insights.

---

📧 **Contact**  
For more information, please contact:  
- **Email:** [Yousefe2152@gmail.com](mailto:Yousefe2152@gmail.com)  
- **LinkedIn:** [Yousef Emad Abdelrhman Elkhoudairy](https://www.linkedin.com/in/yousef-emad-abdelrhman-elkhoudairy)
