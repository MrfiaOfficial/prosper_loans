# (Prosper Loans Data Exploration)
## by: Ige Amos Fadele


## Dataset

The dataset contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others.

The dataset can be found on this link **https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv**

The complete data dictionary which can be found on this link **https://www.google.com/url?q=https://docs.google.com/spreadsheet/ccc?key%3D0AllIqIyvWZdadDd5NTlqZ1pBMHlsUjdrOTZHaVBuSlE%26usp%3Dsharing&sa=D&ust=1554484977407000**. The data disctionary explains all the variables in the data set.


## Summary of Findings

There are a lot of interesting findings from the data exploration, however they their summary is presented here.
The loans that were completed successfully happens to have the lowest interest rate (BorrowerRate), while the three negative loans outcomes (past due, Chargedoff, Defaulted) happen to have the highest interest rate.
Interestingly, Prosper rating and Interest rate (BorrowerRate) have a negative relationship. The better the Prosper rating, the lesser the interest rate.
As one would expect, Borrowers with lower Credit score are found with Cancelled, Chargedoff and Defaulted loan statuses. And those whose loan status are Defaulted, Past-due and Chargedoff happen to have the highest interest rates (Borrower Rate), Also, Cancelled loans happens to have the lowest Loan amount and the loan amount for Current loans happen to be the highest.
These findings depict that Borrower Rate (Interest Rate), Prosper Rating and Credit Score affect loan outcomes.

In addition, we found out that Prosper gives loans more to those that are employed (apart from those that are part-time employed), full-time employed and those that are self-employed than other groups of people. It's common sense that a Loan company would prefer to give a loan to someone that well employed than someone who is not fully employed, since a borrower needs a suitable source of income to pay back a loan as required. Also we discovered that Borrower's homeownership does not seems to pose as a yardstick for getting loan as the number of borrowers who are homeowner and those who are not are almost thesame. It's worth mentioning also that 36 months happened to be the most popular Loan Term.


## Key Insights for Presentation

For this presentation, I focus on Loan Status (Loan outcome) feature which is the feature of interest and other four selected features which happen to have more influence on the loan outcomes. These features are Borrower Rate (Interest rate), Credit Score, Prosper Rating, and Loan Original Amount.

Firstly, I plotted the distribution of the loan outcomes (seven loan statuses/categories) and then moved on to create a Correlation plot for the three numerical variables from the selected features stated earlier and also substantiated this with a Plot Matrix. After this I progressed to create a Clustered Bar chart for the relationship between Loan Status and Prosper Rating.

To round things off, I created a PairGrid Boxplot so as to check the relationship between the numerical features (Credit Score, Loan Original Amount, Borrower Rate) and categorical features concerned (Loan Status, Prosper Rating).

