# Target_Case_Study
Target Business Case Study Using SQL

# Introduction
Target is a globally recognized brand and a leading retailer in the United States. Known for its commitment to providing exceptional value, innovation, and customer experience, Target remains a preferred shopping destination for millions worldwide. This case study delves into Target's operations in Brazil, focusing on the analysis of 100,000 orders placed between 2016 and 2018. The dataset provides a detailed view of various operational aspects, including order status, pricing, payment and freight performance, customer demographics, product attributes, and customer feedback.

# Tools & Technologies Used
Google BigQuery: For data analysis and querying.
# Datasets
The datasets used in this analysis include:

* customers.csv - Information about customers.
* sellers.csv - Data on sellers.
* order_items.csv - Product details for each order.
* geolocation.csv - Geographic information for customers.
* payments.csv - Payment method details.
* reviews.csv - Customer reviews on products.
* orders.csv - Order-level data (status, total price, etc.).
* products.csv - Product information (name, category, etc.).
# Basic Data Analysis
**Data Types**: The datasets contain various data types, including Int, Float, String, and Timestamp.
**Order Dates**: The data spans from September 2016 to October 2018, covering two years of sales.
**Customer Details**: The customers.csv table contains 96,000 unique customer records.
# Exploratory Data Analysis (EDA)
**Sales Growth**: There has been a 19% growth in sales from 2016 to 2018, signaling an upward trend in business performance.

**Order Patterns**: Analysis of customer order timings reveals that most orders are placed around midday, which can inform promotional and operational strategies.

**Geographical Insights**: The majority of orders originate from the following states: São Paulo (SP), Rio de Janeiro (RJ), and Minas Gerais (MG). These are key metropolitan areas, which indicates a higher concentration of customers in urban regions.

**Product Price Trends**: Comparing product costs from 2017 to 2018, there is a 20% increase in prices. This could reflect inflation or changes in product sourcing, and understanding this could help inform pricing strategies for the future.

**Shipping Costs**: The analysis indicates that certain states, such as Roraima (RR), Paraíba (PB), Rondônia (RO), Acre (AC), and Piauí (PI), have the highest average shipping costs. This insight can be valuable for logistics optimization and pricing adjustments based on geographic factors.

**Payment Preferences**: Customers show a clear preference for Credit Cards and UPI (Unified Payments Interface) as their primary payment methods. This insight can help tailor payment options, promotions, and marketing campaigns to better serve customer preferences.

# Actionable Insights
* Focus on Urban Areas for Targeted Marketing: Given the high concentration of orders from metropolitan states like SP, RJ, and MG, Target could consider enhancing marketing campaigns and regional promotions in these high-volume areas to drive further sales growth.

* Adjust Pricing Strategy: The 20% increase in product prices from 2017 to 2018 should be evaluated for its impact on customer purchasing behavior. A deeper analysis into the relationship between price increases and sales volume could help optimize pricing strategies moving forward.

* Optimize Shipping and Logistics: The high shipping costs in certain states (RR, PB, RO, AC, PI) suggest a need for targeted logistics optimization. It may be beneficial to explore regional partnerships or localized fulfillment centers to reduce shipping costs in these areas, improving both profit margins and customer satisfaction.

* Midday Promotions: Since most orders are placed around midday, Target could consider launching time-specific promotions or discounts to capitalize on peak order periods, potentially increasing conversion rates during this time frame.

* Payment Method Optimization: Given the preference for Credit Cards and UPI, Target should ensure these payment methods are prioritized and streamlined in the checkout process. Exploring further integration with popular UPI platforms could improve the overall payment experience for customers.

* Customer Retention & Engagement: With a substantial number of unique customers, understanding retention metrics and customer lifetime value would be beneficial. Target could explore personalized marketing strategies, loyalty programs, or product recommendations based on order patterns and customer demographics.

# Conclusion
This business case study has allowed us to dive deep into Target's operations in Brazil, uncovering key insights from over two years of sales data. By leveraging SQL queries, we observed notable trends in sales growth, customer preferences, and regional logistics challenges. The actionable insights derived from this analysis offer clear opportunities for Target to optimize its marketing, pricing, and logistics strategies. Moving forward, the insights gathered here can serve as a foundation for data-driven decision-making and continuous business improvement.
