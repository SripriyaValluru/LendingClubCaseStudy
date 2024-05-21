# Lending Club Case Study - By Sri Priya Valluru and Priya Sharma
> Lending Club offers loans to borrowers, but many borrowers default, meaning they don't repay the borrowed amount and the interest.These defaults cause financial losses for businesses or lenders.Therefore, the goal of this case study is to identify key factors that can help predict which borrowers are more likely to default. 

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
Lending Club, a finance company specializing in various loan types, faces two key risks when assessing loan applications:

- Approving a loan for an applicant who is likely to repay it ensures business growth and revenue for the company.
- However, approving a loan for an applicant who is likely to default poses a financial risk for the company.
- Using the "loan.csv" dataset, the company aims to identify the primary factors influencing loan default. 
- These factors, also known as driver variables, serve as strong indicators of potential loan default.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
Used Python 3 and its respective libraries:
- Numpy
- Pandas
- Matplotlib
- Seaborn

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Conclusions
#### Univariate Analysis Summary
- The highest number of loan applications are for loan amounts ranging from 5,000 to 15,000.
- Most applicants are offered interest rates between 5% to 16%, with some extending up to 22%.
- The majority of applicants have installment amounts around 20 dollars.
- The most common loan term chosen by applicants is 36 months.
- 10+ years of employement length have higher loan applications
- December month stands out first in loan taking month.

#### Bivariate Analysis Summary
- The majority of loan applications are categorized under Grade B.
- The most common homeowner statuses among applicants are Rent and Mortgage.
- The highest number of loan applications fall under the category of debt consolidation.
- The higher number of Charged Offs of borrowers fall under the category 0 of public record bankruptcies.
- The charged offs are high in state California.

#### Multivariate Analysis Summary
###### Positive Correlations
- loan_amnt and funded_amnt (0.98):

These variables are highly correlated, indicating that the amount of the loan is almost equal to the amount funded.

- funded_amnt and funded_amnt_inv (1.00):

This perfect correlation suggests that the funded amount is equal to the funded amount invested, likely because these values are essentially the same in different contexts.

- loan_amnt and funded_amnt_inv (0.96):

This strong correlation is similar to the one above, reinforcing the relationship between loan amount and funded investment.

- loan_amnt and installment (0.93):

The loan amount is strongly related to the installment amount, which makes sense as larger loans generally require larger installments.

###### Negative Correlation
- annual_inc and dti (-0.12):
This is a weak correlation and it suggests that as annual income increases, the DTI tends to decrease slightly, but the relationship is not strong.


## Acknowledgements
- This project was inspired by Upgrad course "Executive PG Programme in Machine Learning & AI" in collaboration with IIITB.
- This project was based on Exploratory Data Analysis topic.


## Contact
Created by
- Sri Priya Valluru (https://github.com/SripriyaValluru)
- Priya Sharma (https://github.com/priyalotusfeet108)
feel free to contact us!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->