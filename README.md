# (Loan Data from Prosper)
## by (Victoria Edem Effiwatt)


## Dataset

 The data set is from Prosper and it initially contained 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others. This [data dictionary](https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0) explained the variables in the data set. I did some data wrangling like changing the data type of some columns, and picking only columns I needed for the exploration I planned to do. After wrangling, the subset of the dataset had 77,543 loan listings and 19 variables. Some variables were numeric and others categorical.


## Summary of Findings

> In the exploration process, I observed that borrowers who are homeowners, whether employed or not employed receive higher loan amounts from Prosper Loans compared to borrowers who are not homeowners. 

> After examining the relationship between LoanTerm, ProsperScore, and LoanOriginalAmount, I observed that Loan Term influences the loan amount given out. The loan amount given to borrowers is also influenced by the Prosper score (risk score), so borrowers with low risk scores are more likely to receive higher loan amounts. Therefore,the higher the Loan Term, and the higher the risk score(Prosper Score), the larger the Loan Amount received by borrowers. This could be because Lenders are more open to giving out loans to borrowers who they don't assess as risks(for defaulting), and providing a long term to pay back the large Loan amount as an assurance.

> I also observed from the relationship between loan amount and loan status that majority of borrowers with past due(>120 days) payments took relatively higher amounts of loans, this could be a factor in why they're not timely with payment. 



## Key Insights for Presentation

> For this presentation, I focus on the influence of a borrower's features(being a home owner, employment status, prosper score, loan term, etc) on loan amount given to borrowers. I introduce the distribution of the Loan Amount variable, followed by the distribution of the loan status followed by bivariate exploration and then multivariate exploration. 
