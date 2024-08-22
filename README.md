# CustomerSegmentation
Introduction
This project implements Recency, Frequency, and Monetary (RFM) analysis to segment customers based on their purchasing behavior. The goal is to identify customer segments that can be targeted for marketing campaigns, loyalty programs, or personalized offers.
Data Overview
The dataset used in this project consists of customer transaction records. It includes the following columns:

CustomerID: Unique identifier for each customer.
InvoiceDate: Date of the transaction.
InvoiceNo: Unique invoice number.
Quantity: Quantity of items purchased.
UnitPrice: Price per item.
TotalPrice: Total price for the transaction (Quantity × UnitPrice).
RFM Methodology
RFM analysis categorizes customers based on:

Recency: How recently a customer made a purchase.
Frequency: How often a customer makes a purchase.
Monetary: How much money a customer spends.
Customers are scored and segmented into different groups based on their RFM values, allowing businesses to target specific customer segments.

Implementation
The project involves the following steps:

Data Cleaning: Handling missing values and correcting data types.
RFM Calculation: Calculating Recency, Frequency, and Monetary values for each customer.
Scoring: Assigning scores (1-5) to each RFM component.
Segmentation: Creating customer segments based on their RFM scores.
Visualization: Plotting distributions and segment characteristics.
Results and Analysis
RFM Scores: The dataset was segmented into multiple groups based on RFM scores.
Customer Segments: Analysis of customer segments revealed actionable insights for marketing strategies.
Visualizations: Plots and charts illustrating the distribution of RFM scores and customer segments.
Conclusion
This RFM analysis helps in identifying valuable customer segments. The insights derived from this analysis can be utilized for targeted marketing campaigns, improving customer retention, and maximizing revenue.

References
RFM Analysis: A Proven Marketing Model for Customer Segmentation
Customer Segmentation Using RFM Analysis in Python
