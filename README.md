# credit-risk-classification
The purpose of this analysis is to evaluate creditworthiness of borrowers based on historical data contained in lending_data_csv.  Additionally, the comparison of the logistic regression model based on original data versus the logistic regression model based on the resampled data intends to demonstrate which model could best serve a lendor and why.

The results of this analysis show that the regression model based on resampled/oversampled data best serves a lendor for reasons as follows:

    • The accuracy score is .01  better with orginal data at .99 versus resampled data at 1.
    • The precision score is the same for both data sets on healthy and high-risk loans but the macro weighted average is .01 better with orginal data at .99 versus resampled data at 1.
    • The recall score for high-risk loans is .11  better with orginal data at .89 versus resampled data at 1.

In summary, the 11% improvement in recall rate is the main reason for invoking the logistic regression model based on resampled/oversampled data rather than the same model based on original data.  On a high-risk loan, the lender risks losing the principal and incurring the costs of recovering it through federal insurance programs, collections agency fees, and administrative expenses.  An 11% improvment in predicting unhealthy loans is markedly better than the alternative of incurring thousands of dollars of unnecessary costs.  
    
    
