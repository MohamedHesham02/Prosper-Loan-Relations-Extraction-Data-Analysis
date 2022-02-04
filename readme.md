## Exploring prosper loan Dataset to find some insights and guides
***

* Dataset Overview 
***
### Dataset have 81 features of loaners 
### Due to problem of exploring 81 feature, in the project I tried to explore some of the imortant features which are:

 1- Homes Ownership
 2- Borrower's Annual Percentage Rate
 3- Loan Status
 4- Borrower Rate
 5- Estimated Loss
 6- ProsperRating (Alpha)
 7- Borrower State
 8- Employment Status
 9- Available Bankcard Credit
 10- IncomeRange
 11- Current Credit Lines
 12- Loan Original Amount
 13- Percent Funded
 14- Investors
 15- Recommendations
 16- Borrower State

* Some of the questions we want to find out their answers 
***
 What factors affect a loan’s outcome status?
* What affects the borrower’s APR or interest rate?
* What's the relation relation between Credit Lines, Income Range and Employment Status?
* What's the most probable city of borrowers ?
* What's IncomeRange Percantage between variety of loaners?
* relation bbetween loan status and original amount of loan

* Used Explorations:
***
#### Univariate Explorations used in:
  *   Homes Ownership
  *   Loan Status
  *   Prosper Rating (Alpha)
  *   Employment Status
  *   Income Range
  *   Borrower State

#### Bivariate Explorations used in:
  *    estimated loss
  *    no. of credit lines
  *    interest rate
  *    BorrowerAPR
  *    Income Range
  *    Borrower State
  *    Loan Original Amount
  *    Available Bankcard Credit
  *    Loan Status
  *    Investors
  *    Percent Funded
  *    Recommendations

#### Multivariate Explorations used in:
  *    estimated loss
  *    no. of credit lines
  *    Employment Status
  *    Homes Ownership
  *    Income Range
  *    Borrower State
  *    Prosper Rating (Alpha)
  *    Loan Original Amount
  *    Available Bankcard Credit

* Findings
***
 * 1- There's no relationship between home ownership and the loaning
 * 2- At the low and high CurrentCreditLines there're people with low and high EstimatedLoss value so, also there's no relationship
 * 3- There's a clear direct propotion between Borrower Rate and annual percentage rate
 * 4- There is a dense amount of people of employed and fulltime categories in 5 variable income ranges
 * 5- Its obvious that most of self employed are in 0 income category and the limit of no. of credit lines of self employed is 30 
 * 6- The most probable city of borrowers is in CA city, That might be give indications of costy life in the city or high life of investment in the city population
 * 7- 25K - 50K is the most income appeared between loaners 
 * 8- There's an increment betweeen the amount of loaners who have 100K income
 * 9- There's an increment in credit with loaners who have 100K income and also this category from the least people who have no. of loaners
 * 10- It's found that most of 100K income category own home and in 2 catgories( not employed and 0 to 25K) most of them don't own home
 * 11- There is very little amount of people cancelled and most of them in current state and have high loan originals amount
 * 12- The highest percentage in current and completed states and how are about to finish in rest of categories are very low
 * 13- It's found that most of loaners have 100% funding and most of them have investors more than 400 investors
 * 14- It's found that most of loaners don't have recommendations to investors

* Key Insights
***
#### In my plots, I was taking into consideration to have a high related plots to the income of the loaners, their economical state, employment type and other related features to effictively find out the reasons of loan and can be paied again or not 
#### Any plot in the presentation should be very clear for visulaizations and have good colors 

* Relevant and Required Software:
***
 * This analysis is enhanced using python and related analysis libraries like: Pandas, Matplotlib, Numpy and Seaborn 
 * Also, In other enhancements Tableau and Power BI are important tools for data analysis and building valuable insights 

* Files included in the project:
***
  * 2 Notebooks:
  * A data exploration notebook
  * A slide show/presentation notebook
  * 2 HTML files:
  * A data exploration HTML file
  * A slide show/presentation HTML file



