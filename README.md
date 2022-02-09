# Lending Club
You work for a consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:

If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company

If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company



## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Provide general information about your project here.
  -  In Lending Club Case study, we are looking to get useful insights from historical dataset of loans using EDA. 
- What is the background of your project?
  -  We are working on a dataset of a consumer finance company to find out the driving variables that can be indicators of default.
- What is the business probem that your project is trying to solve?
  -  We are trying to find out the kind of loans which could be charged off and see any relationship among other factors.
- What is the dataset that is being used?
  -  We are using Lending Club Loan Dataset.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Technologies Used
- pandas - 1.3.4
- numpy - 1.20.3
- seaborn - 0.11.2
- hvplot - 0.7.3
- matplotlib : 3.4.3


## Conclusions
- Out of all the borrowers, around 15% of the borrowers defaulted and 85% of the loans were fully paid.
- We can observe that as we move from Grade A to Grade G, interest rate increases and so does the number of default loans. This suggestes that company gives higher interest       rates for borrowers with F and G grades.
- Another thing to observe is that with increase in annual income, the percentage of defaulting of loan decreases. 
- In the city of California,New York and Florida, more loan dafaults are seen. 
- With increase in Term of loan, percentage of loan default also increases.
- Loans taken for the purpose of Debt consolidation and credit card have more occurences of default.
- Increase in dti can be seen with increase in interest rate. We can infer that dti is positively correalted with charged off percentage.


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
-This project was inspired by Lending Club Case Study.
- References if any...
- This project was based on [this tutorial](https://learn.upgrad.com/course/1994/).


## Contact
Created by [@VipinJaguri] and [@deepakkalarrikal]- feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
