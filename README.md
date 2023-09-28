# Prosper Data Exploration
## Introduction

This is a Udacity project. The task is to perform an Exploratory Data Analysis using Python and to create a presentation with explanatory plots that convey my findings.

## Dataset

This data set contains 113,937 loans with 81 variables on each loan, including 
loan amount, borrower rate (or interest rate), current loan status, borrower income, 
and many others. The dataset is too large for GitHub. So, It can be found [here](https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv&sa=D&ust=1581581520570000)

## Data Wrangling

The following data wranglings were performed before I started the exploration: 
1. Selected my variables of interest
2. Changed the data type for the listing creation date column
3. Filled the null values in credit grade and prosper rating columns
4. Renamed the listing category column and created a new average credit score column
5. Deleted extraneous columns
6. Updated the numeric values in the Listing category column and updated the 
Employment status column
7. Removed the null values and
8. Removed the duplicated rows


## Summary of Findings

In the exploration, I found out that the loan borrower rate with the highest frequency
was around 14%. While the borrower rate was between 5% and 35%. Prosper mostly gave 
out loans below $5,000 and required a credit score between 650 and 750. Most of 
the loans are current, completed and C-grade loans. The majority of the loans were 
obtained to pay back other loans. Most borrowers are employed and have a yearly income 
range above 25000.

I found out that there was a positive correlation between borrower rate and 
the following variables: the rating grade, term of loan, and debt-to-income ratio. 
There was a negative correlation between borrower rate and the following 
variables: monthly income, employment duration, credit score and loan 
amount. Current, completed and final payment loan status seemed to have lower 
borrower rates and debt-to-income ratios on average compared to loans charged-off 
or past due dates.

The negative correlation between the borrower rate and the loan amount was surprising. I 
discovered that the rating grade attached to a loan seemed to be the main indicator of 
the borrower rate. So, irrespective of the loan amount, the risk attached to the 
loan determines its borrower rate.

## Key Insights for Presentation

For the presentation, I focus on just the influence of the loan amount, monthly 
income and credit grade on borrower rate and leave out other variables in the 
dataset because these selected variables seem to have a major influence on the 
borrower rate. I start by introducing the borrower rate variable followed by 
pattern in the loan amount variable and then show the purpose of the loans with 
a bar chart of the listing category variable.

Afterwards, I plot the relationship between the loan amount and interest rate using 
a scatter plot. I show the relationship between monthly income and borrower rate 
and facet by loan amount. I use a sequential colour palette to represent the 
different loan amounts.

I plot the relationship between rating grade and borrower rate using a box plot. 
Afterwards, I divide the data by the level of rating grades and plot the 
relationship between monthly income and borrower rate. I have made sure to use 
different colour palettes to represent each rating grade.

## Feedback from Udacity reviewer
View the feedback [here](https://drive.google.com/file/d/1nWCkORIO8vwVC1g16F3MSZKeZzdzyDjz/view?usp=sharing)

Warm Regards,
#### Olamide Emida
