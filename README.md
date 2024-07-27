# Sales

Performance Metrics
Random Forest Regression

Mean Squared Error (MSE): 1.44
R-squared score: 0.95
Decision Tree Regression

Mean Squared Error (MSE): 3.40
R-squared score: 0.89
Lasso Regression

Mean Squared Error (MSE): 2.93
R-squared score: 0.91
Ridge Regression

Mean Squared Error (MSE): 2.91
R-squared score: 0.91
Linear Regression

Mean Squared Error (MSE): 2.91
R-squared score: 0.91

Analysis

Random Forest Regression:
The Mean Squared Error (MSE) is the lowest at 1.44, indicating the smallest average squared difference between the predicted and actual sales values.
The R-squared score is the highest at 0.95, suggesting that the model explains 95% of the variance in the sales data, which is very high.

Decision Tree Regression:
The Mean Squared Error (MSE) is 3.40, which is relatively high compared to Random Forest Regression.
The R-squared score is 0.89, which is lower than Random Forest Regression, indicating it explains less variance in the sales data.

Lasso Regression:
The Mean Squared Error (MSE) is 2.93, which is higher than Random Forest but lower than Decision Tree.
The R-squared score is 0.91, which is decent but not as high as Random Forest.

Ridge Regression:
The Mean Squared Error (MSE) is 2.91, similar to Linear Regression and Lasso Regression.
The R-squared score is 0.91, similar to Linear Regression and Lasso Regression.

Linear Regression:
The Mean Squared Error (MSE) is 2.91, indicating it performs similarly to Ridge Regression.
The R-squared score is 0.91, indicating it explains 91% of the variance in the sales data, similar to Ridge and Lasso Regression.

Conclusion
Random Forest Regression is the best model for this dataset. Here are the reasons:
Lowest MSE (1.44): This indicates that the Random Forest model has the smallest average squared difference between the predicted and actual values, leading to more accurate predictions.
Highest R-squared score (0.95): This indicates that the Random Forest model explains the highest proportion of variance in the sales data, making it the most reliable model in terms of prediction accuracy.

The ensemble nature of Random Forest Regression allows it to capture complex relationships and interactions in the data more effectively than individual models like Decision Trees, Linear Regression, Ridge, or Lasso Regression. This results in better overall performance and robustness against overfitting.








