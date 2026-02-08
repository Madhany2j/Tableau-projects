**Sales & Customer Insights Dashboard (Tableau)**
**📊 Project Overview**
This project is an end-to-end Tableau BI solution designed to analyze sales performance and customer behavior. It transforms raw transactional data into two distinct, interactive dashboards: one focused on Sales KPIs and the other on Customer Segment Analysis. The project follows professional BI workflows, including requirement gathering, mockup design, data modeling, and high-fidelity dashboard implementation.

**🚀 Key Features**
Executive KPI Tracking: Instant visibility into Total Sales, Profit, and Quantity, featuring Year-over-Year (YoY) growth comparisons and performance indicators.

Sales Dashboard: * Monthly sales trends comparing the current year against the previous year.

Sales distribution by product category and sub-category.

Regional performance analysis.

Customer Dashboard:  Customer segmentation analysis based on buying patterns.

Top customer rankings by sales and profit.

Histograms showing order frequency and customer distribution.

Interactive Design: * Custom Navigation: Sidebar navigation icons allowing seamless switching between dashboards.

Dynamic Filters: A collapsible "Show/Hide" filter panel to maximize screen real estate.

Cross-Filtering: Selecting a specific category or customer automatically updates all other visuals on the dashboard.

**🛠️ Technical Implementation**
Data Modeling: Implemented a Star Schema with a Fact table (Orders) linked to Dimension tables (Products, Locations, Customers).

Calculated Fields: Developed custom calculations for Current Year (CY) and Previous Year (PY) metrics, YoY growth percentages, and dynamic status symbols (arrows).

UI/UX Optimization: Utilized dashboard containers and custom background layers to create a modern, structured layout with a "Dark Mode" aesthetic.

Data Cleansing: Performed data type corrections (Geographic roles for regions) and handled null values in the data source layer.
