# Bank Analysis – Power BI Dashboards

Interactive Power BI dashboards that analyse **bank loan portfolio** data and **debit / credit transaction** data.

## Screenshots

### Loan Overview
![Loan Overview](https://github.com/user-attachments/assets/4a3cdb09-555c-47c7-add6-5708338c8d52)

### Credit and Debit Analysis
![Credit and Debit Analysis](https://github.com/user-attachments/assets/326b0150-4168-484f-9fc6-ceab328024d4)

Interactive Power BI dashboards that analyse **bank loan portfolio** data and **debit / credit transaction** data.

## Project Files

| File | Description |
|---|---|
| `Bank_Analysis_Dashboard.pbix` | KPI-by-KPI build (one page per KPI) plus a combined **Dashboard** page for loans, and 12 KPI pages for credit/debit transactions |
| `Power_Bi_Bank_Analysis_Dashoard_2.pbix` | Final 4-page dashboard with navigation buttons, bookmarks and slicers |

## Tools Used
- Power BI Desktop
- Power Query (data cleaning and transformation)
- DAX (measures and KPIs)
- Excel (source data)

## Data Model

**Banking Data** (loan data)
Account ID, Bank Name, Branch Name, Region Name, State Name, Product Code, Purpose Category, Grade, Loan Status, Term, Age, Religion, Caste, Funded Amount, Total Payment, Total Received Interest, Total Fees

**Sheet1** (credit / debit transactions)
Transaction Date, Bank Name, Branch, Transaction Method, Amount, High Risk Flag

## Dashboard 2 – Page Overview

### Page 1 – Loan Overview
- KPI cards: Funded Amount, Account count, Total Payment, Total Received Interest, Default Loans, Default Loan Ratio, Delinquent Loans, Delinquent Loan Ratio, Not Verified Loans
- Loan Status funnel
- Funded Amount by Product Code, by Grade, by Religion
- Funded Amount trend (line chart)
- Slicers: Region, Branch, Bank, Religion

### Page 2 – Loan Distribution
- State-wise loan distribution map
- Branch-wise Total Interest, Total Payment and Total Fees table
- Loans by Age group (treemap) and by Term (column chart)
- Slicers: Grade, Branch, Term, State

### Page 3 – Credit and Debit Analysis
- KPI cards: Credit Amount, Debit Amount, Net Transaction Amount, Credit to Debit Ratio, Account Activity Ratio
- Transactions per day / month trend
- Amount by Bank (stacked area), by Branch (bar), by Transaction Method (donut)
- Slicers: Bank, Branch, Transaction Method, High Risk Flag, Transaction Date

### Page 4 – Risk and Growth
- High Risk Flag count by Transaction Method
- Suspicious transactions over time (stacked area)
- Branch Growth % table
- Slicers: Transaction Method, Transaction Date, Branch, Bank

## Dashboard 1 – Key Measures Built

**Loans:** Total Loan Amount Funded, Total Loan, Total Collection, Total Interest, Total Revenue, Count of Default Loan, Count of Delinquent Client, Default Loan Rate, Delinquent Loans Rate, No Verified Loans

**Transactions:** Total Credit Amount, Total Debit Amount, Credit to Debit Ratio, Net Transaction Amount, Account Activity Ratio, Transactions per Day/Week/Month, Branch Growth %, Suspicious Transactions

## Key Insights
- [Add 3 to 5 findings from your own dashboard, e.g. which branch has the highest revenue]
- [Which state has the highest funded amount]
- [Default / delinquent loan rate and which grade drives it]
- [Which transaction method has the most high-risk flags]


## How to Use
1. Clone or download this repository
2. Open a `.pbix` file in Power BI Desktop
3. The data is stored inside the file, so no extra setup is needed. If you use the source Excel files, update the data source path in **Transform data → Data source settings**, then click **Refresh**

## Skills Demonstrated
Data cleaning (Power Query), data modelling, DAX measures, KPI design, interactive slicers, bookmarks and navigation buttons, dashboard layout, risk and growth analysis

## Author
**Shafiq Shaikh** – Mumbai, India

