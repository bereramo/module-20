The purpose of the analysis to was evaluate a model based loan risk based on different factors. such as income, debt to income ratio, the size of the requested loan as well as interest rate. 
The data was taken from historical lending actvity from a lending services that is used to identify criteria that would result in borrowers that could pay back the loan. The variables we were trying to predict were loans that were healthy and those that were high risk.
Machine learning:
        Data Collection: Data was already provided.
        Data Preprocesssing: Choosing the variables for y and seperating from X
        Model Training: LogisticRegression was used for it is commonly used for prediction and classification. Training the model on a traiing set.
       

Model 1:
    Accuracy: The accuracy was calculated to be 0.99 though is might be a bit skewed since there is a smaller sample size for the high risk loans compared to the healthy loans.
    Precision: the model predicted 0.84 precision that identifies only 84% of high risk loans were identified correctly while 16% were classified as unhealthy when they were not.
    Recall: While the recall is better at 0.90 is does leave room for false negatives

LogisticRegression is a good model to use fot this data set but more data should be used in the sample set for high risk loans. The predictions did accurately predict healthy loans is was also predicting some false positives. As a loan service company it is better to be overly catious in these scenarios. It is more important to accrately predict whether a borrrower will be an high risk loan 
    
