# **Order Analysis Dashboard: Insights on Payment Status and Trends**
## Raw Order Data Overview 
![image (1)](https://github.com/user-attachments/assets/e156153b-3081-472a-8329-f327738786d9)
## SALES ANALYSIS : ORDER STATUS
![image (2)](https://github.com/user-attachments/assets/de2a0e52-4dd1-4436-b4ef-1d11f9ef1196)
### The chart is a clustered column chart visualizing the "Sum of Total Due" for each order status.
- A significant portion of the total due amount remains unpaid. Specifically, "Due," "Past Due," “canceled,” and "Returned" orders collectively account for more than 25% of the total
- A substantial amount of revenue is tied up in unpaid orders, which could negatively impact cash flow.
-  Unpaid orders can lead to reduced profitability due to delayed revenue collection.
### Action Planning
- Implement strategies to improve collection rates, such as sending reminders, offering payment plans, or implementing stricter credit checks.
- Review and optimize customer service processes to minimize returns and cancellations.
## Top 3 Salespeople with Highest Returned Amount
![image (3)](https://github.com/user-attachments/assets/729f1977-f85f-4390-a626-2530f758042c)
This chart visualizes the "Sum of TotalDue" for returned orders by SalespersonID

It shows that SalespersonIDs 113, 128, 148, and 135 have the highest "Sum of Total Due" for returned orders.

The top 4 SalespersonIDs contribute significantly to the total amount of returned orders.

This suggests potential areas for improvement in sales processes or product quality for these salespeople
* The heatmap, when filtered by these top 4 SalespersonIDs, will provide further insights into the specific months or order statuses with the highest number of returned orders for each salesperson 
## Sales Analysis: Order Status Heatmap by Month
![image (4)](https://github.com/user-attachments/assets/f7c7d402-816a-4ad5-9ae2-04b5bf1e0108)

The chart displays the "Count of Total Due" for different order statuses (Cancelled, Due, Paid, Past Due, Returned) across various months.   

The "SalespersonID" slicer allows you to filter the data and view the heatmap for specific salespeople.   

![image (5)](https://github.com/user-attachments/assets/e376eaa2-6ac3-4178-89d4-bfe208752eab)
    
#### Filtering the heatmap by SalespersonID 113 and observing the count of returned orders reveals that this salesperson has a higher count compared to others, supporting the initial finding that SalespersonID 113 has the highest returned sales amount
## Timeline Filter for Order Status Analysis
To analyze order status trends over time, ensure your data includes a date column. Create a timeline filter in Excel using the slicer tool on the date column. This will generate a visual timeline with selectable date ranges, allowing you to dynamically analyze order status distributions across different time periods and identify seasonal trends or patterns in order status behavior.

![image (6)](https://github.com/user-attachments/assets/96b3fcda-539c-4622-99b8-b744e49d3204)

