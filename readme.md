# Prosper-Loans-Data Analysis
## by Sash


## Dataset

> This project is on a data set from Prosper, which is America’s first marketplace lending platform, with over $7 billion in funded loans. This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), borrower income, borrower employment status and housing status, borrower credit history, and the latest payment information.

## Investigation Overview

> The main purpose of this project is to summarize the characteristics of variables that can affect the loan status and to get some ideas about the relationships among multiple variables using summary statistics and data visualizations. I am most interested in figuring out the features which are benefecial for receiving loan from Prosper. 

## Summary of Findings

> I started by looking at the main variable of interest i.e. ProsperScore. Plotting IncomeRange, EmploymentStatus and Term to further explore the data. Statistical Correlation between the selected numerical variables of the dataset are displayed. The relationship between AvailableBankcardCredit vs. BorrowerRate is identified. Analysing how the BorrowerRate changed over years for Homeowners vs Non-Homeowners and also analysing BorrowerAPR vs ProsperScore on difference letter ratings. 
> BorrowerAPR vs. CreditScoreRangeUpper & ProsperScore is visalised which is found to be negatively correlated to Borrower APR. The effect of TotalCreditLinespast7years and IncomeRange for BorrowerRate and LoanOriginalAmount is presented. Colorful investigatation is done to ascertain the effect of IncomeRange on the relationship between BorrowerRate and LoanOriginalAmount. Effect of ProsperScore, the relationship between BorrowerRate and LoanOriginalAmount is visualised and also the effect of IncomeRange on ProsperScore and BorrowerRate relationship.

## Key Insights for Presentation

> Prosper principal borrowed is higher with high income range customers. Prosper score is more of high income customers.

> In the Bivariate part of the analysis, AvailableBankcardCredit is contrasted to BorrowerRate and Income range towards ProsperPrincipalBorrowed. Also, BorrowerRate pattern has been analysed over years. The relationship was that the less borrower rate when more bank credit is available. In the second one, the relation is that the propser principal borrowed is directly correlated to the income range excluding 0 or not employed. In the third graph, a pattern has been deciphered which shows that the rate of interest increased from 2005-2006 and then fell off from 2006-2007 and then it constantly picked up for few years, reached its peak in 2011 which then started decreasing constantly.

> Multivariate Analysis- Borrower rate increased for some years in case of non homeowners, however it constantly decreased around 2010. As regards of homeowners, there wasn't much difference till 2009 but after 2009, the graph went up till 2011 and started falling off from then. While analysing Borrower APR vs Prosper score, the patterns shows the lowerest rating(HR) of borrowers have the highest APR. For high rating A(A), the borrowers has lower APR. The visualization differenate groups of people in terms of APR received based on their rating and scores. ProspoerScore gives the strongest negative relationship to BorrowerAPR.

>TotalCreditLinespast7years does not play a significant role on controling the BorrowerRate and LoanOriginalAmount relationship.
only those who has a IncomeRange above 100k, are borrowing higher LoanOriginalAmount (>25K) and their BorrowerRate is <0.15.
Note that, there are other examples which are not following the same trend. For example, you may find, people with a IncomeRange above 100k who has lower LoanOriginalAmount and higher BorrowerRate.

> In general, increasing ProsperScore decreases BorrowerRate. Apparently, people with lower IncomeRange have higher BorrowerRate at each individual ProsperScore.

