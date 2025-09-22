# Real Estate Market & Sales Analytics Dashboard

This repository contains a dynamic and insightful **Power BI** dashboard designed for the strategic analysis of the real estate market. The project leverages a robust technical architecture to process and visualize over **10,000 records**, transforming raw sales data into actionable business intelligence.

[cite_start]The dashboard provides a multi-dimensional view of market trends, asset performance, and investment potential using a historical dataset that extends back to 1992[cite: 42]. It is designed for stakeholders, investors, and analysts to identify opportunities, evaluate assets, and make informed, data-driven decisions.

---

## 📊 Technical Architecture & Stack

This project was built using a modern data stack to ensure performance, scalability, and real-time insights.

* **Data Source**: **Google BigQuery**, providing a high-performance, serverless data warehouse capable of handling large-scale datasets.
* **ETL Process**: An advanced, **real-time ETL (Extract, Transform, Load)** pipeline was developed to ensure data is consistently refreshed and accurate.
* **Data Transformation & Modeling**: **Power Query** was extensively used for data shaping, cleaning, and complex transformations before loading it into the data model.
* **Analytical Engine**: The core of the business logic is driven by **Advanced DAX Formulas**. These measures calculate complex Key Performance Indicators (KPIs), such as Year-over-Year growth, price-per-square-meter ratios, and financial yields.
* **Reporting & Visualization**: **Microsoft Power BI** was used to create interactive, descriptive reports and intuitive visualizations.

---

## 🔑 Key Features & Analytical Insights

The dashboard is structured around several key analytical areas, allowing for a comprehensive market overview.

### Market & Sales Performance

* [cite_start]**Regional Dominance Analysis**: Identifies high-value markets by visualizing total sales volume, highlighting that **Zealand** leads with **95bn** in sales [cite: 20, 87][cite_start], followed by **Jutland** with **81bn**[cite: 20, 88].
* [cite_start]**Year-over-Year (YOY) Growth Tracking**: Uncovers market momentum by analyzing sales type performance, revealing a **+0.29 positive growth in auction sales** [cite: 21, 55, 76] [cite_start]while family sales have seen a sharp **-0.75 decline**[cite: 70, 77].
* [cite_start]**Recent Performance Metrics**: Displays the most recent sales activity, showing **77 units sold** in the latest year and quarter [cite: 31, 46][cite_start], generating around **13bn** in value[cite: 31, 59].

### Property Valuation & Pricing

* [cite_start]**Price-per-SQM Analysis**: Offers nuanced valuation insights, showing that **Zealand** has the highest average price-per-sqm at **20.85K** [cite: 23, 118] [cite_start]and that **townhouses** command the highest cost-per-sqm among all property types at **28.7K**[cite: 25, 179].
* [cite_start]**Negotiation Trend Analysis**: The dashboard shows that offer and purchase prices remain closely aligned across all house types, indicating a stable negotiation trend in the market[cite: 30, 130].

### Investment & Financial Analysis

* [cite_start]**Yield & Profitability**: Assesses investment potential by comparing financial indicators across property types, identifying that **farms** deliver the highest average yield at **4.6%**[cite: 28, 153].
* [cite_start]**Interest Rate Insights**: Tracks financial conditions, noting that interest rates are slightly lower for **Villas (1.8%)** [cite: 40, 156] [cite_start]and **Summerhouses (1.4%)** [cite: 40, 173] [cite_start]compared to Farms (2.1%)[cite: 40, 151].
* [cite_start]**Key Price Influencers**: Leverages advanced analytics to identify that property age is a significant driver of purchase price[cite: 29, 102].

---

## 👨‍💻 Author

* [cite_start]**Aryan Singh** [cite: 1]
