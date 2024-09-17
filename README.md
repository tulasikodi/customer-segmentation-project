# customer-segmentation-project
# Customer Segmentation using RFM Analysis

This project focuses on segmenting customers based on their purchasing behavior using RFM (Recency, Frequency, Monetary) analysis. The dataset contains over 50,000 transactions, and the goal is to identify key customer segments for targeted marketing strategies.

## Process

1. **Data Cleaning**:
   - Handled missing values and removed duplicates.
   - Standardized date formats to ensure accurate recency calculation.

2. **RFM Calculation**:
   - **Recency**: Calculated the number of days since each customer’s last purchase.
   - **Frequency**: Counted the number of purchases made by each customer.
   - **Monetary**: Summed the total amount spent by each customer.

3. **Customer Segmentation**:
   - Customers were segmented into four categories:
     - **Top Customers**: Frequent buyers with high spending.
     - **Loyal Customers**: Consistent but moderate spenders.
     - **At-Risk Customers**: Declining frequency and spending.
     - **Immediate Attention**: Recent but low-frequency buyers.

## Key Insights
- **Top Customers** make up 17.76% of the customer base but generate the highest revenue.
- **Loyal Customers** form 31.23% of the base and demonstrate steady behavior.
- **At-Risk Customers** need targeted re-engagement strategies.
- **Immediate Attention Customers** have a high risk of churn and need quick interventions.

## Tools Used
- **Excel**: For data cleaning, RFM calculations, and basic analysis.
