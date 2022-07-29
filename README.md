# Prosper Loan Dataset Exploration
## by Wilson Okah


## Dataset

> This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others.
 The dataset can be found [here](https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv),
with feature documentation available [here](https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0).


## Summary of Findings

> The original loan amount is a multimodal distribution with peaks at 5000,10000,15000,20000,25000, which shows most loans were multiples of 5000 and the majority of borrowers requested for within the range of 4000-15000. Very few borrowers took loans above 25000. The Loan Amount has a strong positive correlation with monthly loan payments and has a positive correlation with the stated monthly income. It negatively correlated with the BorrowerAPR, LenderYield and the borrower's Rate. The original loan amount gives a right-skewed distribution plotted by employment status and Borrowers state. Most of the distribution belongs to the employed borrowers, and most borrowers are from CA. There was a rise in the loan amount requested by borrowers up till 2007, then a sharp decline in the loan amount till 2009, and then a steady increase in Average loan Amount between 2010 and 2014. The average original loan amount by year is greater than the average Yearly loan payment made, with a decline between 2007 and 2009.After a closer look at the average amount earned by the month in the five states with the most borrowers and the five states with the Least Amount of borrowers. I saw a trend that shows the more the average income in a state, the higher the loan amount revealing a linear trend and showing a strong correlation with  one another   
there seems to be a positive relationship between the original loan amount  and the term, the Original loan Amount and the  credit rating
The higher the credit score range, the higher the loan amount you would be able to borrow There is a strong positive relationship between the loan amount and monthly payment across every employment and as previously seen in the scatter plot in the bivariate plot scatter plot of the Loan amount and monthly payment there was a separate linear trend outside the in the plot the facet grid revealed that the employed employment status is responsible for this separate trend The income range shows a somewhat positive relationship with the Loan original amount There is no apparent correlation. Still, a linear trend can be seen in the stated income and loan amount. The income Range of 0 dollars has an outlier at 20,000 dollars, and some people have stated monthly income above 5k dollars. The higher the income range you belong to, the higher the loan amount you would have access to 

> 

## Key Insights for Presentation

> I focused on the influence of the Income range, Loan term, monthly income, credit grade, credit
score and the borrower's state on the Loan Amount.
I start by introducing the Loan Amount variable, followed by the pattern in Monthly income distribution, then the distribution of the credit score lower range, 
I introduced the categorical variables like the income range, credit score levels, borrower's state and credit grade. Boxplots, violin plots and trend lines were used to show the relationship between this variables and the original loan amount.
A scatter plot is used to show how the Loan Amount correlates with the Monthly loan payment. The states with the most borrowers were gotten and their average income and average loan amount was ploted to show the correlation betwwen higher income and higher loan Amount.