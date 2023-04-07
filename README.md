# Data Findings from Prosper Loan Dataset
## by Victoria Edem Effiwatt

## Project Overview 
This project has two parts that demonstrate the importance and value of data visualization techniques in the data analysis process.

In Part I, Exploratory data visualization, I use Python visualization libraries to systematically explore the Loan dataset from Prosper, starting from plots of single variables and building up to plots of multiple variables.


In Part II, Explanatory data visualization, I produce a short presentation that illustrates interesting properties, trends, and relationships that I discovered in the Loan dataset. The primary method of conveying my findings is through transforming my exploratory visualizations from the first part into polished, explanatory visualizations.


## Installation
This project uses Python 3 and was completed through the Jupyter Notebooks IDE. I used the following libraries in this project:

##### NumPy
##### pandas
##### Matplotlib
##### Seaborn

## Dataset

 The dataset is from Prosper. Prosper is a lending platform that allows investors to choose among personal loans to invest in. They do that by considering a number of factors, which include loan amount, borrower rate (or interest rate), current loan status, borrower income, a custom calculated Prosper Score that represents the risk for each loan, and many others. 
 
The dataset initially contained 113,937 loans with 81 variables on each loan.  This [data dictionary](https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0) explains the variables in the dataset. I did some data wrangling and picked only columns I needed for the exploration I planned to do. After wrangling, the new dataset had 77,543 loan listings and 19 variables, and is found in the "ProsperLoanDataClean.csv" file.


## Summary of Findings

1. In the exploration process, I observed that borrowers who are homeowners, whether employed or not employed receive higher loan amounts from Prosper Loans compared to borrowers who are not homeowners. 

2. After examining the relationship between LoanTerm, ProsperScore, and LoanOriginalAmount, I observed that Loan Term influences the loan amount given out. 
   The loan amount given to borrowers is also influenced by the Prosper score (risk score), so borrowers with low risk scores are more likely to receive higher loan amounts. Therefore, the higher the Loan Term, and the higher the risk score(Prosper Score), the larger the Loan Amount received by borrowers. This could be because lenders are more open to giving out loans to borrowers who they don't assess as risks(for defaulting), and providing a long term to pay back the large Loan amount as an assurance.

3. I also observed from the relationship between loan amount and loan status that majority of borrowers with past due(>120 days) payments took relatively higher amounts of loans, this could be a factor in why they're not timely with payment. 


## Key Insights for Presentation

##### For this presentation, I focus on the influence of a borrower's features (being a home owner, employment status, prosper score, loan term, etc) on loan amount given to borrowers. 
##### I introduce the distribution of the Loan Amount variable, followed by the distribution of the loan status, bivariate exploration, and then multivariate exploration. 
