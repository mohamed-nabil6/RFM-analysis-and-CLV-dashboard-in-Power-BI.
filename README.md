# Rfm analysis and Customer lifetime value

This project contains Power BI dashboards for RFM (Recency, Frequency, Monetary) Analysis and Customer Lifetime Value (CLV) analysis. These dashboards help businesses analyze customer behavior, segment customers, and understand their value over time.

## RFM Analysis Dashboard

### Overview
The RFM dashboard provides insights into customer segments based on their purchasing patterns. Key metrics include the number of customers, total sales, average recency value, average frequency value, and average monetary value.

### Key Metrics
- **Number of Customers**:
  - **18K**: This shows the total number of customers analyzed.

- **Total Sales**:
  - **29.36M**: This is the total sales amount from all customers.

- **Average Recency Value**:
  - **4.03K**: This represents the average recency score, indicating how recently customers made a purchase.

- **Quantity**:
  - **60K**: The total quantity of items sold.

- **Average Frequency Value**:
  - **1.49**: The average frequency score, showing how often customers purchase.

- **Average Monetary Value**:
  - **1.59K**: The average monetary score, representing the average amount spent by customers.

### Visualizations
1. **Total Sales by Monetary Score**:
   - A bar chart showing total sales categorized by monetary score (1 to 5).
   - Highest sales (19M) are associated with the highest monetary score (5).

2. **Total Tax by Monetary Score**:
   - A pie chart illustrating the tax amount contributed by different monetary score categories.
   - The largest segment (66.41%) is contributed by the highest monetary score (5).

3. **% Customer in Each Segment**:
   - A tree map displaying the percentage of customers in different segments.
   - Segments include New Customers, Promising, At Risk, Loyal, Champions, Hibernating, Lost Customers, and more.
   - New Customers form the largest segment (17.52%), followed by Promising (13.96%) and Cannot Lose Them (11.08%).

4. **Customer by Segment**:
   - A bar chart showing the number of customers in each segment.
   - The highest number of customers are in the New Customers segment (3.2K).

5. **Total Sales by Segment**:
   - A bar chart depicting total sales generated by each customer segment.
   - Champions segment contributes the highest sales (8.3M), followed by At Risk (7.3M) and Loyal (6.2M).

### Insights
- **High-Value Customers**: The highest monetary score customers contribute significantly to total sales and taxes.
- **Customer Distribution**: A significant portion of customers are new, promising, or at risk.
- **Segment Performance**: Champions, At Risk, and Loyal customers generate the most revenue.

### Conclusion
This RFM dashboard provides a comprehensive overview of customer segmentation and behavior, allowing businesses to identify high-value customers, understand the distribution of customer segments, and make data-driven decisions to enhance customer engagement and retention strategies.

## CLV Dashboard

### Overview
The CLV dashboard provides insights into the long-term value of customers, average revenue per user, average purchase frequency, and average customer lifespan.

### Key Metrics
- **Customer Lifetime Value (CLV)**:
  - **2.38K**: The average customer lifetime value, which represents the total revenue a business can reasonably expect from a customer throughout their relationship.

- **Average Revenue Per User (ARPU)**:
  - **1.59K**: This is the average revenue generated per user.

- **Average Purchase Value (APV)**:
  - **1.06K**: The average value of purchases made by customers.

- **Average Purchase Frequency (APF)**:
  - **1.50**: This indicates the average number of purchases made by customers.

- **Average Customer Lifespan (ACL)**:
  - **1.50**: The average duration (in years, months, or another unit) a customer continues to purchase from the business.

- **Total Sales**:
  - **29.36M**: The total sales amount from all customers.

### Filters
- **Year, Quarter, Month**: These filters allow users to drill down the data to specific periods for more granular analysis.

### Table
- **Month**: Lists months from 1 to 12.
- **Num of Orders**: The number of orders placed in each month.
- **Total Sales**: The total sales amount for each month.
- **Total Tax**: The total tax amount for each month.
- **Avg Purchase Frequency (APF)**: The average number of purchases per customer for each month.
- **Avg Purchase Value (APV)**: The average value of purchases made in each month.
- **Customer Lifetime Value (CLV)**: The lifetime value of customers for each month.

### Visualizations
1. **Customer Lifetime Value (CLV) by Month**:
   - A line chart showing the CLV trend over the months.
   - The CLV increases significantly towards the end of the year, reaching its peak in December (26).

2. **Churned by Month**:
   - A line chart showing the percentage of customers churned each month.
   - The churn rate is highest in April (1013%) and gradually decreases towards the end of the year, reaching its lowest in December (664%).

3. **ARPU by Month**:
   - A line chart displaying the ARPU trend over the months.
   - ARPU is relatively stable at the beginning of the year, dips in February (94), and then rises steadily, peaking in December (174).

### Insights
- **Customer Value Trends**: CLV increases over the months, indicating improved customer retention or increased spending by customers.
- **Churn Analysis**: The churn rate is high in the first half of the year and decreases in the latter half, suggesting better customer retention strategies or improved customer satisfaction.
- **Revenue Insights**: ARPU shows a steady increase, implying that the business is successfully generating more revenue per user over time.

### Conclusion
This CLV dashboard provides a comprehensive overview of customer value, purchasing behavior, and churn rates. It helps businesses identify trends, understand customer retention, and make informed decisions to optimize marketing strategies, improve customer engagement, and increase overall revenue.

### Explore the complete interactive dashboard by following this link :
- [RFM analysis Dashboard]((https://app.powerbi.com/view?r=eyJrIjoiNTRhMzU3N2MtOTIyNS00YzYzLTkxZDktMzFkYmRiNDhiYmUwIiwidCI6ImRmODY3OWNkLWE4MGUtNDVkOC05OWFjLWM4M2VkN2ZmOTVhMCJ9&pageName=1d9906c90e025c70baca) 
- [Customer lifetime value Dashboard]([(https://app.powerbi.com/view?r=eyJrIjoiNTRhMzU3N2MtOTIyNS00YzYzLTkxZDktMzFkYmRiNDhiYmUwIiwidCI6ImRmODY3OWNkLWE4MGUtNDVkOC05OWFjLWM4M2VkN2ZmOTVhMCJ9&pageName=2797b61c4a6a57ea4cd1)
