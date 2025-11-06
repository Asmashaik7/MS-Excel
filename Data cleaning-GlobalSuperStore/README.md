# 🧹 Data Cleaning & Analysis – Global Superstore Dataset

## 📁 Project Overview
This project focuses on **data cleaning, transformation, and analysis** of the *Global Superstore* dataset using **Microsoft Excel**.  
The dataset contains **51,290 rows** and **24 columns**, covering sales, profit, order, and shipment details across regions.

---

## 🧼 Data Cleaning Process
**Tools Used:** Excel Power Query & Excel Functions  

1. **Loaded raw CSV file (GlobalSuperstore.csv)** into Power Query.  
2. **Fixed inconsistent date formats**  
   - Original issue: Dates appeared in mixed styles (`/` and `-`) and different locales.  
   - Solution: Replaced `-` with `/`, changed locale to *English (United States)*, and converted data type to *Date*.  
3. **Removed errors & nulls** from invalid date and numeric fields.  
4. **Standardized Data Types**  
   - `Order Date`, `Ship Date` → Date  
   - `Sales`, `Profit`, `Discount` → Decimal Number  
   - `Order ID`, `Customer Name`, `Region`, etc. → Text  
5. **Created Calculated Columns**
   - **Delivery Days** = Ship Date − Order Date  
   - **Profit Margin** = Profit / Sales  
6. **Formatted Profit Margin as Percentage (%)** for better readability.  
7. **Loaded cleaned data** back to Excel for analysis.

---

## 🚚 Data Challenges & Solutions
| Challenge | Root Cause | Solution |
|------------|-------------|-----------|
| Date column not showing hierarchy | Mixed formats (`/` & `-`) and locale mismatch | Replaced symbols and set locale to English (US) before changing to Date type |
| Power Query showing errors after type conversion | Locale applied *after* type change | Corrected order: Replace symbols → Set locale → Change data type |
| Large file restarting or lagging | 51k+ rows with multiple pivot operations | Used a fresh workbook for clean data |
| Profit Margin not converting to % | Excel treated it as text | Re-created column and formatted as Percentage |
| Understanding shipping performance | Needed numeric comparison | Created Delivery Days column for analysis |

---

## 📊 Analysis Performed (Pivot Tables + Charts)
Each analysis was built on a separate Excel sheet, with a pivot table and chart:
1. **Sales by Region** – Compared total sales across regions  
2. **Sales by Category** – Identified top-performing product categories  
3. **Average Delivery Days by Order Priority** – Measured delivery efficiency  
4. **Profit Margin by Region** – Evaluated regional profitability  
5. **Monthly Sales Trend** – Visualized seasonality and growth pattern  

---

## 💡 Key Insights
- Some *High-Priority* orders still took longer than expected to deliver.  
- Certain regions contributed higher sales but lower profit margins.  
- Seasonal peaks were visible in monthly sales trends.  

---

## 🏁 Outcome
A **fully cleaned, analyzed, and visualized** dataset — ready for reporting and dashboard creation.  
This project demonstrates strong Excel data cleaning, transformation, and pivot-based visualization skills.

---

## 👩‍💻 Author
**Asma Shaik**  
*Data Analyst (Power BI | Excel | SQL | Python)*  
