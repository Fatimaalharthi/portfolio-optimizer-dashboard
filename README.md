# Business Performance Dashboard

## Project Overview

This project presents an interactive business performance dashboard developed to analyze retail sales data and provide a structured view of operational performance. The objective of the dashboard is to organize transactional information into clear and interpretable insights that support understanding of revenue behavior, profitability trends, and performance differences across business segments.

The dashboard combines key performance indicators with interactive visualizations to offer both a high-level summary and detailed analytical perspectives. Users can evaluate overall business activity, observe performance trends over time, and explore how product categories and geographic regions contribute to financial outcomes. The design prioritizes clarity, consistency, and ease of interpretation to ensure the analysis remains accessible to both technical and non-technical audiences.

---

## Data Source

The analysis is based on the **Sample Superstore dataset**, a publicly available dataset commonly used for business intelligence and analytics practice. The dataset represents simulated retail transactions and includes detailed information about orders, sales revenue, profit values, product categories, customer segments, and regional markets.

Dataset source:  
[Sample Superstore Dataset – Kaggle](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)

The dataset structure enables performance evaluation across time, categories, and regions using transactional financial metrics such as sales and profit.

---

## Steps & Methodology

The project began with connecting and reviewing the dataset in Google Looker Studio to confirm correct data types and aggregation behavior. Key performance indicators were defined to summarize business outcomes, including total sales, total profit, profit margin, total orders, and average order value.

A clear visual hierarchy guided the dashboard design. Summary indicators are presented at the top to provide an immediate overview, followed by a time-series visualization showing performance trends over time. Additional charts analyze results by product category and region to help explain differences in performance. A scatter visualization was included to explore the relationship between sales and profitability at the sub-category level. A detailed transaction table allows users to view the underlying records supporting the analysis.

Interactive filters were added to enable exploration of results by region, category, and date range, allowing users to adjust the analysis according to specific interests or questions.

---

## Dashboard Overview

<img src="images/dashboard overview.png" width="900">

---

## Key Insights

The dashboard highlights several observable patterns within the dataset. Technology products tend to show stronger profitability compared to other categories, while regional performance varies across markets. The analysis also shows that higher sales volumes do not always correspond to higher profit margins, suggesting differences in cost structure or discounting behavior across products.

These observations demonstrate how visual analytics can help identify performance patterns and support further business investigation.

---

## Live Dashboard Link

The interactive dashboard can be accessed through the following link:

**Live Dashboard:**  
[(https://lookerstudio.google.com/s/iWrjxy-Ce8g)]

## Assumptions & Limitations

The dataset represents simulated retail operations and therefore does not include external business factors such as operational costs, logistics expenses, or market conditions. Profit values reflect transactional profitability rather than complete financial accounting measures. Additionally, the analysis assumes consistent data quality across regions and time periods.
