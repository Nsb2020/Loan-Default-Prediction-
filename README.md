# SuperLender Loan Default Prediction

### Bussines Problem
<img src="https://github.com/Nsb2020/Loan-Default-Prediction-/blob/main/Super%20lender.png">
SuperLender is a local digital lending company, which prides itself in its effective use of credit risk models to deliver profitable and high-impact loan alternative. Its assessment approach is based on two main risk drivers of loan default prediction: (1) willingness to pay and (2) ability to pay.
Since not all customers pay back, the company needs experienced data scientist to build robust models to effectively predict the odds of repayment.

These two fundamental drivers need to be determined at the point of each application to allow the credit grantor to make a calculated decision based on repayment odds, which in turn determines if an applicant should get a loan, and if so - what the size, price and tenure of the offer will be.

## Project Objective
* This project was aimed at predicting if a loan was good (1) or bad (0) using the borrower's information as the training set. It helps the SuperLender's loan officer   make a calculated decision based on repayment odds, which in turn determines if an applicant should get a loan and, if so, what the size, price, and tenure of the   offer will be.
* The model in this project was built using random forest classifiers and grid search to optimize the best parameters for the model.


# Data
The data used for this project was provided by Zindi Africa, and there are three different datasets for both training and testing the model.
The three datasets were merged to obtain the required columns for this project.

Below are what the columns of the data represent:

* customerid: A unique ID assigned to a customer contains all of the customer's information. 
* loannumber: The number of loan that a customer took.
* bank_name_clients: Name of the customer's bank.
* bank_account_type: customer's bank account type.
* Approval_Period_Days: Number of days it took the superlender's loan officer to approve the loan.
* Loan_Period_days: Numbers of days it took the customer to pay back previous loan, a negative Loan_Period_days means the customer pays back before the due date.
* Due_Period_Days: Number of days it is expected for a customer's loan to be due for repayment.
* Age_In_Days: Age of the customer in days. divide the result by 365.5 to get the age in years.
* loanamount: Loan value taken
* totaldue: Total repayment required to settle the loan = this is the capital loan value disbursed + interest and fees
* termdays: Term of loan
* longitude_gps and latitude_gps: geographical location of the customer
* good_bad_flag: (good = settled loan on time; bad = did not settled loan on time) - this is the target variable that we need to predict


# Skills and Technologies
* Programming (Python)
* Data Preprocessing 
* Exploratory Data Analysis
* Data Visualization(Seaborn and Matplotlib)
* Machine Learning 
* Google Collobarotory Notebook

# Model Selection
Two different ensemble models were selected and compared for this project (the Random Forest Decision Classifier and the Gradient Bosting Decision Classifier), and the best parameters for these models were optimized using grid search.

# Notebook
The jupyter notebook containing all the code and exploratory data analysis can be found [here](https://github.com/Nsb2020/Loan-Default-Prediction-/blob/main/LOAN_PRED.ipynb)



