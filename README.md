### Advanced Exploratory Analysis on Bank Loans 

The main purpose of this project is to analyse the factors that contribute to changes on the borrower Annual Percentage Rate (APR) for a loan. After a comprenhensive exploratory analysis, the selected variables to be invistaged are ProsperScore, ProsperRating (Alpha), LoanStatus and loan amount. Python visualization libraries are used to systematically explore a selected dataset, starting from plots of single variables and building up to plots of multiple variables and producing a summary highlights showing trends and relationships discovered in the Loan Data from Prosper. The Jupyter Notebook is coverted into an HTML slideshow presentation.

Questions to be explored:
What factors affect a loan’s outcome status?. The variables to be considerred are as follows.
Employment status
IncomeRange
Prosper Score
Home owner status
Borrower State
What affects the borrower’s APR or interest rate?
Loan original amount
Listing Category

##### Summary of Findings

It seems the main variables impacting Borrower APR are ProsperScore and ProsperRating with a negative correlation. ProsperScore seems to increase when BorrowerRate decrease.

Another relevant find is that Borrowers with different letter ratings were also analyzed. It came out that borrowers with the lowerest rating(HR) received higher APR percentage, and borrower with high rating A(A) received lowers APR percentage. This differentiate groups of people in terms of APR received based on their rating and scores.

In the exploration stage, I found the following relevant inights:
- It seems the main variables impacting Borrower APR are ProsperScore and ProsperRating with a negative correlation. ProsperScore seems to increase when BorrowerRate decrease
- Another relevant find is that Loan Amount increases when Borrower APR increases. 
- The loan status current is correlated wiht high ProperScore. It seems that Borrowers APR decrease the higher the income range
- It appears that the higher the ProperScore, the lower the borrower APR wiht current status and charge off as main loan status
- It seems the borrower APR increases when borrowers are retired and self-employed. It also increase when borrowers do not own their home
- It seems that most of the defaulted credits comes from individuals with low Prosper ratings

##### Key Insights for Presentation

Based on the visual analysis and answering the question posted in the introduction  it is concluded that:

Employment status, income, home owner status are variables that appear to impact the loan outcome and Borrower APR. That means that clients that are full time employed, with average incomes and owners of homes are seen to obatianed a higher Proper Score that ultimalety allows then to get a current loan.

It is also noticed that loan amonts are higher when the Proper Score is hig. 

A statistical analysis and modelling is necessary after the Exploratory Data Analysis is underatken to make definitive assertions on the relationhsis and impacts of variables.

   
