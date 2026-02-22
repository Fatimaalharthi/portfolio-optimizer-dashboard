# Business Performance Dashboard

## Project Overview

This project presents an interactive business performance dashboard designed to analyze retail sales operations and profitability using transactional data. The objective of the dashboard is to transform raw business records into meaningful insights that support data-driven decision-making and provide a clear understanding of organizational performance.

The dashboard delivers an executive-level view of key financial and operational metrics by combining summarized performance indicators with interactive visual analysis. It allows stakeholders to evaluate revenue trends, profitability patterns, and operational performance across product categories and geographic regions. The design emphasizes clarity, accessibility, and structured storytelling so that insights can be easily interpreted by both technical and non-technical users.

---

### Dashboard Overview

<img src="images/dashboard overview.png" width="900">

---

## Data Source

The analysis is based on the **Sample Superstore dataset**, a publicly available dataset commonly used for business intelligence and analytics practice. The dataset simulates retail transaction data and contains detailed information related to orders, sales revenue, profit performance, product categories, customer segments, and regional markets.

The dataset includes order-level transactional records with associated financial metrics such as sales and profit, enabling realistic evaluation of business performance over time. Its structure supports the development of performance indicators and comparative analysis across regions and product segments.

The dataset contains:

- Order dates and transaction records  
- Sales revenue and profit values  
- Product categories and sub-categories  
- Regional market performance  
- Customer and order-level information  

This structure allows realistic business performance analysis and KPI development.

---

## Steps & Methodology

The project followed a structured analytical workflow beginning with data preparation and validation within Google Looker Studio. Data fields were reviewed to ensure appropriate data types and aggregation behavior, allowing accurate calculation of business metrics.

Key performance indicators were then defined to represent organizational outcomes, including total sales, total profit, profit margin, total orders, and average order value. These indicators were positioned at the top of the dashboard to provide an immediate overview of business health.

A visual hierarchy was applied to guide interpretation. A time-series visualization was used to highlight performance trends over time, followed by category and regional analyses to explain performance drivers. A scatter visualization was implemented to examine the relationship between sales and profitability at a more detailed level, helping identify areas where high revenue does not necessarily produce strong margins. A detailed transaction table was included to provide transparency and allow validation of the underlying data.

Interactive filters were incorporated to enable users to dynamically explore results by region, category, and time period, enhancing analytical flexibility and usability.

## Key Insights

The analysis reveals several important observations. Technology products demonstrate stronger profitability compared to other categories, while regional performance differences suggest variations in operational efficiency and market behavior. The dashboard also highlights instances where products with high sales volumes generate relatively lower profit margins, indicating potential opportunities for pricing optimization or cost management improvements.

These insights illustrate how interactive dashboards can support strategic planning by connecting high-level performance indicators with detailed operational analysis.


---

## Live Dashboard Link

The interactive dashboard can be accessed through the following link:

**Live Dashboard:**  
[(https://lookerstudio.google.com/s/iWrjxy-Ce8g)]

## Assumptions & Limitations

The dataset represents simulated retail operations and therefore does not include external business factors such as operational costs, logistics expenses, or market conditions. Profit values reflect transactional profitability rather than complete financial accounting measures. Additionally, the analysis assumes consistent data quality across regions and time periods.
