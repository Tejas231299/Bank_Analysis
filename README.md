# Bank_Loan_Analysis

![FINANCE (4)](1721177210873.png)


## 📝 Project Overview
This project contains SQL queries designed to analyze bank loan data from two tables: finance 1 and finance 2. The analysis focuses on extracting key performance indicators (KPIs) related to loan amounts, revolving balances, payments, and loan statuses.

## 💾 Database & Tables
Database: bank_loan_analysis

Tables:

finance 1: Contains loan details such as loan amount, issue date, grade, and state.

finance 2: Contains payment details such as total payment, last payment date, and loan status.

🚀 KPIs & Queries
✅ KPI 1: Year-wise Loan Amount Stats
-- Output: Year and total loan amount issued.
📊 KPI 2: Grade & Sub-Grade Wise Revolving Balance
Output: Grade, sub-grade, and the total revolving balance.

💰 KPI 3: Payment Stats by Verification Status
Output:

verification_status: Verified or Non-verified.

total_payment: Formatted in millions (e.g., $5.32M).

🌍 KPI 4: State-wise & Month-wise Loan Status

Output: State, credit pull date, and loan status.

🏠 KPI 5: Home Ownership vs Last Payment Date

Output:

home_ownership: Ownership type (e.g., Rent, Mortgage).

last_pymnt_d: Last payment date.

total_payment: Formatted in thousands (e.g., $52

📚 Setup & Execution

Clone this repository:

Import the SQL script into your database environment.

Execute the SQL queries to generate the KPIs.

Use the results for analysis and reporting.

🛠️ Technologies Used

SQL

MySQL Database
