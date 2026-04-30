📊 Data Cleaning & Analysis — Global Superstore Dataset (Excel)

📁 Project Overview

This project focuses on end-to-end data cleaning, transformation, and business analysis of the Global Superstore dataset using Microsoft Excel.

The dataset contains 51,290 rows and 24 columns, covering sales, profit, orders, and shipment details across global regions (2011–2015).

🛠️ Tools Used
Microsoft Excel (Pivot Tables, Charts, Dashboard Design)
Power Query (Data Cleaning & Transformation)
Excel Functions (IFERROR, SUMIFS, COUNTIFS)
Calculated Columns (Delivery Days, Profit Margin)

🧹 Data Cleaning Process
Steps Performed:
Loaded raw CSV file into Power Query
Fixed inconsistent date formats (- and /) and corrected locale to English (US)
Converted columns to appropriate data types:
Order Date, Ship Date → Date
Sales, Profit, Discount → Decimal
Region, Category → Text
Removed nulls and errors from dataset
Created calculated columns:
Delivery Days = Ship Date − Order Date
Profit Margin = Profit / Sales (handled using IFERROR to avoid division errors)
Formatted Profit Margin as Percentage (%)
Loaded cleaned dataset into Excel for analysis

🚧 Data Challenges & Solutions
Challenge	Solution
Mixed date formats	Standardized using Power Query and locale conversion
Division errors in Profit Margin	Handled using IFERROR()
Large dataset lag	Used clean structured data model
Incorrect % formatting	Applied proper percentage formatting

📊 Analysis Performed

Each analysis includes pivot tables, charts, and business insights.

📊 Key Analysis
Sales by Region
Sales by Category
Profit Analysis
Profit Margin by Region
Delivery Performance
Monthly Sales Trend
Sales by Ship Mode

💡 Key Insights
Central region dominates sales (~23%), indicating dependency on a single region
Technology leads category sales, but profitability varies across categories
Some regions (Africa, EMEA) are loss-making, despite generating sales
Overall profit margin is low (~4.7%), indicating need for cost optimization
Sales show strong seasonality, with peak performance in Q4
Standard shipping dominates (61%), showing customer preference for cost over speed

🏁 Outcome

Developed a complete Excel-based analysis project with:

Cleaned and structured dataset
Business insights using pivot tables
Dashboard-style visualizations

👤 Author

Asma Shaik
Data Analyst | Excel | SQL | Power BI | Python