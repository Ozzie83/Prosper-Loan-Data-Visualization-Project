# An Exploratory Analysis of Loan Data from Prosper MarketPlace 
## by David Eruemu


## Prosper Loan Dataset (2005-2014)

 > This is an exploratory analyis of loan data from Prosper MarketPlace, a peer to peer lending industry. This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others.
 > For this analysis, '$0' income range was merged with not employed and the different stages of past due('Past Due (1-15 days)', 'Past Due (31-60 days)',
       'Past Due (61-90 days)', 'Past Due (91-120 days)',
       'Past Due (16-30 days)', 'FinalPaymentInProgress',
       'Past Due (>120 days)') were condensed into one as they both convey the same message. The numeric values of the listing category were also replaced with what they represented


## Summary of Findings

> The correlation between the yield and the amount gets stronger as the loan term increases
>There is a three way correlation between the borrower apr, estimated return and lender yield
>BorrowerRate ,BorrowerAPR ,Term , LenderYield , EstimatedEffectiveYield, EstimatedLoss, and EstimatedReturn all have high correlation between each other.
>The percentage of 'charged off', 'defaulted' and 'past due' loans decreases as the prosper rating increases.
>Another noticeable feature would be the relative increase in $100,000+ earners as the rating increases as well as a decrease in unemployed and low earners.
>The median Debt to Income Ratio slightly increases as the income range decreases.The standard deviiation also increases as the income range decreases. The $75,000-$99,999 range has the smallest spread
>The median Debt to income ratio is similar across prosper ratings. The major difference is the distribution. The kernels become more triangular and the standard deviation decreases as the rating increases
>the larger spread of the distribution of loan original amount as the Income range increases. The median loan amount increases asthe income range increases
>The frequency of loans taken out for debt consolidation increases with the income range while the frequency of loans taken out for household expenses decreases.
>The frequency of business loans increases with the income range with an exception for the unemployed.

## Key Insights for Presentation

> The distribution of income ranges 
> How the prosper ratings are distributed across income ranges
> The distribution of Debt to Income Ratio
> The relationship between the Debt to Income Ratio and the prosper rating.
> The relationship between the Debt to Income Ratio and income range.
> The distribution of Listing categories
> The relationship between listing categories and income ranges

####  No major changes were made to the design of illustrations from the exploratory phase to the expanatpry phase. Minor changes include a change in scale to make it more visually appealing to an audience and more descriptive axis labels and titles for clarity.