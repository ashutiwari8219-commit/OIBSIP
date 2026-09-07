# EDA on Retail Sales Data

## Objective
Performed exploratory data analysis on a retail sales dataset to uncover 
sales trends, customer demographics, and product category performance.

## Dataset
Retail sales dataset with transaction-level data (Date, Customer ID, 
Gender, Age, Product Category, Quantity, Price, Total Amount).

## Tools Used
Python, pandas, matplotlib, seaborn, Jupyter Notebook (VS Code)

## Key Findings
- Electronics generated the highest total revenue (~$157K), closely followed 
  by Clothing (~$156K), with Beauty trailing behind (~$143K) — the top two 
  categories are nearly tied, suggesting both deserve continued investment.
- Monthly sales are highly volatile rather than seasonal: May was the peak 
  month (~$53K) while September dipped sharply (~$23K), and there's a steep 
  drop-off in January 2024 (likely incomplete data for that month rather 
  than a genuine trend).
- The customer base is nearly gender-balanced (51% Female, 49% Male) with 
  a fairly even age spread from 20-64, though customers in their early 20s 
  and early 60s appear slightly more frequently than other age groups.
- Price per Unit is strongly correlated with Total Amount (0.85), while 
  Quantity has only a moderate correlation (0.37) — indicating that 
  higher-priced items, not bulk purchases, drive most revenue.
- Gender-category breakdown shows Males slightly outspend Females in 
  Electronics, while Females slightly outspend Males in Beauty and Clothing.

## Business Recommendations
1. Since Price per Unit (not Quantity) drives revenue, focus promotional 
   efforts on upselling higher-value items within each category rather 
   than volume-discount bundles.
2. Investigate the September dip and May spike (e.g., check for seasonal 
   demand, marketing campaigns, or stock issues) to replicate what worked 
   in May and prevent low-performing months like September.
3. Since Electronics slightly favors Male customers and Beauty/Clothing 
   slightly favor Female customers, tailor marketing creative and email 
   segments by gender-category affinity to improve campaign relevance.