# Banking Data Analysis using PySpark

## Overview
This project analyzes multiple banking-related datasets — **Loan**, **Credit Card**, and **Transaction** — using **PySpark** for distributed data processing.  
It focuses on extracting valuable insights such as loan distribution, credit card eligibility, and transaction behavior of customers.

## Process
The analysis was carried out using **PySpark** to handle large-scale financial data efficiently.  
The steps involved in the process are as follows:

1. **Data Loading:**  
   - Imported and read multiple CSV files — `loan.csv`, `credit card.csv`, and `txn.csv`.  
   - Created Spark DataFrames and inspected their schemas, data types, and counts.

2. **Data Exploration & Cleaning:**  
   - Checked for missing or duplicate records.  
   - Ensured data consistency by validating numerical and categorical fields.  

3. **Data Transformation & Analysis:**  
   - Used PySpark functions (`groupBy`, `filter`, `orderBy`, `count`, `max`, `min`) to perform key operations and derive insights.  
   - Applied conditional filtering to study customer income, loan amounts, and transaction activities.  

4. **Insights Extraction:**  
   - Identified customers eligible for credit cards based on credit scores and activity.  
   - Analyzed loan categories, expenditure patterns, and cheque return behaviors.  
   - Determined transaction frequency, maximum/minimum withdrawal and deposit amounts, and account balances.

### Key Operations
- **Loan Dataset**
  - Count loans by category.  
  - Identify customers with high loan amounts or low income.  
  - Analyze returned cheques and monthly expenditures.

- **Credit Card Dataset**
  - Detect customers eligible for credit cards (CreditScore > 700).  
  - Analyze active members and salary distribution by geography.  

- **Transaction Dataset**
  - Count total transactions per account.  
  - Find maximum/minimum withdrawal and deposit amounts.  
  - Calculate overall account balances and detect high-value withdrawals.

## Results
✅ Identified creditworthy customers and high-value accounts.  
✅ Gained insights into loan trends, expenditure patterns, and transaction frequency.  
✅ Demonstrated how **PySpark** efficiently handles large-scale financial data.

---

