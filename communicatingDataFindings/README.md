# Communicate Data Finding : PROSPER LOAN DATA
## by Edwin Kihara


# What the Project will test 

* Introduction of the topic and dataset
* Dataset Investigation and preliminary wrangling
* Further Data Wrangling
* Univariate Exploration and Analysis
* Bivariate Exploration and Analysis
* Multivariate Exploration and Analysis
* Conclusions and answers


## Dataset

> - Loan Data from Prosper: This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others.
> - The source data (Prosper Loan Data) was from Udacity website.



### Features :

The Features included in the Data are as follows :

- LoanStatus
- LenderYield
- ProsperRating (numeric)
- ProsperScore
- ListingCategory (numeric)
- Occupation
- EmploymentStatus
- IsBorrowerHomeowner
- CurrentDelinquencies
- AmountDelinquent
- DelinquenciesLast7Years
- IncomeRange
- TotalProsperLoans
- OnTimeProsperPayments
- BorrowerState
- Investors
- LoanKey
- MemberKey


### Questions to be answered: 

1. Category that the borrower selected when posting their listing.
2. Number of prosper score rating for every loan.
3. What is the current loan status for most loans.
4. Who takes the most loans according to employment status.
5. Which occupation has the largest largest number of borrowers.


### Summary of Findings

> From our data analysis it can be observed that most of the loans customer had, were at the point of listing is 1(Debt consolidation category).
> The number of loans increased significantly as there was an observed increase in properscore, except for properscore between 9 and 10, the data as well had an outier on the prosperscore which was 11 and contained 823 records.
> We can say that those who earn more tend to acquire more loans, this is as observed from income range where those on thwe highest income range were the highest borrowers
> We can see that the status of most loans are current with a percentage of 57%.A positive repayment trend is observed, having most loan status completed at a percentage of 34% compared to those that have been defaulted at a percentage of 2%.
> We can observe that people who are employeed take the most loans, with those who are Full time employeed leading followed by those who are Self employeed.
> From observation, we can see that professional occupation have the highest borrowers, when we discard other and professional the top 3 most occupation with borrowes is Computer programmer, Executive and Analyst.
