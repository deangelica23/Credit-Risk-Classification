# Credit Risk Analysis #

##Over view of the Analysis ## 
- The purpose of the analysis is to use the historical lending data to predict if a loan is healthy or high risk. This is used to help the company minimize financial risk. 
- Data was prepped by loading into jupyter using pandas. Then, it was split inot training and testing sets to evaluate the performance. 
- Logistic Regression algorithm was used and is effective for binary classification tasks, in this case, to predict healthy or high-risk loans. The trained logistic regression model was used to make predictions on the dataset. 
- The performance was assessed by the confusion matrix and classification report. the Confusion Matrix heals visualize true positives, true negatives, false positives, and false negatives. Classification Reports provide the precision, recall, and f1-score for each class. 

## Accuracy ##
- 99% 

## Precision ## 
- Class 0 = Healthy Loans        
- Class 1 = High-Risk-Loans

Class 0 Precision     | Class 1 Precision
--------------------- | ---------------------
1.00 or 100%          | 0.94 or 94%
 
## Recall scores ##

- Class 0 Recall = 0.99 or 99%
- Class 1 Recall = 0.94 or 94%

## Summary ##

- The logistic regression model does well at predicting healthy loans (0) with 100% precision and 99% recall.
- The precision for high-risk loans is a little lower and ideal 84%, but recall for the class has a favorable 94%, meaning it's doing it's job and correctly identifying the high-risk loans.
- The model has a strong micro average precision and f1-score of 92% and 97% respectively. 
- I recommend using this model for loan risk prediction due to its strong recall and high accuracy.
- Although precision for high-risk loans could use some improving, the model does reliably flag most high-risk loans. 
- This is an overall valuable tool for minimizing financial losses.