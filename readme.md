# (Ford GoBike System Data)
## by (Ahmed Khaled Mohamed)


## Dataset

> It is the prosper loan data set, that contains information about loan listings and related variables including borrower as well as lender information. It contains variables related to Borrower such as credit rating, prosper rating etc. Moreover, the dataset also has lender information.

> The Prosper loan dataset contains 113,937 observations of 81 variables. The observations refer to loan listings on Prosper.com from late 2005 until 2014, and various characteristics of those loans. The data seems “tidy,” according to Hadley Wickham’s definition: the variable names are not variables themselves, so there is not much work required in the way of “tidying” the data.


## Summary of Findings

In this analysis, I ran into difficulties from the sheer size of the data set. Not so much from the 114K observations, but from the 81 variables. There were so many different ways to slice and dice the data that it was easy to get lost at times. It also prompted me to ask some questions of the data that probably can’t be answered. For example, I wanted to reverse engineer the Prosper Score and Prosper Ratings algorithms, which I later learned wasn’t really possible.

Our initial assumptions were strengthened. The outcome of credit depends on Prosper raing, Term, Employment status. Defaulted credits tend to be larger than completed for all ratings except the lowest ones. In terms of purposes of credits more default prone are other and business categories (business category also tend to have larger loans). Long term (60 months) loans are riskier than mid-term and short term.

I extended my investigation of borrower APR against loan amount by looking at the impact of the Prosper rating. The multivariate exploration showed that the relationship between borrower APR and loan amount turns from negative to slightly positive when the Prosper ratings increased from HR to AA. I then explored the rating and term effects on loan amount, it shows that with better Prosper rating, the loan amount of all three terms increases, the increase amplitude of loan amount between terms also becomes larger.

## Key Insights for Presentation

> Investor number depend on the commetment of the borrower and it's highest credet grade and the lowerest risk of propsper score and lowest debt to income ratio.
> The loan amount increases with better rating. 
> The borrower APR decreases with better rating. Interestingly, the relationship between borrower APR and loan amount turns from negative to slightly positive when the Prosper ratings are increased from HR to A or better. 
> he borrower APR decreases with increasing Prosper rate. But for people with 4.0,7.0 ratings, the APR increase with the decrease of borrow term. 
> Debt to income ration decreases with increasing the prosper score.
> The Loan original quarter increases with moving forward in years and increases it's duration. The higher prosper score is nearly vanished in earlyer years from 2009 to 2011.
> BorrowerAPR and EmploymentStatus for loan terms to find the most distributed data in whole loan term is employed status followed by full time status.
> ProsperScore and EmploymentStatus investigation to find middle ratings seem to have greater proportions of individuals with employment status.