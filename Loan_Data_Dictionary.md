# Data Dictionary

This database contains the publicly available data from LendingClub.com, a platform that connects borrowers and investors. The database has information on more than 9,500 loans, including the loan structure, the borrower, and whether the loan was fully paid. 

[Data Source](https://www.kaggle.com/itssuru/loan-data)

| Variable           | Explanation                                                                                                                                                                       |
|--------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| credit_policy      | 1 if the customer meets the credit underwriting criteria of LendingClub.com, and 0 otherwise.                                                                                     |
| purpose            | The purpose of the loan (takes values "creditcard", "debtconsolidation", "educational", "majorpurchase", "smallbusiness", and "all_other").                                       |
| int_rate           | The interest rate of the loan, as a proportion (a rate of 11% would be stored as 0.11). Borrowers judged by LendingClub.com to be more risky are assigned higher interest rates.  |
| installment        | The monthly installments owed by the borrower if the loan is funded.                                                                                                              |
| log_annual_inc     | The natural log of the self-reported annual income of the borrower.                                                                                                               |
| dti                | The debt-to-income ratio of the borrower (amount of debt divided by annual income).                                                                                               |
| fico               | The FICO credit score of the borrower.                                                                                                                                            |
| days_with_cr_line  | The number of days the borrower has had a credit line.                                                                                                                            |
| revol_bal          | The borrower's revolving balance (amount unpaid at the end of the credit card billing cycle).                                                                                     |
| revol_util         |  The borrower's revolving line utilization rate (the amount of the credit line used relative to total credit available).                                                          |
| inq_last_6mths     | The borrower's number of inquiries by creditors in the last 6 months.                                                                                                             |
| delinq_2yrs        | The number of times the borrower had been 30+ days past due on a payment in the past 2 years.                                                                                     |
| pub_rec            | The borrower's number of derogatory public records (bankruptcy filings, tax liens, or judgments).                                                                                 |
| not_fully_paid     | 1 if the loan is not fully paid; 0 otherwise.                                                                                                                                     |
