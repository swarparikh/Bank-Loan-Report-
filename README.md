# Bank Loan Portfolio Risk Analytics Dashboard

## Overview

This project is an end-to-end Power BI dashboard built to analyze bank loan data and financial risk metrics. The primary objective of this project was to transform raw banking and loan application data into a clean, interactive dashboard that highlights critical financial trends, portfolio health, borrower profiles, and risk dynamics.

The project covers the complete Power BI workflow — from ingesting and transforming data with Power Query to establishing robust data models, writing business-logic DAX measures, and designing a clear financial dashboard.

## Project Details

I developed this project to gain practical hands-on experience in financial data analytics and risk management. In banking, understanding credit risk, repayment capacity, and loan defaults is vital for maintaining portfolio profitability. The focus was on building a data-driven pipeline that delivers high-level operational KPIs alongside granular risk insights.

The dashboard allows stakeholders to:
- Monitor overall loan application volume, total funded capital, and total repayments received.
- Distinguish between "Good Loans" (performing) and "Bad Loans" (non-performing/defaults).
- Analyze borrower financial health using key metrics like average Interest Rates and Debt-to-Income (DTI) ratios.
- Explore performance dynamics across loan terms, employment lengths, geographic regions, and loan purposes.

## Features

- **Data Cleaning & Transformation:** Handled missing values, standardized data types, and validated loan attributes in Power Query.
- **Data Modeling:** Modeled structured financial metrics with optimized table relationships.
- **DAX Measures:** Written custom measures for key metrics including Total Funded Amount, Total Amount Received, MTD/MoM growth, and Good vs. Bad Loan ratios.
- **Interactive Visuals & Slicers:** Filter by loan grade, purpose, state, employment length, and repayment status.
- **Executive & Detail Views:** High-level executive summaries paired with detailed tabular loan breakdowns.

## Project Workflow

```powershell
Raw Bank Loan Data
    ↓
Data Import in Power BI / SQL Database
    ↓
Data Cleaning & Transformation
    ↓
Data Modeling & DAX Measures
    ↓
Dashboard Creation
    ↓
Financial Insights & Risk Analysis
```

**Dataset & Domain Knowledge**

The dataset contains comprehensive loan application and repayment details across the full lending lifecycle: 
- **Loan Applications:** Capital requested, loan status, issue dates, and loan terms.  
- **Financial Details:** Interest rates, installment amounts, and borrower Debt-to-Income (DTI) ratios. 
- **Borrower Profile:** Employment history, home ownership, verified income, and location. 
- **Repayment Data**: Total principal and interest collected to evaluate overall portfolio profitability.


**Key Metrics & KPIs**

- **Total Loan Applications:** Measure of overall incoming loan demand. 
- **Total Funded Amount:** Total capital disbursed to borrowers.
- **Total Amount Received:** Total cash flow collected through repayments.
- **Average Interest Rate & DTI:** Financial health indicators of the loan portfolio.
- **Good vs. Bad Loan Breakdown:** Quantitative tracking of fully paid/current loans versus charged-off/defaulted loans.




**Using the Dashboard**

Once the dashboard is opened:

- Use top-level slicers to filter by issue date, grade, or state.
- Navigate between Summary, Overview, and Details tabs to inspect portfolio health from macro to micro levels.
- Analyze regional distributions and default patterns to assess risk exposure.

**Tools & Technologies**

- Power BI Desktop.
- Power Query.
- DAX (Data Analysis Expressions).
- SQL / CSV Datasets.

**What I Learned**

Working on this project helped me:

- Master financial analytics concepts such as debt-to-income evaluation and credit risk profiling.
- Implement complex DAX measures for month-over-month (MoM) and year-to-date (YTD) financial performance.
- Apply domain knowledge to build risk-focused visuals that support executive decision-making.
- Build structured ETL pipelines to handle raw banking datasets.

## Author
Swar Parikh

Busniess Analyst | Data Analyst | Power BI | SQL | Python
