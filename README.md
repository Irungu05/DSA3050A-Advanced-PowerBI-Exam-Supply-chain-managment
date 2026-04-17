# DSA3050A-Advanced-PowerBI-Exam-Supply-chain-managment

# Supply Chain & Revenue Analytics Dashboard
**DataCo Global Operations Performance Analysis**

## 👤 Student Information
* **Name:** Angela Irungu
* **Admission Number:** 669289
* [cite_start]**Course Code:** DSA 3050A [cite: 3]
* [cite_start]**Class:** SS 2026 [cite: 3]

##  Project Overview
[cite_start]This project is a comprehensive Business Intelligence solution designed to analyze DataCo’s smart supply chain operations[cite: 117]. [cite_start]The dashboard provides a multi-dimensional view of global sales, profitability, and delivery logistics to help stakeholders identify risks and optimize performance[cite: 31].

##  Problem Statement
[cite_start]DataCo Global faces significant operational challenges, specifically regarding shipping efficiency[cite: 154]. [cite_start]The primary goal of this analysis is to identify geographic and operational bottlenecks causing high "Late Delivery" rates and to evaluate the profitability of different customer segments and product categories[cite: 150].

## 📊 Dataset Description
[cite_start]The analysis utilizes the **DataCo Smart Supply Chain** dataset[cite: 235].
* [cite_start]**Transactional Volume:** 180,000 rows of data[cite: 36].
* [cite_start]**Key Metrics:** Includes Sales, Profit, Shipping Days, and Order Status[cite: 93, 94].
* **Scope:** Global coverage including 5 Markets and 3 Customer Segments.

##  Tools Used
* [cite_start]**Power BI Desktop:** For data modeling and visualization[cite: 117].
* [cite_start]**Power Query:** For data cleaning and ETL processes[cite: 48].
* [cite_start]**DAX (Data Analysis Expressions):** For advanced analytical measures[cite: 87].
* [cite_start]**GitHub:** For project documentation and version control[cite: 164].

##  Steps Followed
1.  [cite_start]**Data Acquisition:** Selected a dataset rich enough for relational modeling and time intelligence[cite: 34, 38].
2.  [cite_start]**Data Cleaning:** Used Power Query to address duplicates, fix data types, and standardize category names[cite: 55, 56, 57].
3.  [cite_start]**Data Modeling:** Established a **Star Schema** with a central Fact table and Dimension tables (Product, Geography, and Calendar)[cite: 66, 81].
4.  [cite_start]**DAX Engineering:** Created 8+ mandatory measures for KPIs, time intelligence, and operational risk[cite: 89, 90].
5.  [cite_start]**Dashboard Design:** Developed a three-page interactive report focusing on Executive, Operational, and Product insights[cite: 117].

## Dashboard Features
* **Executive Overview:** High-level KPI cards for Total Sales (**$36.78M**) and Total Profit (**$3.97M**).
* [cite_start]**Operational Performance:** A specialized Matrix visual with conditional formatting to highlight regional logistics risks[cite: 128].
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

## 🏁 Conclusion
[cite_start]The implemented Star Schema and advanced DAX measures provide a scalable and reproducible BI solution[cite: 82, 186]. [cite_start]By addressing the identified logistics bottlenecks in specific high-risk regions, DataCo can significantly improve customer satisfaction and operational margins[cite: 154].
