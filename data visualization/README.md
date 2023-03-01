# ProsperLoan Data Exploration

## Dataset

This financial [dataset](https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv&sa=D&ust=1547699802003000)includes information about loans, borrowers, lenders, interest rates, and other connected topics. A company called Prosper, also known as Prosper Marketplace Inc., is located in San Francisco, California and specializes in giving borrowers loans with low interest rates. We are looking for a trend in the Prosper data in this dataset. Due to the sheer magnitude of the dataset and the complexity of all the financial datasets, this could be tedious.

There are 113937 items in the dataset, which has 81 variables.
This [data dictionary](https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit?usp=sharing) explains the 
variables in the data set.
All of the dataset's factors are not anticipated to be explored as part of the project goal! But limit your research to just 24 of them.

## Summary of Findings


•LoanStatus of all Borrowers are with current, completed and defaulted state
•EmploymentStatus of all Borrowers are with Employed
•Majority of the loan applicants are from 25K to 50K range with emloyeed status
•The top 2 loan consideration reasons are **1 - Debt Consolidation, 7 - Other** 
•The majority of borrowers work in Other and Professional fields.
•The top two borrowing jurisdictions are CA and FL.
•The majority of the loans were for terms of **36** months
•The loan's initial principal payment. This is now intriguing. We can see that the distribution is right-skewed in this case, with the peak being found at roughly 4000 USD.
Majority of the borrowers are with a prosper score between **4 to 9**


## Key Insights for Presentation

- Most people having a source of income were considered for loan with Majority of them earning above 25,000 USD
- People earning above 100,000 USD had the lowest numbers of defaulters, majority of the defaulters were in the 0 - 100,000 USD bracket.
- Majority borrowed loan due to **Debt Consolidation**, while some still defaulted.
- People whose occupation belong to the category **Other** dominated the loan pool, followed by **Professional**
- Most people that defaulted on the loan or were chargedoff had loan with a high _BorrowerAPR_
- There is a positive relationship between term and rating and the loan amount
- The lesser the _BorrowerAPR_ the higher the _ProsperRating_Numeric
- BorrowerRate, BorrowerAPR, and LenderYield are all strongly correlated, implying that they might have similar effect on prediction.
- Some borrowers filled **Occupation, EmploymentStatus and ListingCategory (Numeric)** with _Other_. This categories of borrowers defaulted significantly on their loans, and also were chargedoff.