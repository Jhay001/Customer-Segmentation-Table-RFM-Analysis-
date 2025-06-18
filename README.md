# Customer Segmentation Table (RFM Analysis in Excel)

**Author:** Jibril Yahaya Jibril  
**Domain:** Manufacturing

**Tool:** Microsoft Excel  
**Status:** Completed


## Project Overview

This project applies **RFM (Recency, Frequency, Monetary)** analysis to a simulated B2B transaction dataset for a cement manufacturing company operating in Northern Nigeria.

The primary goal is to **segment customers** based on behavior—identifying top buyers, loyal clients, at-risk customers, and churned accounts. The final output supports informed decision-making around marketing, sales prioritization, and retention efforts.


## Dataset Features

The dataset was custom-generated to reflect realistic business transactions and includes:

| Columns             
|--------------------
| Transaction Date  
| Customer ID      
| Customer Name  
| Region    
| Product
| Transaction Amount


## Analysis Steps

1. **Data Cleaning**:  
   Ensured valid formats, removed duplicates, cleaned up text and numeric fields.

2. **RFM Metric Calculation**:
   - **Recency**: Days since last transaction
   - **Frequency**: Total number of transactions
   - **Monetary**: Sum of all transaction amounts

3. **RFM Scoring (1-5 scale)**:  
   Used Excel's `QUARTILE.INC()` to generate dynamic scoring ranges.

4. **Customer Segmentation**:  
   Assigned segment labels like `Champions`, `Loyal`, `At Risk`, `Lost`, etc., based on score patterns.

5. **Pivot Table Summary**:  
   Created visual summaries of customer distribution and revenue contribution by segment.


## Key Outcomes

- Identified **Champions** and **Loyal Customers** that account for majority revenue.
- Highlighted **At Risk** and **Lost** customers for potential reactivation campaigns.
- Created a lightweight but scalable Excel solution usable in real-world manufacturing contexts.


## Built With

- Microsoft Excel (Formulas, Pivot Tables, IF & LOOKUP functions)
- Manual RFM scoring logic
- Business domain logic inspired by real manufacturing distribution patterns

## License

This project is released for educational and portfolio use. Attribution appreciated if you fork or reference.
