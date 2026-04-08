# Super Store Sales Analytics – Power BI

## Overview
This project presents a structured Business Intelligence solution built using Power BI to analyze retail sales performance.

The objective was to transform raw transactional data into a structured analytical model and build interactive dashboards that support data-driven decision-making.

---

## Data Preparation (Power Query)
Several data transformation steps were applied to ensure data quality and consistency:

- Removed duplicate records  
- Standardized categorical fields  
- Cleaned inconsistent text values  
- Validated and corrected data types  
- Created derived date attributes for time-based analysis  

---

## Data Modeling
A **Star Schema** was implemented to optimize performance and usability:

- **Fact Table**
  - Sales transactions  

- **Dimension Tables**
  - Dim_Customer  
  - Dim_Product  
  - Dim_Date  
  - Dim_City  

Relationships were configured to support efficient filtering and aggregation across the model.

---

## DAX Measures
Custom measures were created to support analysis and reporting:

- Total Sales  
- Number of Orders  
- Average Delivery Time  
- Sales by Category  
- Sales by Quarter  
- Percentage Distribution Metrics  

---

## Dashboard Features
The dashboard was designed to be interactive, clear, and business-oriented:

- KPI cards for high-level performance overview  
- Category-level sales analysis  
- Customer performance breakdown  
- Quarterly trend visualization  
- Interactive slicers for dynamic filtering  
- Consistent and clean visual styling  

---

## Business Insights
Key findings from the analysis include:

- Technology category generated the highest sales  
- A small number of customer segments contributed disproportionately to revenue  
- Clear seasonal variation across quarters  
- Delivery performance varied across different regions  

---

## Tech Stack
- Power BI  
- Power Query  
- DAX  
- Star Schema Data Modeling  

---

## CV Version (BI-Focused)

- Designed a star schema data model (fact and multiple dimensions) for retail sales analytics  
- Performed data cleaning and transformation using Power Query  
- Built interactive dashboards using DAX measures and KPI visualizations  
- Generated insights on sales trends, customer behavior, and seasonal patterns  
