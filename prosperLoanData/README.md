# prosperLoan Data Exploration

## Dataset

The dataset containing 113 937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others. 


## Summary of Findings

in the exploration, i found that only the Current and completed classes can relatively be deduced from certain numerical characteristics such as BorrowerAPR (The Borrower's Annual Percentage Rate (APR) for the loan), and categorical characteristics such as not belonging to a group, being of class 1 (Debd consolidation), being an employee, living in California and have an estimated loan term of 36 months.

Another class of LoanStatus can be deduced, but with a lower degree of certainty (Other class of Occupation, 1(Debd consolidation) of ListingCategory (numeric), full-time of EmploymentStatus, CA(California) of BorrowerState and 36 of Term). This is the Completed class.

As for the correlations between the variables, we realized that there is a very good linear correlation between the numerical variables (BorrowerAPR, BorrowerRate and LenderYield). However, only the EmploymetStatusDuration variable has no correlation with the others, even after performing a logarithmic transformation.



## Key Insights for Presentation

For the presentation, I focus on the identification of factors affecting loan's outcome status.

I start by introducing the LoanStatus variable followed by the distribution of BorrowAPR.

Afterwards, I introduce by displaying the BorrowerAPR distribution for each class in the LoanStatus column.
After that, i focus my observations in a categoricals values (EmploymentStatus) and one boolean variable (CurrentlyInGroup) because those variables allow to identify some lon's statuts outcomes. I've made sure to use different color palettes for each quality variable to make sure itis clear that they're different between plots.

