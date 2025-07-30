# Banking-Data-Excel-Project-
📊 BANKING DATA ANALYSIS PROJECT (Excel Dashboard – No Macro)
🔍 Project Objective:
To analyze banking transaction data using Excel and generate a dynamic, insightful dashboard for business understanding — all without using macros or VBA.

📁 Sheets Used:
Customer

Employee

Account

Transaction

Branch

✅ Work Done:
🔸 Data Cleaning & Preparation:
Created helper columns in raw sheets to support dashboard calculations.

Performed data classification and transformations for meaningful grouping.

🔸 Calculated Fields:
Transaction Sheet:

High Value Flag: Marked based on custom amount threshold.

Time Category: Categorized each transaction into Morning, Afternoon, Evening, Night.

Weekly Classification: Grouped transactions into Weekday / Weekend.

Employee Sheet:

Used DATEDIF function to calculate Years of Experience from DOJ.

Customer Sheet:

Created Full Name column using CONCAT function.

Calculated Age, then categorized into Age Group.

Account Sheet:

Used XLOOKUP to fetch Customer Name using Customer ID.

Used INDEX-MATCH to fetch Branch Name using Branch Code.

🔸 Conditional Formatting:
Applied to Transaction Amount column to highlight outliers using percentile-based logic(IQR).

🔸 Dashboard Creation:
Created KPI Summary:

Total Transactions, Total Amount, Total Accounts, Total Balance, Deposits, Transfers, Withdrawals.

Built visual charts using Pivot Tables:

Monthly Trend

Total Amount by Account Type

Top Transacting Customers

Age Group & Time Category Frequencies

State-wise Amount Flow

Branch-wise Amount & Split

Weekly Analysis

High Value Transaction Impact

Customer Balance Comparison

Used Pivot Tables and Charts for dynamic data insights.

🔸 Interactivity:
Added Slicers to filter dashboard by:

Year

Branch

📌 Tools & Techniques Used:
Pivot Tables

Pivot Charts

Slicers

Conditional Formatting

Excel Formulas:

SUMIF, XLOOKUP, INDEX-MATCH, DATEDIF, CONCAT, IF, IFS

📈 Business Value:
Helps management identify:

High-transacting customers

Transaction behavior by age, time, and geography

Outliers & suspicious transactions

Fully dynamic and macro-free, easy to update and share.

📝 Note:
Outlier logic and conditional formatting is explained in the transaction sheet.

All columns used in the dashboard are calculated directly in raw sheets.
