# Sales Performance Analysis of Retail Chain

## Overview
This project presents a business intelligence capstone focused on analyzing the sales performance of a retail chain in order to improve sales and inventory strategies.

The analysis examines sales patterns across products, stores, cities, and time periods, with the goal of identifying high-performing products, understanding regional sales differences, evaluating stock-level impact, and supporting more effective business decisions.

The final findings were presented in a structured business presentation supported by data preparation, analysis, visualizations, dashboards, and recommendations.

## Objective
To analyze retail sales performance and transform raw data into business insights and recommendations through data preparation, querying, statistical analysis, and Tableau dashboarding.

## Business Scenario
The project focuses on a retail chain operating across multiple regions and offering a diverse product range. The purpose of the analysis was to uncover key sales trends, evaluate product performance, assess regional sales variation, and provide recommendations to improve profitability and operational efficiency.

## Data Sources
The analysis started from six CSV datasets:
- `sales.csv`
- `product_hierarchy.csv`
- `store_cities.csv`
- `store_names.csv`
- `city_names.csv`
- `product_names.csv`

These datasets contained sales transactions, product hierarchy data, store information, and city details.

## Methodology

### 1. Data Cleaning and Preparation
- Cleaned and integrated the raw CSV datasets
- Used Excel to merge related columns such as product IDs, store IDs, and city IDs
- Built a consolidated dataset for further analysis

### 2. Data Querying and Analysis
- Used PostgreSQL for structured querying and analysis
- Applied SQL queries to retrieve, summarize, and analyze sales data
- Created aggregated views using ROLLUP
- Summarized performance across hierarchies such as store and product dimensions
- Analyzed sales trends across time and regions

### 3. Data Visualization and Statistical Analysis
- Used Excel to create supporting visualizations such as:
  - line chart
  - bar chart
  - sunburst chart
  - scatter plot
- Performed regression analysis to examine the impact of time on sales
- Interpreted p-values and R-squared values to assess significance and explanatory strength

### 4. Tableau Dashboards and Interactive Visualizations
- Imported the cleaned dataset into Tableau
- Created interactive visualizations including:
  - bar chart
  - line chart
  - scatter plot
  - packed bubbles chart
- Built dashboards combining multiple worksheets
- Used filters and highlight actions to support interactive analysis and drill-down

## Key Insights
- Sales performance differed across stores, cities, and products
- Higher stock levels were generally associated with higher sales
- Seasonal and regional sales trends were identified
- Certain products and locations had a stronger contribution to revenue
- Interactive dashboards improved the clarity and usability of the analysis

## Recommendations
- Optimize inventory levels to better match demand
- Focus resources on strong-performing regions and products
- Improve weaker-performing areas through targeted actions
- Prepare inventory and marketing strategies for peak periods
- Continue using data-driven analysis to support planning and decision-making

## Tools Used
- Excel
- PostgreSQL
- Tableau

## Deliverables
- cleaned and integrated dataset
- SQL-based analysis outputs
- Excel-based visualizations
- Tableau dashboards
- final business presentation

## Skills Demonstrated
- data cleaning and integration
- SQL querying and aggregation
- statistical analysis
- dashboard development
- data visualization
- business insight communication
- presentation of analytical findings
- decision-support reporting

## Evidence
This project includes supporting evidence such as:
- final presentation
- project overview screenshot
- dashboard screenshots
- analysis screenshots

## Files Included
- `final-presentation.pptx`

## Status
Completed capstone project

## Next Step
Enhance this portfolio entry with selected dashboard screenshots, a short section on the most important KPIs, and a brief explanation of how stakeholders can use the findings in practice.
