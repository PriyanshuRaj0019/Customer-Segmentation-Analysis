# Customer Segmentation Analysis using K-Means Clustering and Power BI

## Overview

This project focuses on customer segmentation using K-Means Clustering to identify distinct customer groups based on annual income and spending behavior. The objective is to uncover meaningful customer segments that can support targeted marketing strategies and business decision-making.

## Objectives

- Analyze customer demographics and spending patterns
- Perform customer segmentation using K-Means Clustering
- Visualize customer groups and behavioral differences
- Generate actionable business insights through dashboards

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Power BI

## Dataset Features

- CustomerID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1-100)

## Methodology

### 1. Data Preprocessing
- Loaded and explored customer data
- Checked for missing values
- Selected relevant features for clustering
- Standardized numerical variables

### 2. Clustering
- Applied K-Means Clustering
- Used the Elbow Method to determine the optimal number of clusters
- Assigned cluster labels to customers

### 3. Visualization
- Customer distribution by cluster
- Income vs Spending Score scatter plot
- Cluster summary analysis
- Interactive Power BI dashboard

## Dashboard Components

- Total Customers KPI
- Average Age KPI
- Average Income KPI
- Average Spending Score KPI
- Customer Distribution by Cluster
- Customer Segments Scatter Plot
- Cluster Summary Table
- Business Insights Section

## Key Insights

- Identified distinct customer groups based on purchasing behavior
- Discovered high-value customer segments
- Analyzed spending trends across clusters
- Generated insights useful for targeted marketing campaigns

## Project Structure

```text
Customer-Segmentation-Analysis/
│
├── customers_segments.csv
│
├──  customer_segmentation.ipynb
│  
├──  Customer_Segmentation.pbix
│
├──  dashboard.png
│   
├──  requirements.txt
│
└── README.md
```


## Results

The project successfully segmented customers into distinct groups using K-Means Clustering and presented the findings through an interactive Power BI dashboard, enabling better understanding of customer behavior and purchasing patterns.

## Author

Priyanshu Raj
