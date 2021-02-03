# Proper Loan Data Exploration
## by Ghada Maher


## Dataset

> The Dataset consists of information regarding various factors and variables in Loans given by Prosper Loans from year 2006 to 2014.
This document explores a dataset contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others.

- [This data dictionary](https://www.google.com/url?q=https://docs.google.com/spreadsheet/ccc?key%3D0AllIqIyvWZdadDd5NTlqZ1pBMHlsUjdrOTZHaVBuSlE%26usp%3Dsharing&sa=D&ust=1602316069252000&usg=AOvVaw30T5Cb1SJcH_-mM-PE6sWH) explains the variables in the data set.


## Summary of Findings

- The prosper rating and score distribution is normal, most term used is 36 Months and most of the individuals income range falls between 25,000 and 75,000.
- The distribution of `BorrowerAPR` is approximatly normal with a mean of 22.26%, median of 21.47%, minmun rate of 0.65% and maximum of 51.23%. and most of the values ranges between 10% and 45%.
- Most of the Borrower was from California followed by Florida and Texas.
- There is a postive relatioship between `ProsperScore` and `LoanOriginalAmount`.
- There is a negative relationship between `BorrowerAPR` and `ProsperScore`.

- The most status is Current followd by completed, Chargedoff and Defaulted and Canceled loans are almost 0.
- The distribution of APR looks multimodal.There are a small spike centered at 0.1, a large spike centered at 0.2. There is also a small spike centered 0.3. Additionally, there is a very shape spike at rate = 0.36. Only very few loans have APR greater than 0.43 and most of the values ranges between 0.10 and 0.35.
- The most common Income Range was between 50k and 75k with about 24000 borrowers, then comes the range between 25k and 50k with 22000 borrowers.
- Maximum count of Loan's Original Amount belongs to the range 2000-6000$.
- There is no clear relation between BorrowerAPR and the payment Term.
- The BorrowerAPR is lower for Homeowners than if the individual doesn't own a house.
- Not employed idividuals have the highest APR for current loans.
- Current Loan Status has the lowest BorrowerAPR followed by completed Loan Status
- Completed, charged off and defaulted categories have the lowest LoanOriginalAmount according to EmploymentStatus.



## Key Insights for Presentation

> For the presentation , I focus on relationships between different variables and how they affect the Borrower's APR and how other features affect the loan status. Firstly, I introduce each variate by showing their distribution, and then start to combine two variable to see their correlation.Finally, I plot 3 variables to detect the relationship between variables.