# Lending club case study
Lending club case study is a project for analyzing the historical data of consumer finance data.The data has lot of information of previously lended loans and their performance.
in this activity we have concentrated mainly on loan amount, interest rate, Purpose of loan and loan tenure. based on these variables we have tried to analyze the risk factors in lending loans to certain group of customers.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
A consumer finance company which specializes in lending various types of loans wants to perform analysis on the existing data to learn about the risks and arrive to a solution which will enable them to lend the loans in a way which will reduce the risks.
For this activity we have used the concepts of exploratory data analysis and analyzed the data using python 
This presentation describes about the data analysis done on the provided data based loan.csv on the company's loan applicant's history.

Below activities are performed as part of this project:

Data Cleaning
	Removing Duplicates
	Removing null Columns
	Removing special Characters from Number columns 
Univariat analysis
	Analyze the data for loan amount, Interest Rate, Total Payment.
	Discard outliers
	Derive and analyze the correlation matrix for loan. 
Bivariate Analysis
	Perform analysis on loan amount and purpose of loan
	Check the no. of loans provided vs status of loans
	Analyze the data based on annual income vs charged off


OBSERVATIONS:

Based on the data 82% of loans issues are fully paid and around 14% got charged off.
It is observed the major chunk of loans were taken for debt_consolidation and credit card is also the trailing reason after debt consolidation

Univatiate Analysis:

Most of the borrower's income is in the range of 40000 to 80000
14% of total loans were charged off out of total loans issued.
Most of the loan amounts range from 5000 to 15000
No. of loans taken for debt consolidation and credit card is high.This also shows that in these categories the charged of percentage is more too.

Bivariate Analysis:
Charged off percentage is more for the people who opted for 60-month loan tenure.
Borrowers having income 0-20000 are the highest to rate of charge off
Charge off loans are minimum in case of borrowers who have income 80000+
Small business applicants have high chances of getting charged off whereas charged off proportion is better for renewable energy than other categories.
This indicates that as the loan amount increases the interest rate also increases.



## Conclusions
Loans related to debt consolidation and credit card are more at the same time charged off ratio when compared to others is also high. This is most availed category of loan nad also most risky.
The company needs to asses more while lending the loan to the income group 0-20000.
80000+ Annual income borrowers are more likely to repay the loans hence has very less risk while lending loan to this category.
Small business applicants pose  ore risk to the company when lended loan.


## Technologies Used
Python
Libraries used: 
		numpy
		pandas
		matplotlib.pyplot
		seaborn


## Contact
Created by [@gourishankarayachitula] - feel free to contact me!
"# LendingClubCaseStudy" 
