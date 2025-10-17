
**Banking Data Analytics with PySpark**

### 📖 Description:

This project demonstrates **banking domain analytics** using **PySpark**. It covers three datasets – **Loans, Credit Cards, and Transactions** – and extracts insights such as loan distribution, customer behavior, credit card eligibility, and high-value transactions.

The project highlights **data cleaning, grouping, filtering, and aggregations** in PySpark, showcasing how large-scale financial data can be analyzed efficiently.

---

### ⚡ Features:

* 📊 **Loan Analysis** – Loan category distribution, high loan amounts, income-based loan eligibility, overdue detection.
* 💳 **Credit Card Analysis** – Customer segmentation by credit score, activity status, salary-based exit patterns, country-wise filtering.
* 💰 **Transaction Analysis** – Account-level transaction counts, min/max withdrawal & deposit, sum of balances, high-value withdrawals, date-wise activity.
* 🛠️ **Tech Stack** – PySpark, Python, Jupyter Notebook.

---

### 📂 Project Structure:

```
banking-data-analytics/
│── loan.csv
│── credit_card.csv
│── txn.csv
│── banking_analysis.ipynb
│── README.md
```

---

### 🚀 How to Run:

1. Install dependencies

   ```bash
   pip install pyspark findspark
   ```
2. Start Jupyter Notebook

   ```bash
   jupyter notebook
   ```
3. Open `banking_analysis.ipynb` and run cells step by step.

---

### 📊 Sample Insights:

* Loan Category distribution → **Gold Loan is the most common**.
* Credit Card customers → **Active members with CreditScore > 700 are eligible**.
* Transactions → **Some accounts have withdrawals > 1 crore**.

---

