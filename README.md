# PROJECT TITLE 
Credit Card Fraud Detection

## NON-TECHNICAL EXPLANATION OF YOUR PROJECT
Credit cards are essential instruments of the financial world. The sole purpose behind the invent of Credit card was to ease the financial transactions and helps in increasing the purchasing powers. However one of the major drawback of the credit cards these days are the fraudlent transaction which result loss of wealth and eventually into churning of the customers. With this project I'm trying to come up with an alogrithm that can help the organisations detect the credit cards frauds, so that they can take preventive actions and inform the related customer about the possible fraud in real time. The key focus area of the project at this time to detect the fraudlent transaction. 

## DATA
The dataset was generated from the the PaySim simulator (Ref: https://www.researchgate.net/publication/313138956_PAYSIM_A_FINANCIAL_MOBILE_MONEY_SIMULATOR_FOR_FRAUD_DETECTION) During generating the dataset constrainted where implemented to not generate duplicate and NULL values to mimic the real world credit card datasets. This was done to restrict the model development around the algorithm development.  

## MODEL 
A summary of the model you’re using and why you chose it. 
I have tried to evalute the input dataset on four models viz., Random forest, LGBM, XGB and LR. Based on the optimisation result the Random forest model was the optimised model and was able to detect fradulent transaction with highest AUC = 0.9. 

## HYPERPARAMETER OPTIMSATION
Description of which hyperparameters you have and how you chose to optimise them. 
For Logistic regression I used liblinear as solver parameter, for XGB is used max_depth, n_jobs and learning_rate hyperparameters, for LGBMClassifier I used boosting_type, objective as hyperparameters, for RandomForest I used n_estimators, n_jobs.

## RESULTS
THE FRAUD TRANSACTIONS WERE EITHER CASH_OUT or DEBIT and were made from customer to customer account. I trained four algorithms and Random Forest performed best among them. It gave the AUC score of 0.9.

## (OPTIONAL: CONTACT DETAILS)

