# Bank Statement Analysis (Excel)

## Objective
Analyse a year of bank transactions to understand how money moved in and out of the account, which transaction categories drove the balance, and how the balance changed over time.

## Dataset
- 1,000 transactions from 1 Jan 2022 to 1 Jan 2023, with an opening balance of ₹1,000
- Columns: Transaction No., Date, Category, Amount, Balance, Debit/Credit type, Change
- Categories: Deposit, Withdrawal, Interest, Fee, Transfer

## Tools & Techniques
- Excel / Google Sheets
- Formulas: built a `Change` column (`=E3-E2`) to calculate the impact of each transaction on the balance
- Filters to explore transactions by category and type
- Line chart to visualise the balance trend across all 1,000 transactions

## Approach
1. Reviewed the statement structure and classified each transaction as Credit, Debit or NC (no change in balance)
2. Added a `Change` formula column to measure how each transaction moved the balance
3. Verified that every running balance matched the opening balance plus cumulative changes
4. Plotted the balance over time to identify peaks, dips and overall trend

## Key Insights
1. The line chart plots the account balance across all 1,000 transactions (Jan 2022 to Jan 2023).
2. Overall growth: The balance rose from ₹1,000 to ₹6,664.08, a net gain of ₹5,664.08, but not in a straight line.
3. Strong finish: From November onwards, the balance rose steeply to a peak of ₹7,108.11 on 26 December 2022, driven by high deposits and lower spending.



<img width="587" height="340" alt="Bank_Statement_Analysis" src="https://github.com/user-attachments/assets/8c14d05d-d515-4290-8247-843a5812aefa" />
<img width="688" height="519" alt="Bank_Statement_Change" src="https://github.com/user-attachments/assets/67893363-d598-4f60-823a-834f9be4cdcd" />

