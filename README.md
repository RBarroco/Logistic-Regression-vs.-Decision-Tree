If the project is not visible on github, you can use this link:</br>
https://nbviewer.jupyter.org/github/RBarroco/Logistic-Regression-vs.-Decision-Tree/blob/master/supervised-learning-logistic-tree-loan-modelling.ipynb

## Logistic Regression and Decision Tree Classification

Tools:</b>

1) Anaconda or Conda for environment creation.
2) Exploratory data analysis, uni-variate and multi-variate analysis.
3) Scikit-learn and statsmodels
4) Working with imbalanced data set
5) Feature Engineering and data preprocessing
6) Model preparation
7) Logistic Regression Log Loss
8) ROC, AUC curve
9) Accuracy, Precision, Recall and f1-score
10) Finding the best threshold for Logistic Regression curve
11) Test for multicollinearity
12) Feature importance
13) Precision-Recall curve (to find best threshold)
14) Confusion Matrix
15) Business insights

### Background and Context

AllLife Bank has a growing customer base. Majority of these customers are liability customers (depositors) with varying size of deposits. The number of customers who are also borrowers (asset customers) is quite small, and the bank is interested in expanding this base rapidly to bring in more loan business and in the process, earn more through the interest on loans. In particular, the management wants to explore ways of converting its liability customers to personal loan customers (while retaining them as depositors).

A campaign that the bank ran last year for liability customers showed a healthy conversion rate of over 9% success. This has encouraged the retail marketing department to devise campaigns with better target marketing to increase the success ratio with a minimal budget.

You as a Data scientist at AllLife bank has to build a model that will help marketing department to identify the potential customers who have higher probability of purchasing the loan. This will increase the success ratio while at the same time reduce the cost of the campaign.

### Objective
To predict whether a liability customer will buy a personal loan or not.

Which variables are most significant.

Which segment of customers should be targeted more.

### Data Dictionary
* ID: Customer ID
* Age: Customer’s age in completed years
* Experience: years of professional experience
* Income: Annual income of the customer (in thousand dollars)
* ZIP Code: Home Address ZIP code.
* Family: the Family size of the customer
* CCAvg: Avg. spending on credit cards per month (in thousand dollars)
* Education: Education Level. 1: Undergrad; 2: Graduate;3: Advanced/Professional
* Mortgage: Value of house mortgage if any. (in thousand dollars)
* Personal_Loan: Did this customer accept the personal loan offered in the last campaign?
* Securities_Account: Does the customer have securities account with the bank?
* CD_Account: Does the customer have a certificate of deposit (CD) account with the bank?
* Online: Do customers use internet banking facilities?
* CreditCard: Does the customer use a credit card issued by Bank?
