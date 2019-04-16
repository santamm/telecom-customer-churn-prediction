# Telecom Customer Churn Prediction

### Table of Contents

1. [Project Analysis](#motivation)
1. [Installation](#installation)
3. [Metric](#metric)
4. [File Descriptions](#files)
5. [Results](#results)
6. [Licensing, Authors, and Acknowledgements](#licensing)

## Project Analysis<a name="motivation"></a>
Customer attrition, also known as customer churn, customer turnover, or customer defection, is the loss of clients or customers.

Telephone service companies, ISPs, Pay TV companies, insurance firms, and alarm monitoring services, often use customer attrition analysis and customer attrition rates as one of their key business metrics  because the cost of retaining an existing customer is far less than acquiring a new one. Companies from these sectors often have customer service branches which attempt to win back defecting clients, because recovered long-term customers can be worth much more to a company than newly recruited clients.

Companies usually make a distinction between voluntary churn and involuntary churn. Voluntary churn occurs due to a decision by the customer to switch to another company or service provider, involuntary churn occurs due to circumstances such as a customer's relocation to a long-term care facility, death, or the relocation to a distant location. In most applications, involuntary reasons for churn are excluded from the analytical models. Analysts tend to concentrate on voluntary churn, because it typically occurs due to factors of the company-customer relationship which companies control, such as how billing interactions are handled or how after-sales help is provided.

Predictive analytics use churn prediction models that predict customer churn by assessing their propensity of risk to churn. Since these models generate a small prioritized list of potential defectors, they are effective at focusing customer retention marketing programs on the subset of the customer base who are most vulnerable to churn.

## Installation <a name="installation"></a>
The code in this project is written in Python 3.6.6 :: Anaconda custom (64-bit).
The following additional libraries have been used:
* pandas
* numpy
* matplotlib
* seaborn
* plotly
* sklearn
* warnings
* time
* graphviz
* yellowbrick 
* xgboost
* imblearn (Synthetic Minority Oversampling TEchnique (SMOTE))

## Metric<a name="metric"></a>
The following metrics have been used to compare the model performances:
* Accuracy
* Precision
* Recall
* F1 score
* AUC ROC


## File Descriptions <a name="files"></a>
The Jupyter notebooks included in this project are:
- Telecom Customer Churn Prediction.ipynb.ipynb

Data files (under data directory):
- WA_Fn-UseC_-Telco-Customer-Churn.csv


## Results<a name="results"></a>
The following classifiers have been compared:
- Logistic Regression
- Logistic Regression with Recursive Feature Elimination (RFE)
- SVC
- Random Forest
- Decision Tree
- KNN
- Naive Bayes
- LGBM
- XGBoost

Logistic regression achieved the highest accuracy score of 0.8026166. However, considering the class imbalances, this is not the best metric to compare model performances.
Logistic Regression with RFE achieved the best recall of 0.8040816.
Support Vector Machine with Linear Kernel achieved the best F1 score of 0.6433225.
Random Forest schieved the best precision of 0.7044025
Naive Bayes achieved the best ROC AUC score of 0.768


## Licensing, Authors, Acknowledgements<a name="licensing"></a>
For licensing see LICENSE file.
