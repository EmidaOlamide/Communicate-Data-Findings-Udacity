# Prosper Data Exploration

## Dataset

This data set contains 113,937 loans with 81 variables on each loan, including 
loan amount, borrower rate (or interest rate), current loan status, borrower income, 
and many others. The dataset is too large for GitHub. So, It can be found [here](https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv&sa=D&ust=1581581520570000)

The following data wrangling were performed before I started the exploration: 
1. Selected my variables of interest
2. Changed the data type for the listing creation date column
3. Filled the null values in credit grade and prosper rating columns
4. Renamed listing category column and created a new average credit score column
5. Deleted extraneous columns
6. Updated the numeric values in the Listing category column and updated the 
Employment status column
7. Removed the null values and
8. Removed the duplicated rows


## Summary of Findings

In the exploration, I found out the loan borrower rate with the highest frequency
was around 14%. While the borrower rate was between around 5% and 35%. Prosper gave 
out mostly loans below 5000 and required credit score between 650 and 750. Most of 
the loans are current, completed and C grade loans. And loans were mostly obtained 
by borrowers to pay back other loans. Majority of the borrowers are employed and 
have a yearly income range above 25000.

I found out that there was a postive correlation between between borrower rate and 
the following variables: the rating grade, term of loan, and debt to income ratio. 
And there was a negative correlation between borrower rate and the following 
variables: monthly income, employment duration, credit score and suprisingly loan 
amount. Current, completed and final payment loans status seemed to have lower 
borrower rates and lower debt to income ratios on average compared to loan charged 
off or past due dates.

The negative correlation between borrower rate and loan amount was suprising and I 
discovered that rating grade attached to a loan seemed to be the main indicator of 
the borrower rate. So irrespective of the loan amount, the risk attached to the 
loan determined its borrower rate.

## Key Insights for Presentation

For the presentation, I focus on just the influence of the loan amount, monthly 
income and credit grade on borrower rate and leave out other variables in the 
dataset because these selected variables seem to have the major influence on the 
borrower rate. I start by introducing the borrower rate variable followed by 
pattern in the loan amount variable and then show the purpose of the loans with 
a bar chart of the listing category variable.

Afterwards, I plot the relationship between the loan amount and interest rate using 
a scatter plot. I show the relationship between monthly income and borrower rate 
and facet by loan amount. I use a sequential color palette to represent the 
different loan amounts.

I plot the relationship between rating grade and borrower rate using a box plot. 
Afterwards, I divide the data by the level of rating grades and plot the 
relationship between monthly income and borrower rate. I have made sure to use 
different color palettes to represent each rating grade.

## Feedback from Udacity reviewer
View the feedback [here](https://drive.google.com/file/d/1nWCkORIO8vwVC1g16F3MSZKeZzdzyDjz/view?usp=sharing)

Warm Regards,
#### Olamide Emida
