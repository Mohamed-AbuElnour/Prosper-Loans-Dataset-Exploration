
# Prosper Loans Dataset Exploration
## by **Mohamed Magdy Ibrahim Mohamed**

## Dataset

> **Introduction:** This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others. The dataset can be found [here](https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv&sa=D&ust=1554484977406000).This [data dictionary](https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0) explains the definition of each variable in the dataset.

> **Data Wrangling:** Before choosing the final variables that I'll use, I've cleaned the data as follows:
- I changed the type of the date column from object to datetime
- Deleted all duplicated loans
- I've unified the credit ratings (before & after 2009) into one variable called CreditRating

> Out of the 81 variables, I've chosen 20 variables in which the visualization will focus

## Summary of Findings


> Borrowing rate was evidenced to decrease as these variables increase:
- Loan amount
- No. of investors funding the loan
- No. of recommendations to receive the loan

> Moreover, the Borrowing rate was found to decrease as:
- The borrower is a home owner (compared to non-home owners)
- The borrower has verified income proof documents (compared to the people who doesn't have these docs)
- The borrower belongs to higher income classes (compared to lower income classes)
- The borrower has a better Credit Rating (compared to low credit borrowers)

> I extended my visualization to see if there're certain criteria that supports the borrower to get a loan with lower interest rate. I found that even within the same group (like credit rating and having income proofs), borrowers can be charged lower borrowing rates as they meet further conditions (like being employed)

## Key Insights for Presentation

> I'll focus on the linear relationships that affects the movements of borrowing rates in either directions (i.e. up & down) 

> Moreover, I'll present differences between income groups, employed & unemplyed concerning the borrowing rates they pay for their loans

> I'll talk about the odd finding that the unemployed non-home owners are charged lower borrowing rates than the unemployed home owners, and how I decrypted this mystery 


```python

```
