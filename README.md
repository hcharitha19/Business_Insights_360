# Business_Insights_360


## Project Overview
AtliQ Hardware is growing rapidly and decided to implement data analytics using Power BI
to enable data-driven decision-making and stay competitive in the global market.

In this project, I built an end-to-end Power BI analytics solution to answer key business
questions across Finance, Sales, Marketing, Supply Chain, and Executive domains.

---

## Live Report
https://app.powerbi.com/groups/me/reports/872c73ff-7e69-45c2-9267-1941489d7eee/ReportSection3e6d270a5b20870d7cd8?experience=power-bi

---

## Tech Stack
- SQL
- Power BI Desktop
- Excel
- DAX Language
- DAX Studio
- Power BI Service

---

## Power BI Techniques Learned
- Understanding business requirements before starting the project

## Learning Reference:
Codebasics (data analytics Bootcamp) 
👉https://codebasics.io/
- Creating calculated columns
- Creating measures using DAX
- Snowflake data modeling
- Using bookmarks to switch between visuals
- Page navigation using buttons
- Using DIVIDE function to prevent zero division errors
- Creating date table using M language
- Dynamic titles based on applied filters
- KPI indicators
- Conditional formatting using icons and background colors
- Data validation techniques
- Publishing reports to Power BI Service
- Setting up personal gateway for scheduled data refresh
- Power BI app creation
- Workspace collaboration and access permissions

---

## Business Terms
- Gross Price
- Pre-Invoice Deductions
- Post-Invoice Deductions
- Net Invoice Sales
- Gross Margin
- Net Sales
- Net Profit
- COGS (Cost of Goods Sold)
- YTD (Year to Date)
- YTG (Year to Go)

---

## Company Background
AtliQ Hardware is a global company that sells computers and computer accessories through
multiple business channels:
- Retailers
- Direct sales
- Distributors

The company experienced losses due to expansion decisions based on intuition and limited
analysis. To compete with analytics-driven competitors and improve decision-making,
AtliQ Hardware decided to build a centralized analytics solution using Power BI.

---

## Dataset Understanding

### Dimension Tables
- **dim_customer**  
  Contains customer details, markets, regions, platforms, and channels.

- **dim_market**  
  Contains market, region, and sub-zone information.

- **dim_product**  
  Contains product divisions, categories, and variants.

### Fact Tables
- **fact_sales_monthly**  
  Contains monthly sold quantities for each product and customer.

- **fact_forecast_monthly**  
  Contains monthly forecast quantities to support demand planning and supply chain optimization.

Fact tables store transactional data, while dimension tables store descriptive attributes
used for analysis.

---

## Data Modeling
Data modeling plays a critical role in report performance and accuracy.  
This project follows **Snowflake schema** best practices to ensure:
- Better query performance
- Reduced data redundancy
- Accurate aggregations across dimensions

---

## Dashboard Views

### Home View
Provides navigation to all report sections.

### Finance View
Analyzes revenue, costs, profit margins, and financial KPIs.

### Sales View
Tracks sales performance by market, customer, and product.

### Marketing View
Evaluates market trends, customer contribution, and channel performance.

### Supply Chain View
Compares forecast vs actual sales to identify demand gaps.

### Executive View
Provides high-level KPIs and insights for leadership decision-making.

(Add dashboard GIFs or screenshots here)

---

## Project Outcome
This dashboard enables stakeholders to:
- Monitor revenue and profitability trends
- Identify high- and low-performing markets and products
- Compare actual vs forecast performance
- Improve supply chain planning
- Make faster, data-driven business decisions

This project strengthened my end-to-end Power BI development, data modeling, and business
analytics skills and improved my ability to translate data into actionable insights.
