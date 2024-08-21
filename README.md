# Lending Club Case Study
> Study the variables that affect the customer's tendency to default.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface. 

Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'. 

loan.csv dataset is used that has the complete loan data for all loans issued through the time period 2007 t0 2011.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions

###Univariate Analysis

- Defaulter's loans are lower in numbers compared to Non-Defaulters (Fully Paid)
- Loan amount has a range of loans from 500 to 35k with a mean of 9.8k
- The loans in 60 months term mostly consist of grade B, C and D loans whereas the loans in 36 months term majorly consist of grade A and B loans
- More than half of the loan taken has term of 36 months compared to 60 months
- Interest rate is more crowded between 5-10 and 10-15 along with a drop near 10%
- Lot of loans are in Grade A and Grade B, meaning loans are approved more for higher grades

###Segmented Univariate Analysis

- High number of loans are issued in 12th months and year 2011
- Borrowers below 50k have high almost half of the defaulters, this can be a risk factor
- Volume of loans has vastly increased with each year, also indicates approvals have increased
- Borrowers with 10+ years have taken more loans and high number of fully paid, defaulters are also comparatively more
- The interest rate has increased till 16% and then dropped from 17% for defaulters. For Fully paid, there is drop near 10%
- Defaulters with RENT and MORTGAGE Home Owners are most likely to default than wit OWN homes
- The Loan Status varies with DTI ratio; we can see that the loans in DTI of 10-15% have higher number of defaulted loan,higher the dti more chance of defaulting.
- A high percentage of loans are taken for the purpose of debt consolidation followed by credit card
- Compared to Sub grades of A, more numbers of defaulters are in Sub Grade of B & C, this us a risk factor

###Bivariate Analysis

- The rate of interest is inversely proportional to Grades meaning higher the grade, lower is the interest rate. Grade is a risk factor.
- Most of the borrowers dont have bankruptcy records and are safe choice for loan approvals
- The Grade A which is lowest risk also has lowest DTI ratio which we can say that higher grade has lower rate of default
- The brrowers are mostly having no record of Public Recorded Bankruptcy and are safe choice for loan issue.

###Rationale

1. Borrowers having loans against debt consolidation and Credit Cards are more likely to get into debt trap with high interest      
   rates complicating loan repayment and are likely to default
2. Borrowers with very high Debt to Income ratio are likely to default, additional due diligence needs to be carried out
3. Borrowers with highest grade A are safer compared to lower grades pose high risk
4. Borrowers having annual income less than ~50000 are likely to default more posing risk of repayment
5. Borrowers with Public Recorded Bankruptcies pose higher risk for loan repayment 
6. Borrowers with Rented and Mortgaged Home Ownership carry more disk to default loans
7. Borrowers with high interest rates pose high risk to default
8. Even though borrowers with working experience of 10+ years are likely to fully pay,they also pose risk to default loans given the fact borrowers with 10+ years expereience are high consumer of loans


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
    Python - version 3.12.4
    Pandas - version 2.2.2
    Matplotlib - version 3.8.4
    Numpy - version 1.26.4
    Seaborn - version 0.13.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
    EDA session by Upgrad/IIIT_B


## Contact
Created by [@sirfan12] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
