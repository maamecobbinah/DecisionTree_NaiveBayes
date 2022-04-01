# DecisionTree_NaiveBayes
## Objective:  
The objective is to develop an accurate machine learning model that can be used by a German Bank to determine loan  eligibility. The goal is to develop a system that ensures the maximization of income and minimization of financial loss by ensuring that low risk customers who are likely to repay get approved and high risk customers who are likely to default do not get approved. The project utilizes both using Decision Tree and Naive Bayes methods for loan prediction. It compares both methods to determine which is more accurate and meets the overall need of the Bank.

## Models: 
The models adopted for analysis are the Decision Tree and Naïve Bayes Model. The Decision tree model is a supervised machine learning method that  breaks down a dataset into smaller and smaller subsets in a tree-like manner. It is made up of internal nodes that represent the features of a dataset, branches that represent the decision rules and finally leaf node that represents the outcome. The Naïve Bayes Model on the other hand is a supervised machine learning model that assumes the independence of variables in the dataset and uses probabilistic calculation to identify features and classify elements.

## Data Set:  
The data source for this project is the German Credit dataset which is a collection of the credit information of 1000 loan applicants. The dataset contains 21 predictor variables that essentially determine the credibility of an applicant. It looks into factors such as the applicant's age, income, occupation, account balance, marital status, current assets, and so on. An applicant is rated Good credit (700 cases within the dataset) or Bad Credit (300 cases within the dataset).

1. Creditability: This is a class attribute  showing whether the credit rating is good or bad. Good credit is represented by 1 and bad credit rating is represented by 0.
2. Account Balance: This represents checking account status (1 < 0 DM, 2 0<=...<200 DM, 3 > 200 DM, 4 No checking account), where DM= Deutsche Mark 
3. Duration of Credit (month): This represents duration of credit in months 
4. Payment Status of Previous Credit: This refers  to  credit history of the applicant.  0 means no credits taken,1 all credits at this bank paid back duly, 2 existing credits paid back duly till now, 3 delay in paying off in the past, 4 critical account.
5. Purpose: This shows the purpose of the loan (0 New car, 1 Used car , 2Furniture/Equipment, 3 Radio/Television, 4 Domestic Appliances , 5 Repairs ,6 Education ,7Vacation, 8 Retraining ,9 Business, 10 Others)
6. Credit Amount: This is a numerical value showing the credit amount
7. Value Savings/Stocks: This shows average balance in savings and stocks (1  <100 DM, 2 100<= ... < 500 DM, 3  500<= ... < 1000 DM, 4  =>1000 DM,5 unknown/ no savings account)
8. Length of  current employment: This shows length of employment (1  unemployed, 2 < 1 year, 3 1<=...<4 years, 4 4<=…<7 years, 5>=7years).
9. Instalment percent: This represents installment rate in percentage of disposable income (numerical)
10. Sex & Marital Status: This is an attribute showing gender and marital status (1 male  divorced/separated, 2 female  divorced/separated/married, 3  male single,4 male  married/widowed, 5  female  single)
11. Guarantors: This variable represents guarantors and co-applicants (1  none, 2  co-applicant, 3  guarantor)
12. Duration in  Current address: This value shows the duration in current address (1 <= 1 year, 2 1<...<=2 years, 3 2<...<=3 years, 4 >3 years)
13. Most valuable available asset: This variable shows valuable assets ( 1  real estate 2  savings agreement/ life insurance,3  car or other, 4  unknown / no property)
14. Age (years): This variable shows age in years.
15. Concurrent Credits: This variable represents installment plans ( 1  bank, 2  stores, 3  none )
16. Type of apartment: This variable represent type of housing ( 1  rent, 2  own, 3  for free)
17. No of Credits at this Bank: This variable shows the number of existing credits at the bank.
18. Occupation: This variable represents the skill level of an applicant's occupation.  (1  unemployed/ unskilled - non-resident, 2  unskilled - resident, 3  skilled employee / official, 4  management/ self-employed/highlyqualified employee/ officer)
19. No of dependents: This variable represents the number of dependents
20. Telephone: This variable represent the telephone number (1 yes, 2 No)
21. Foreign Worker:This variable shows whether the person is the foreign worker or not (1 yes , 2 no)

