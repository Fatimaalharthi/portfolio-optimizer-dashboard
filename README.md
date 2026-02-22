# Business Performance Dashboard

## Project Overview

This project explores business performance using an interactive dashboard built on retail sales transaction data. The goal was to organize raw operational data into a format that makes performance easier to understand and explore through visual analysis.

The dashboard focuses on providing a clear overview of revenue and profitability while allowing users to examine how results differ across product categories and regions. Instead of presenting isolated charts, the dashboard was designed to guide users from a high-level summary toward more detailed analysis, helping them understand both overall outcomes and the factors influencing performance.

---

## Data Source

The analysis is based on the **Sample Superstore dataset**, a publicly available retail dataset. The dataset contains order-level transaction records including sales values, profit, product categories, customer segments, order dates, and regional markets.

Dataset source:  
[Sample Superstore Dataset – Kaggle](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)

The structure of the dataset makes it suitable for analyzing performance over time and comparing outcomes across business dimensions using financial metrics such as sales and profit.

---

## Steps & Methodology

The dataset was connected to Google Looker Studio, where fields were reviewed to ensure correct data types and aggregation behavior. Key performance indicators were then defined to summarize overall activity, including total sales, total profit, profit margin, total orders, and average order value.

The dashboard design follows a structured analytical approach. Summary metrics are presented first to provide context, followed by a time-series visualization showing how performance evolves over time. Additional charts analyze results by product category and region to help explain variations in performance. A scatter visualization compares sales and profit at the sub-category level, allowing relationships between revenue and profitability to be explored. A detailed transaction table is included to provide transparency and allow inspection of the underlying data behind the visual summaries.

Interactive filters enable users to adjust the analysis by region, category, and time period, making the dashboard flexible and exploratory.

---

## Dashboard Overview

<img src="images/dashboard overview.png" width="900">

---

## Key Insights

The analysis highlights several observable patterns. Technology products tend to generate stronger profitability compared to other categories, while performance varies across regions. The dashboard also shows that higher sales volumes do not always correspond to higher profit margins, suggesting differences in pricing or discount behavior across product groups.

These observations demonstrate how visual analysis can help identify patterns within transactional data and support further business investigation.

---

## Live Dashboard Link

The interactive dashboard can be accessed [here](https://lookerstudio.google.com/s/iWrjxy-Ce8g)

## Assumptions & Limitations

The dataset represents example retail transaction data and does not reflect real organizational operations. Profit values represent transaction-level results only and do not include additional operational costs such as logistics, staffing, or marketing expenses. The analysis assumes consistent data quality across all records and time periods.
