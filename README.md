# DSA3050A-Advanced-PowerBI-Exam-Supply-chain-managment

# Supply Chain & Revenue Analytics Dashboard
**DataCo Global Operations Performance Analysis**

##  Student Information
* **Name:** Angela Irungu
* **Admission Number:** 669289
* **Course Code:** DSA 3050A 
* **Class:** SS 2026 

##  Project Overview
This project is a comprehensive Business Intelligence solution designed to analyze DataCo’s smart supply chain operations.The dashboard provides a multi-dimensional view of global sales, profitability, and delivery logistics to help stakeholders identify risks and optimize performance.

##  Problem Statement
DataCo Global faces significant operational challenges, specifically regarding shipping efficiency.The primary goal of this analysis is to identify geographic and operational bottlenecks causing high "Late Delivery" rates and to evaluate the profitability of different customer segments and product categories.

## 📊 Dataset Description
The analysis utilizes the **DataCo Smart Supply Chain** dataset.
* **Transactional Volume:** 180,000 rows of data.
* **Key Metrics:** Includes Sales, Profit, Shipping Days, and Order Status.
* **Scope:** Global coverage including 5 Markets and 3 Customer Segments.

##  Tools Used
* **Power BI Desktop:** For data modeling and visualization.
* **Power Query:** For data cleaning and ETL processes.
* **DAX (Data Analysis Expressions):** For advanced analytical measures.
* **GitHub:** For project documentation and version control.
##  Steps Followed
1. **Data Acquisition:** Selected a dataset rich enough for relational modeling and time intelligence.
2.  **Data Cleaning:** Used Power Query to address duplicates, fix data types, and standardize category names.
3.  **Data Modeling:** Established a **Star Schema** with a central Fact table and Dimension tables (Product, Geography, and Calendar).
4. **DAX Engineering:** Created 8+ mandatory measures for KPIs, time intelligence, and operational risk.
5.  **Dashboard Design:** Developed a three-page interactive report focusing on Executive, Operational, and Product insights.
## Dashboard Features
* **Executive Overview:** High-level KPI cards for Total Sales (**$36.78M**) and Total Profit (**$3.97M**).
* **Operational Performance:** A specialized Matrix visual with conditional formatting to highlight regional logistics risk.
* **Product Analytics:** Treemaps and Scatter Charts to analyze category dominance and profit-to-sales correlations.

##  Key DAX Measures
* **Total Sales:** `$36,784,735.01`
* **Late Delivery %:** Global average of `0.55 (55%)`
* **Average Shipping Days:** `3.50 Days`
* **Order Count:** `66,000 (66K)`

##  Key Insights
* **Regional Risk:** **Armenia** was identified as a critical bottleneck with a **1.00 (100%)** late delivery rate.
* **Shipping Inefficiency:** **First Class shipping** tiers consistently show the highest delay rates, nearing a **1.0** late delivery metric.
* **Market Revenue:** The **Europe** market is the top performer, contributing **$11M** to total sales.
* **Segment Dominance:** The **Consumer segment** drives the majority of revenue, accounting for **$19.1M (51.91%)**.

## Conclusion
The implemented Star Schema and advanced DAX measures provide a scalable and reproducible BI solution. By addressing the identified logistics bottlenecks in specific high-risk regions, DataCo can significantly improve customer satisfaction and operational margins.
