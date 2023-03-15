# Credit-Card-Approval-Prediction---CLASSIFICATION

## About Dataset

## A Credit Card Dataset for Machine Learning!
### Context
Credit score cards are a common risk control method in the financial industry. It uses personal information and data submitted by credit card applicants to predict the probability of future defaults and credit card borrowings. The bank is able to decide whether to issue a credit card to the applicant. Credit scores can objectively quantify the magnitude of risk.
 
Generally speaking, credit score cards are based on historical data. Once encountering large economic fluctuations. Past models may lose their original predictive power. Logistic model is a common method for credit scoring. Because Logistic is suitable for binary classification tasks and can calculate the coefficients of each feature. In order to facilitate understanding and operation, the score card will multiply the logistic regression coefficient by a certain value (such as 100) and round it.
 
At present, with the development of machine learning algorithms. More predictive methods such as Boosting, Random Forest, and Support Vector Machines have been introduced into credit card scoring. However, these methods often do not have good transparency. It may be difficult to provide customers and regulators with a reason for rejection or acceptance.

## Task

Build a machine learning model to predict if an applicant is 'good' or 'bad' client, different from other tasks, the definition of 'good' or 'bad' is not given. You should use some techique, such as vintage analysis to construct you label. Also, unbalance data problem is a big problem in this task.

## Content & Explanation
There're two tables could be merged by ID:

### application_record.csv		
Feature | name |	Explanation	Remarks
ID	- Client number	

CODE_GENDER -	Gender	

FLAG_OWN_CAR -	Is there a car	

FLAG_OWN_REALTY	 - Is there a property	

CNT_CHILDREN -	Number of children	

AMT_INCOME_TOTAL	- Annual income	

NAME_INCOME_TYPE -	Income category	

NAME_EDUCATION_TYPE -	Education level	

NAME_FAMILY_STATUS -	Marital status	

NAME_HOUSING_TYPE -	Way of living	

DAYS_BIRTH -	Birthday	Count backwards from current day (0), -1 means yesterday

DAYS_EMPLOYED	- Start date of employment	Count backwards from current day(0). If positive, it means the person currently unemployed.

FLAG_MOBIL -	Is there a mobile phone	

FLAG_WORK_PHONE	- Is there a work phone	

FLAG_PHONE -	Is there a phone	

FLAG_EMAIL -	Is there an email	

OCCUPATION_TYPE -	Occupation	

CNT_FAM_MEMBERS -	Family size	


## credit_record.csv	

Feature | name	| Explanation	Remarks

ID -	Client number	

MONTHS_BALANCE - 	Record month	The month of the extracted data is the starting point, backwards, 0 is the current month, -1 is the previous month, and so on

STATUS	- Status	0: 1-29 days past due 1: 30-59 days past due 2: 60-89 days overdue 3: 90-119 days overdue 4: 120-149 days overdue 5: Overdue or bad debts,
write-offs for more than 150 days C: paid off that month X: No loan for the month
