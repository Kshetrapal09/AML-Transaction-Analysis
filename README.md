# Identifying High-Risk Accounts for AML Using Frequency and Value Analysis
## 📊 Project Summary
This project analyzes financial data from the IBM Anti-Money Laundering (AML) dataset to identify high-risk accounts. Using a rule-based approach focused on transaction frequency and total monetary value, this analysis flags potential money laundering suspects by identifying accounts with behavior consistent with structuring.

## Steps Taken
-Data Preprocessing: Loaded and cleaned the transaction dataset, renaming columns and correcting data types for analysis.

-Rule 1 (Frequency Analysis): Identified accounts with an unusually high frequency of suspicious cash deposits, a common indicator of structuring.

-Rule 2 (Value Analysis): Calculated the total monetary value of these deposits for each account to find high-value targets.

-Data Enrichment: Loaded a second 'Accounts' dataset and merged it with the transaction findings to create a detailed profile of the top suspects.

## Key Findings
-The analysis identified two high-risk accounts that met the criteria for both high frequency and high value of suspicious cash deposits.

-These accounts had deposit counts of 24,726 and 14,989 respectively.

-The total value of these deposits was massive, at approximately ** $22.1 billion and $12.5 billion **.

-Both suspect accounts were linked to the ** same institution: Willows Thrift bank **.

-![Suspicious Accounts Chart](https://github.com/Kshetrapal09/AML-Transaction-Analysis/blob/main/aml_chart%20(1).png)

## Tools Used
-Python (Pandas)-for Analysis

-Python (Matplotlib)-for visualization
