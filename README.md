# Lending Club Case Study
> The aim of this project is to analyse and understand the factors that can cause loan default. Repository contains data files, step by step analysis and pictorial represenations.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
Lending Club is a marketplace for personal loans that matches borrowers who are seeking a loan with investors looking to lend money and make a return. When the applicant drafts his or her willingness for loan, the company must check the eligibility of each customer before processing a loan. There are two types of risks associated with the bank's decision
- If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company
- If the applicant is not likely to repay the loan, i.e., he/she is likely to default then approving the loan may lead to a financial loss for the company.

Company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.
Dataset provided contains complete loan data for all loans issued through the time period 2007 t0 2011 by the financial organisation used in this project.

Approach followed is to use following EDA techniques to derive required observations.
- Data Understanding
- Data Cleaning (Missing values, Outliers, Dropping not required data, etc)
- Variable Analysis (Univariate, Bivariate, Multivariate)
- Visual Analysis (Plotting - easy to derive insights)

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
Summary for the provided data:
- ~15% of the loans are currently defaulted   
- Highest number of loans approved are for Debt Consolidation category
- Majority of the people who are taking loans and defaulting are living in rented and mortgaged homes
- Average interest rate is around 12%
- People with 10+ years of work experince applied for most of the loans. And people with 0-1 years experience are the second most category of people applied for loans.
- Majority of the loans are A, B and C graded
- Majority of the loans funded are within 15k
- Highest loan amount was taken for small_business followed by debit_consolidation
- Loan taken for 60 months has higher interest rate
- Interest rate is in increasing order for grades A to G
- Interest rate increasing with increase in loan amount
- Max installment amount defined is around 32% of monthly income

Possible Driving Factors for loan default
- High Interest rate loans
- G, F and E graded loans
- Loans applied for 60 months term
- People who are in the lower income range
- Higher loan amount requests
- Loans for Small Businesses
- People who have defaulted before

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python
- Pandas
- Matplotlib
- Seaborn

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Coding references used from the following web-sites
- https://www.machinelearningplus.com/pandas/
- https://stackoverflow.com/
- https://www.geeksforgeeks.org/graph-plotting-in-python-set-1/

## Contact
Created by [@sivaprasadt246] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
