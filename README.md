# Linear Regression from scratch
### This project contains several algorithms on the Abalone dataset
Initially strating with the Linear regression:
- The data is preprocessed for any null values and to make the data in numeric form
- A class for linear regression is made for:
  - Fit and Predict methods, these methods are created to perform the matrix operations.
  - This class will be used for the training and testing of the mopdel
- RMSE is calculated to check the working and effectiveness of the generated model

## Ridge and Lasso Regularization Techniques
These techniques are applied for better comparison
- Graphs are made for better visualization of the change of RMSE with change of Hyperparameter (alpha).
- Best alphas are calculated from Ridge and Lasso and are compared with the best alpha by Sklearn GridSearch
