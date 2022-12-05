# Machine-Learning-Project-Credit-Card-Fraud-Detection

Aiming at the problem that credit card defaulting in banking sector is unbalanced, which leads to increased credit risk, it is necessary to bring useful data analysis that gives better prediction results. The goal of this project is to exploit some of the famous supervised ML algorithms to recogonize the key factors that determines the likelihood of credit card default, based on the unbalanced data that leads to unsatisfactory results. The project constructs machine learning models such as logistic regression (with regularization, lasso and ridge), Neural Networks, Support Vector Machines and combination algorithm of Naive Bayes. It also offers ways to analyze and compare accuracies of different algorithms implemented to a base-line model. 

#Dataset Description:

The dataset covers credit card transactions in the country of Taiwan. We have around 30000 instances and 24 attributes. A few additional characteristics of our dataset are as follows:

#Attribute Information:

Our target variable is a binary variable, default payment (Yes = 1, No = 0. The 23 features that we will be using to make the prediction are as follows:

X1: Amount of the given credit (NT dollar): it includes both the individual consumer credit and his/her family (supplementary) credit.
X2: Gender (1 = male; 2 = female).
X3: Education (1 = graduate school; 2 = university; 3 = high school; 4 = others).
X4: Marital status (1 = married; 2 = single; 3 = others).
X5: Age (year)
X6 to X11 denotes Repayment statuses (-1 = paid duly, 1 = 1 month delay, 2 = 2 month delay,………………, 9 = 9 months delay and above)
X6: Repayment Status (September 2005)
X7: Repayment Status (August 2005)
X8: Repayment Status (July 2005)
X9: Repayment Status (June 2005)
X10: Repayment Status (May 2005)
X11: Repayment Status (April 2005)
X12 to X17 denotes the Amount of the bill Statement
X12: Bill amount for September 2005
X13: Bill amount for August 2005
X14: Bill amount for July 2005
X15: Bill amount for June 2005
X16: Bill amount for May 2005
X17: Bill amount for April 2005
X18 to X23 denotes the Amount of the previous payment
X18: amount paid in September 2005
X19: amount paid in August 2005
X20: amount paid in July 2005
X21: amount paid in June 2005
X22: amount paid in May 2005
X23: amount paid in April 2005

#Goal and purpose:

Our primary aim is to create a model which can predict if a transaction is fraudulent or not with fairly good confidence and also holds good when tested against a variety of external data sources. To achieve this, we aim to build a clean Machine Learning model. We will be trying to identify the key features that influence the target variable the most, and also the magnitude by which those features do so.
