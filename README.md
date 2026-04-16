%%writefile README.md
# Customer Spending & Behaviour Analysis

## Overview
This project applies **K-Means Clustering** to group retail customers based on their shopping behaviour and spending patterns.

## Dataset
The dataset contains 10 customers with the following features:

| Column | Description |
|---|---|
| Cust_ID | Unique customer identifier |
| Name | Customer name |
| Avg_Mthly_Spend | Average monthly spending (₦) |
| No_Of_Visits | Number of store visits |
| Apparel_Items | Number of apparel items purchased |
| FnV_Items | Number of Fruits & Vegetables purchased |
| Staples_Items | Number of staple items purchased |

## Goal
Segment customers into groups to help the business understand:
- Who are the high-value customers?
- What do different customer groups buy?
- How can marketing be targeted per segment?

## Tools Used
- Python
- Jupyter Notebook
- Pandas
- Scikit-learn
- Matplotlib / Seaborn

## Technique
- Unsupervised Learning
- K-Means Clustering
