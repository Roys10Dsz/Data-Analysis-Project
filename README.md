# AdventureWorks: Sales & Customer Analytics Power BI Report

## Project Overview
This project is an in-depth analysis of the AdventureWorks sales data, visualized through an interactive, multi-page Power BI report. The goal was to move beyond simple reporting and uncover actionable insights into sales performance, product profitability, and customer behavior to inform strategic business decisions.

## Problem Statement
The AdventureWorks management team needed a clear and dynamic way to answer key business questions, including:
* What are the primary drivers of revenue and what are the sales trends over time?
* Which product categories and subcategories are the most profitable?
* Who are our most valuable customers and what are their purchasing patterns?
* How does sales performance vary across different geographic regions?

## Tools & Technologies
* **Database**: Microsoft SQL Server
* **Data Transformation & Querying**: T-SQL
* **Data Modeling & Analysis**: DAX (Data Analysis Expressions)
* **Data Visualization**: Power BI Desktop

## Process & Methodology

### 1. Data Extraction & Transformation (SQL)
I connected to the SQL Server database and wrote a comprehensive T-SQL query to join multiple tables, including sales orders, product details, customer information, and sales territories. This created a single, clean, and structured dataset ready for analysis, ensuring efficiency by performing complex joins at the database level rather than in Power BI.

### 2. Data Modeling & DAX Measures (Power BI)
In Power BI, I developed a robust data model and created several key DAX measures to enable deep analysis. These measures went beyond simple aggregations and included:
* `Total Revenue` & `Total Orders`
* `Average Order Value (AOV)`
* Time-intelligence measures like `Year-to-Date Sales (YTD)` and `Prior Year Sales (PYS)` to track performance against historical data.

### 3. Report Design & Visualization (Power BI)
I designed a multi-page interactive report with a focus on user experience and visual storytelling. The report includes:
* **Executive KPI Overview**: A high-level summary of key performance indicators with trend analysis and geographical sales distribution.
* **Product Deep-Dive**: Utilizes a decomposition tree and a detailed matrix to analyze product performance across categories and subcategories.
* **Customer Analysis**: Employs a scatter plot to segment customers based on revenue and order frequency, helping to identify VIP clients.

The design incorporates a professional color palette, consistent formatting with shadows and rounded borders for a modern look, and intuitive slicers for dynamic data exploration.

## Key Insights from the report
* **Top Performers**: The "Bikes" category is the primary driver of revenue, with specific models outperforming others significantly.
* **Customer Segmentation**: A key segment of high-frequency, high-value customers was identified, suggesting an opportunity for a targeted loyalty program.
* **Regional Performance**: The report highlighted that the Pacific sales region is underperforming compared to others, indicating a need for further investigation or strategic intervention.

## Report Preview
Page 1: Executive KPI Overview
<img width="1325" height="741" alt="image" src="https://github.com/user-attachments/assets/be9e064f-b296-4950-999d-705c8a780ce3" />

Page 2: Product Deep Dive
<img width="1324" height="742" alt="image" src="https://github.com/user-attachments/assets/d6c8202a-0888-442e-8bb3-b90de74d8879" />

Page 3: Customer Analysis
<img width="1324" height="741" alt="image" src="https://github.com/user-attachments/assets/35e31c56-3814-4ff6-a178-aa7fb1a6cd35" />


