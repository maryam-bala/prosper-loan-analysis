#  Prosper Loan Data Exploration
## by Maryam Adamu Bala 

## Dataset
This dataset contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others.The dataset can be found [here](https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv) with feature documentation available [here](https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0)

> 
## Summary of Findings
- In my exploration, I found out that the borrower APR and loan original amount are negatively correlated, that is the more the loan amount, the lower the APR. 
- BorrowerAPR and BorrowerRate have a very strong correlation. Having a high APR will result in borrowers paying more interest on their loans.
- Income range of $1-24,999k has the highest median Borrower rate. It is off from the trend of $25k and above income ranges where median borrower rate reduces with increased income. 
- The original loan amount is positively correlated with the stated monthly income, it makes sense since borrowers with more monthly income can take more loans. The loan amount is also increased with the increase of loan term. The unemployed category has the highest median borrower rate. Unemployed individuals pay more interests on loans.
- The loan amount increases with better rating and the borrower APR decreases with better rating.
- For AA-B ratings, the APR increases with the increased of loan term. The APR decreases with the increased of loan term for C to HR ratings. 

## Key Insights for Presentation

For the presentation, I focused on features that could affect the borrower APR, which are original loan amount, Prosper rating. I showed the distribution of the borrower APR, loan amount and ProsperRating (Alpha) variables. Then, I showed the relationship between APR vs. loan amount. I also showed the multivariate relationship between rating, loan term and APR. 
