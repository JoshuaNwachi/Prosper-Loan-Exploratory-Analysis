# Prosper Loan Exploratory Analysis
## by Nwachi Joshua


## Dataset

The prosper loan data set contains 113,937 loans with 81 different variables for each loan, such as the loan amount, the interest rate paid by the borrower, the loan status, the borrower's income, and many more. The dataset is available  [here](https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv&sa=D&ust=1581581520570000).  [Here](https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0) is a variable description


## Summary of Findings

Based on the investigation, the following findings were observed:<br>
1. The distribution of borrower APR, borrower rate, lender yield, and estimated effective yield were symmetrical with a spike in the 3.0-4.0 range for borrower APR, borrower rate, and lender yield.<br>
2.	Homeownership appeared to have an impact on loan performance, with the most common loan status for both homeowners and non-homeowners being "Active", followed by "Completed", and a higher number of "Defaulted" loans for non-homeowners compared to homeowners.<br>
3.	The loan amount was right-skewed and most loans were for amounts between 1000-5000. The most popular loan origination months were January, October, and December. The majority of loans had a term of 36 months.<br>
4.	The numerical variables in the dataframe showed a negative correlation between borrowerAPR and borrower rate and a high correlation between borrower rate and borrower APR. The loan original amount and borrower APR also showed a negative correlation.<br>
5.	Borrower's income range appeared to have an impact on the borrower APR, borrower rate, and debt-to-income ratio, with higher income resulting in lower borrowing costs and improved loan repayment prospects.<br>
6.	Prosper risk level appeared to impact the loan original amount and monthly loan payment, with higher risk levels resulting in smaller loan amounts and lower monthly payments.<br>
7.	The loan original amount had a strong relationship with the monthly loan payment, but little to no correlation with the stated monthly income.<br>
8.	There was a relationship between the listing category and lender yield or monthly loan payment, where certain categories like business, debt consolidation, and large purchases resulted in lower lender yield and monthly loan payments. <br>
9.	The average loan original amount showed an upward trend over time with a slight dip observed during 2008-2009.<br>
10.	Borrowers with verified income had a higher average loan amount compared to those with unverified income.<br>
11.	Higher income borrowers were more likely to own a home, employed and full-time borrowers were more likely to take out loans with a term of 12 months, and the Prosper rating was positively correlated with a low Prosper risk level.<br>
12.	The relationship between the loan original amount and borrower's APR was found to be negative and as the loan original amount increased, the borrower APR decreased.<br>
Overall, these findings provide valuable insights into the various factors that impact loan performance and can help inform lending decisions and strategies.



## Key Insights for Presentation

I focused my presentation on exploring the various factors that influence loan performance. I started by showing the distribution of the borrower APR, borrower rate, lender yield, and estimated effective yield then i went on explaining the relationship between homeownership and loan performance.<br>
Next, I highlighted the impact of income on loan metrics such as the borrower APR, rate, and debt-to-income ratio. I then delved into the effects of Prosper's risk level on loan original amount and monthly payments. Finally, I concluded by showcasing the upward trend in loan collections by individuals over time.
