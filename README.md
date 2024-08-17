# Regression_Models
I developed regression models to predict superconductivity's critical temperature, including Linear, Ridge, and Lasso regressions. I also used PCA for dimensionality reduction and PLS for handling multicollinearity. Each model was evaluated for accuracy to determine the best predictor.


# Linear Regression:

I started with a standard linear regression model to establish a baseline. This model assessed the relationship between the critical temperature and the features using a simple linear approach.
# Ridge Regression:

To address potential multicollinearity and improve model generalization, I employed ridge regression. By adding a regularization term, ridge regression penalized large coefficients, which helped in managing overfitting and improving model stability.
# Lasso Regression:

I also used lasso regression, which, unlike ridge regression, can shrink some coefficients to zero. This method performed feature selection and reduced the complexity of the model by focusing only on the most influential features.
# Principal Component Analysis (PCA):

To handle high-dimensional data and enhance model performance, I applied PCA for dimensionality reduction. This technique transformed the features into principal components, capturing the most variance in the data while reducing the number of features.
# Partial Least Squares (PLS) Regression:

Finally, I used PLS regression to model the relationship between the critical temperature and features while considering latent variables. PLS regression is useful for handling multicollinearity and extracting latent factors that explain the variance in both predictors and responses.
Each method was evaluated based on performance metrics such as R-squared, Mean Absolute Error (MAE), and Root Mean Squared Error (RMSE). This approach provided a comprehensive comparison of model effectiveness, helping to identify the most accurate and reliable method for predicting the critical temperature of superconductivity.
