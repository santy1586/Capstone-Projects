# Loan_Prediction_Analysis
# Business Understanding & Overview
The loan providing companies find it hard to give loans to the people due to their insufficient
or non-existent credit history. Because of that, some consumers use it as their advantage by
becoming a defaulter. Suppose you work for a consumer finance company which specialises
in lending various types of loans to urban customers. You have to use EDA to analyse the
patterns present in the data. This will ensure that the applicants capable of repaying the
loan are not rejected.
# Business Objective
We will perform this Exploratory Data Analysis in order to get actionable insights, and convert them into meaningful stories and present it so that the companies can take necessary actions in order to reject or accept loan application.
* To perform Exploratory Data Analysis in order to get actionable insights for maximizing the profits of the company for accepting the loan.
* Overall minimizing the rejection of the application.
# Data Summary
There are 203 Rows and 13 Columns, There are 7 categorical Variables, There are 4 Variable which are in Decimal Format, and 2 Variables are integer Format. There are NULL values which are of less than 15%
* Loan_ID - Consists of Loan Application ID of Customers/Applicants
* Gender - Consists of Male and Female based on Applicants
* Married - Yes means the applicant is married and No means the applicant is not married.
* Dependents - No of Dependents of the particular applicant.
* Education - Value Consists Graduate and Not Graduate. 
* Name_income_type - Profession such as WORKING,STATE SERVANTS, PENSIONERS, COMMERICIAL ASSOCIATES are present in this 	    	Variable.
* ApplicantIncome - Consisits of income of the applicants
* CoapplicantIncome - Consists of income of the coapplicants
* LoanAmount - funds that are needed or requests by the applicants
* Loan-Amount_Term - No. of days that is selected by the applicants
* Credit_History - For those who has proper credit history are indicated as 1 and for those who don't have are indicated 	as 0
* Property_Area - Urban, Rural, and Semiurban are the values that are present in the variable.
* Loan_Status - Yes indicates that the approval of loan and No indicates the Disapproval of loan.
# Key Findins of the EDA
After performing exploratory data analysis on the data set,
* Overall the no of Percentage of the Accepted Loan is of 67% of Total.
* And the no of Percentage of the Rejected Loan is of 33% of Total.
* Most clients are married. Single people have higher chances of defaulting than others and are from Urban areas.
* The working class applies the most for loans, and have a very low default rate, hence they are reliable.
* commercial associates, state servants and pensioners are fairly more reliable.
# Machine learning models

### First of all we will divide our dataset into two variables X as the features we defined earlier and y as the Loan_Status the target value we want to predict.

### Models we will use:

    Decision Tree
    Random Forest
    Logistic Regression

### The Process of Modeling the Data:

    Importing the model
    Fitting the model
    Predicting Loan Status
    Classification report by Loan Status
    Overall accuracy
# Conclusion
* Most clients are married. Single people have higher chances of defaulting than others and are from Urban areas.
* The working class applies the most for loans, and have a very low default rate, hence they are reliable.
* commercial associates, state servants and pensioners are fairly more reliable.
* Banks should focus more on 'Student' ,'Pensioner', 'State Servants' and 'Commericial Associates' as the are having         most number of unsuccessful payments.
* Banks should focus less on income type ‘Working’ as they are having most number of successful
    payments
* Female applicants are the most defaulters as compared to Male applicants
* Most Defaulters are in Low Income Range.

Bascially all the features are very important variables because of its high correlation with Loan_Status.
The Random Forest algorithm is the most accurate: approximately 82%.






