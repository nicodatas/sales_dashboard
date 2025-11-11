# sales_dashboard
 Sales Analytics Dashboard

Interactive sales dashboard featuring:
- Real-time KPI tracking (Total Sales, Profit, Discounts, Orders)
- Geographic sales distribution with interactive map
- Monthly and daily sales trends analysis
- Payment method breakdown
- Category-based sales comparison
- Multi-dimensional filtering (Country, Store Location, Category, Payment Method, Date Range)

Perfect for business intelligence and sales performance monitoring.

📊 Sales Performance Dashboard - Global Analytics Project
🎯 Project Overview
This project presents a comprehensive sales analysis dashboard built with Power BI, designed to provide actionable insights into global sales performance across multiple dimensions. The dashboard enables data-driven decision-making through interactive visualizations and advanced analytics.



🔧 Technologies & Tools Used

Power BI - Interactive dashboard and data visualization
Excel & Power Query - Initial data cleaning and transformation
SQL - Data structuring with CTEs and subqueries
Power Pivot & DAX - Calculated columns and custom measures
Data Modeling - Relational data model design

📊 Key Metrics & KPIs

Total Sales: $4.14M
Total Profit: $959.35K
Total Discounts: $76.69K
Total Orders: 3K
Average Order Value: $1.38K

🔍 Key Features
1. Multi-Dimensional Filtering

Country selection
Store location filtering
Product category breakdown
Payment method analysis
Custom date range selector

2. Geographic Analysis

Interactive global map visualization
Sales distribution across continents (North America, Europe, Asia, Australia, Africa, South America)
Store location markers for granular insights

3. Temporal Analysis

Monthly Sales Trends: Track performance fluctuations throughout the year
Daily Sales Patterns: Identify peak sales days (Sunday showing highest performance at 185K)
Seasonal trend identification

4. Payment Method Insights

Credit Card: 33.06% ($1.37M)
Cash: 32.75% ($1.35M)
Mobile Payment: 34.24% ($1.42M)

5. Category Performance

Home & Kitchen: $1.13M (highest performer)
Clothing: $0.71M
Electronics: $0.68M
Sports, Beauty, Toys: $0.68M, $0.67M, $0.67M respectively
Grain category analysis available

6. Profitability Analysis

Discount vs Profit correlation scatter plot
Store location profitability comparison
Regional performance analysis (Vancouver, Delhi, Chicago, Port Harcourt, Abuja, Los Angeles, Manchester)

📈 Key Insights & Findings

Sales Performance

Peak sales months: January ($0.44M), July ($0.43M), and March ($0.41M)
Lowest performance: June ($0.24M) and September ($0.26M)
Strong recovery trend observed in Q4


Geographic Trends

North American markets show consistent performance
Emerging opportunities in Asian and African markets
European markets demonstrate stable growth


Payment Preferences

Nearly equal distribution across payment methods indicates diverse customer preferences
Mobile payments slightly leading (34.24%), suggesting digital adoption trend


Category Insights

Home & Kitchen dominates with 27% market share
Balanced performance across other categories suggests diversified product portfolio
Grain category shows minimal contribution (0.00M)


Daily Patterns

Weekend sales (especially Sunday) significantly outperform weekdays
Mid-week dip observed (Tuesday: 71K)
Strategic inventory planning needed for weekend demand



💡 Business Recommendations

Inventory Management

Increase stock levels for Home & Kitchen products
Prepare additional inventory for weekends, especially Sundays
Focus on high-performing months (January, March, July)


Marketing Strategy

Launch promotional campaigns in low-performing months (June, September)
Leverage mobile payment trends with digital marketing
Target weekend shoppers with special offers


Regional Expansion

Strengthen presence in high-profit regions (Vancouver, Port Harcourt)
Investigate underperforming locations for improvement opportunities
Consider expansion in emerging markets


Discount Optimization

Analyze discount vs profit correlation to optimize pricing strategy
Review discount policies in regions with lower profitability
Implement targeted discounting during slow periods


Product Portfolio

Evaluate Grain category performance - consider discontinuation or revitalization
Expand Home & Kitchen offerings given strong performance
Balance inventory investment across top-performing categories



🛠️ Data Processing Workflow

Data Cleaning (Excel & Power Query)

Removed duplicate records
Handled missing values and inconsistencies
Standardized data formats and structures


Data Transformation (SQL)

Structured raw data using CTEs (Common Table Expressions)
Aggregated metrics with subqueries
Optimized data model for efficient querying


Data Modeling (Power Pivot & DAX)

Created calculated columns for derived metrics
Developed custom measures:

Total Profit = SUM(Sales) - SUM(Costs)
Average Order Value = DIVIDE([Total Sales], [Total Orders])
Discount Rate = DIVIDE([Total Discounts], [Total Sales])


Established relationships between dimension and fact tables
