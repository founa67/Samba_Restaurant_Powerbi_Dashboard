# Samba Bar & Restaurant: A 15-Year Performance Dashboard

## Project Overview
This project involved designing and developing an end-to-end **Power BI business intelligence solution** for **Samba Bar & Restaurant**, a Kenya-based establishment. The interactive dashboard consolidates and analyzes **15 years of operational data (2009-2024)**, transforming raw, disparate data into a clear, strategic asset for management and executives.

The solution provides a 360-degree view of the business, enabling data-driven decision-making for sales strategy, menu optimization, staff performance, and geographic expansion.



## Business Objectives
-   **Empower Management:** Provide an at-a-glance overview of the company's health and long-term trajectory.
-   **Identify Trends:** Uncover patterns in sales, customer behavior, and operational efficiency over a 15-year period.
-   **Drive Strategy:** Deliver actionable insights to guide menu engineering, staff scheduling, branch performance analysis, and strategic planning.

## Technical Implementation

### Data Engineering & ETL (Power Query)
The project followed a robust **ETL (Extract, Transform, Load)** pipeline using **Power BI's Power Query** to integrate data from multiple sources:
-   **Sources:** Excel (`.xlsx`), JSON (`.json`), and consolidated CSV files.
-   **Key Transformations:**
    -   Data type conversion (e.g., `sale_date` to Date/Time).
    -   Column derivation (splitting datetime into separate Date and Time columns).
    -   Data structuring (flattening nested JSON).
    -   Removal of unnecessary metadata columns.
    -   Consolidation of multiple sales files into a unified fact table.

### Data Modeling & DAX
A star schema data model was built to enable powerful analytics:
-   **Custom Calendar Table:** Created using **DAX** to enable advanced time intelligence calculations (YTD, YoY, MTD, QTD).
-   **Relationships:** Established a single, many-to-one relationship between the `Calendar` and `Sales` tables for accurate time-based filtering.
-   **Key DAX Measures:** Developed for critical KPIs like `Total Sales`, `Revenue Growth (YTD YoY)`, and `Average Transaction Value (ATV)`.

## Dashboard Features & Key Visuals

### 1. Executive KPI Overview
-   **Total Sales (YTD)**
-   **Sales vs. Target (%)**
-   **Average Transaction Value (ATV)**
-   **Total Units Sold**
-   **Revenue Growth (YTD YoY)**

### 2. Strategic Analytical Reports
-   **Sales Trend Analysis (2009-2024):** Line chart tracking long-term performance.
-   **Monthly Sales vs. Target:** Stacked bar chart for performance tracking.
-   **Menu Performance (Pareto Analysis):** Ranked bar chart identifying top-selling, high-revenue menu items.
-   **Peak Period Heatmap:** Matrix visualization of sales volume by hour and day for optimal staff scheduling and promotions.
-   **Staff & Employee Productivity:** Analysis of sales contribution per employee.
-   **Branch & City Performance:** Geographic analysis using maps and tables to identify top-performing locations.

### 3. Interactive Controls
Dynamic filters and slicers allow for deep, exploratory analysis:
-   **Historical Date Range (2009-2024):** Drill down by Year, Quarter, Month, and Day.
-   **Menu Analysis:** Filter by Category (e.g., Appetizers, Bar, Main Course) and specific Menu Item.
-   **Performance Drill-Down:** Analyze individual staff contribution and performance trends.

## Tools & Technologies
-   **BI & Visualization:** Microsoft Power BI Desktop
-   **Data Processing & ETL:** Power Query (M Language)
-   **Data Modeling & Calculations:** DAX (Data Analysis Expressions)
-   **Data Sources:** Excel, JSON

## Project Documentation
For a detailed breakdown of the process, please refer to the project documents:
-   **[Branch Management Dashboard](./Branch_Management_Dashboard_v2.pdf)** - Detailed view of operational KPIs and visuals.
-   **[Executive Dashboard](./Top_Management_Dashboard_v2.pdf)** - High-level strategic insights for leadership.
-   **[Data Engineering & ETL Process](./Power_BI_Data_Engineering_ETL_v2.pdf)** - In-depth technical walkthrough of the data pipeline.

## Conclusion
This Power BI dashboard successfully transformed 15 years of historical data for Samba Bar & Restaurant into a single source of truth. It moves beyond simple reporting to enable proactive, data-informed strategic decisions, empowering the management team to optimize operations, maximize profitability, and drive sustained future growth.

---
**Developed by Frank Ouna | Data Analyst**
