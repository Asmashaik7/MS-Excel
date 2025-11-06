🧼 Data Cleaning Process

Tools Used: Excel Power Query & Excel Functions

Loaded raw CSV file (GlobalSuperstore.csv) into Power Query.

Fixed inconsistent date formats

Original issue: Dates appeared in mixed styles (/ and -) and different locales.

Solution: Replaced - with /, changed locale to English (United States), and converted data type to Date.

Removed errors & nulls from invalid date and numeric fields.

Standardized Data Types

Order Date, Ship Date → Date

Sales, Profit, Discount → Decimal Number

Order ID, Customer Name, Region, etc. → Text

Created Calculated Columns

Delivery Days = Ship Date − Order Date

Profit Margin = Profit / Sales


Formatted Profit Margin as Percentage (%) for better readability.

Loaded cleaned data back to Excel for analysis.
