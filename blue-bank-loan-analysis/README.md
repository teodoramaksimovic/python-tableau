# Blue Bank Loan Analysis

Python data cleaning + interactive Tableau dashboard for a fictional bank's loan portfolio.

📊 [View the dashboard on Tableau Public](https://public.tableau.com/app/profile/teodora.maksimovic/viz/BlueBank_17945288744050/BlueBankLoan)

![Blue Bank Loan Dashboard](<Blue Bank Loan.png>)
   > The screenshot is static. Open the Tableau Public link to use the filters and the detail view.

## What I did
- **Python (pandas):** loaded raw JSON loan data, converted log income to annual income, created FICO category and interest rate type features, and exported `loan_cleaned.csv` ([notebook](blue_bank.ipynb)).
- **Tableau:** built a dashboard with KPIs, a pie chart, a utilization histogram, bar charts by credit score and income group, and filters. Created an *Annual Income Group* calculated field.

## Key insights
- 54.51% of loans have a high interest rate (>12%).
- Most borrowers have *Excellent* or *Good* FICO scores (~95%).
- Loans are concentrated in the 10k–100k income range.

## Dashboard Features
- Interactive filters (interest rate type, FICO category, income group) that update all charts at once
- KPI cards at the top for a quick portfolio overview
- Detail view: Clicking a mark in any chart (e.g. the *Fair* bar in the credit score chart) opens a
  *Click for More Info* table with the underlying loan-level records (ID, FICO category, income group,
  purpose, annual income, days with credit line, DTI, interest rate, revolving balance, utilization rate)

## Tools
Python (pandas, NumPy, matplotlib) · Tableau Public

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white) 
