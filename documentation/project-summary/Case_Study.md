# Samba Bar & Restaurant: Business Intelligence Transformation Case Study

## Executive Summary
Samba Bar & Restaurant, a Kenya-based establishment, faced challenges in leveraging 15 years of accumulated operational data (2009-2024) for strategic decision-making. This case study documents the transformation of disparate historical data into an interactive Power BI dashboard that provides actionable insights for management and executive teams.

## Business Challenge
### Problem Statement
- **Data Fragmentation:** Operational data scattered across multiple formats (Excel, JSON, CSV files)
- **Limited Visibility:** No centralized view of long-term performance trends across 15 years
- **Manual Analysis:** Time-consuming manual processes for performance reporting
- **Strategic Gaps:** Difficulty identifying growth patterns, seasonal trends, and operational inefficiencies

### Key Business Questions
- How has the business performed over the 15-year period?
- Which menu items drive the majority of revenue?
- What are the peak operational hours for optimal staffing?
- How do different branches and staff members perform comparatively?

## Solution Architecture

### Technical Implementation
**ETL Pipeline (Power Query):**
- Consolidated data from Excel workbooks, JSON files, and CSV exports
- Performed data type conversions, column derivations, and structural transformations
- Created unified fact tables for comprehensive analysis

**Data Modeling (DAX):**
- Built custom Calendar table for advanced time intelligence
- Established star schema relationships between fact and dimension tables
- Implemented calculated measures for YTD, YoY, and growth metrics

**Visualization Layer:**
- Executive dashboard for high-level strategic overview
- Branch management dashboard for operational insights
- Interactive filters for dynamic data exploration

### Key Features Delivered
1. **Executive KPI Monitoring:** Real-time tracking of sales, growth, and performance metrics
2. **Historical Trend Analysis:** 15-year sales performance visualization
3. **Menu Optimization Tools:** Pareto analysis of top-performing menu items
4. **Operational Intelligence:** Peak period heatmaps for staffing optimization
5. **Geographic Performance:** Branch and city-level performance comparisons

## Business Impact

### Quantitative Benefits
- **360° Performance Visibility:** Consolidated 15 years of data into single source of truth
- **Time Efficiency:** Reduced manual reporting time from days to real-time access
- **Data-Driven Decisions:** Enabled evidence-based strategic planning
- **Operational Optimization:** Identified opportunities for menu and staffing improvements

### Strategic Advantages
- **Proactive Planning:** Ability to forecast based on long-term historical patterns
- **Competitive Edge:** Data-driven insights for market positioning
- **Scalable Foundation:** Architecture supports future business growth and data expansion

## Technology Stack
- **BI Platform:** Microsoft Power BI Desktop
- **Data Processing:** Power Query (M Language)
- **Data Modeling:** DAX (Data Analysis Expressions)
- **Data Sources:** Excel, JSON, CSV
- **Methodology:** Star Schema Data Modeling

## Project Timeline
- **Phase 1:** Data Discovery & Requirements Gathering (1 week)
- **Phase 2:** ETL Pipeline Development (2 weeks)
- **Phase 3:** Data Modeling & DAX Implementation (1 week)
- **Phase 4:** Dashboard Development & Visualization (2 weeks)
- **Phase 5:** Testing & Deployment (1 week)

## Conclusion
The Samba Bar & Restaurant Power BI dashboard project successfully transformed historical operational data into a strategic asset. By implementing a robust data engineering pipeline and intuitive visualization layer, the business now possesses the tools to make informed decisions, optimize operations, and drive sustained growth.

The solution demonstrates how proper data management and business intelligence practices can unlock valuable insights from historical data, turning information into competitive advantage.

---
*Project completed by Frank Ouna | Data Analyst*