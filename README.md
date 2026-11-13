# PhonePe Payment Insights Dashboard

Interactive Power BI dashboard that analyzes digital payment transactions, user segments, and service performance.

![Dashboard Preview](dashboard.png)

## Files
- `phonepay_analysis_1.pbix` – Power BI dashboard file
- `dashboard.png` – dashboard screenshot

## Dashboard Features
- KPI cards: total transactions, total value, unique users, success rate, and MoM growth
- Monthly trend of transactions and transaction value
- Age segment contribution
- Service-wise transaction value analysis
- Top 5 users by transaction value
- Weekday vs weekend usage
- Month and payment status slicers

## Data Model
- **All_Users:** User_ID, Name, Age Segment, Join_Date
- **All_Transactions:** Transaction_ID, User_ID, Date, Amount, Service, Service Type, Payment_Status, Reason
- **Date_Table:** Date, Day No., Month, Month No., Quarter

## Tools
Power BI, DAX, Power Query

## Key Insights
- 101K transactions worth 528.97M from 108K users
- 96.15% of transactions are successful
- Loans generate the highest transaction value
- Weekdays carry about 72% of all transactions
- Gen X and Millennials make up about 75% of users

## How to Open
Download the `.pbix` file and open it in Power BI Desktop.

