# Model Card

## Model Description

**Input:** 
 Input is the credit card transaction details with 11 columns like:
 Type- like DEBIT, PAYMENT, CASH_OUT, TRANSFER
 Amount- amount of transaction
 oldbalance
 newbalance
 Origin Name
 Destination Name
 isfraud
 isflaggedfraud

**Output:** 
Output is the total number of fraud transactions out of total transactions. And the Type of transactions made from which account.

**Model Architecture:** 
I used Random Forest Regressor as it performed best for this problem. I also trained other algorithms like logistic regressor, XGBoost and compared them but the Random Forest gave the best AUC score and more accuracy.

## Performance

I check the Classification_report for the algorithm and Checked the accuracy and AUC of each model.


## Trade-offs

The Random Forest algorithm performs best with large data but speed during testing suffers. It also suffers from imbalanced dataset and requires more preprocessing of data for better results