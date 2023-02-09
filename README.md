# Car Prediction Model

In this repository, we aim to predict the value of a car based on various features such as the engine size, horsepower, and other features. We will be using three different machine learning models to make the prediction: Random Forest Regressor, XGBoost Regressor, and Catboost Regressor.

## Requirements

The following libraries are required to run the code:

- numpy
- pandas
- matplotlib
- seaborn
- sklearn
- xgboost
- catboost

## Data

The data used for this project is the Car Dataset from the UCI Machine Learning Repository. The data includes information on different makes and models of cars and their characteristics.

### Random Forest Regressor
The first model we will be using is the Random Forest Regressor. The Random Forest algorithm is a supervised learning algorithm that can be used for both regression and classification problems. The algorithm creates multiple decision trees, and the prediction is based on the average of the predictions made by each tree.

The performance of the Random Forest Regressor is measured using three evaluation metrics: Mean Absolute Error (MAE), Mean Squared Error (MSE), and Root Mean Squared Error (RMSE). The results are as follows:

- MAE: 0.8907546153846154
- MSE: 3.978401452385715
- RMSE: 1.994593054331062

### XGBoost Regressor
The second model we will be using is the XGBoost Regressor. XGBoost is a gradient boosting algorithm that is designed for high-performance computing. It is an optimized version of the gradient boosting algorithm that reduces computation time and increases accuracy.

The performance of the XGBoost Regressor is measured using the same evaluation metrics as the Random Forest Regressor:

- MAE: 0.7469347548091804
- MSE: 2.5684632032821106
- RMSE: 1.602642568785102

### Catboost Regressor
The third and final model we will be using is the Catboost Regressor. Catboost is an open-source gradient boosting algorithm that is specifically designed to handle categorical variables in the data. It uses an algorithm that can handle missing values, categorical variables, and outliers.

The performance of the Catboost Regressor is measured using the same evaluation metrics as the other models:

- MAE: 1.0132939743818592
- MSE: 3.934934144002637
- RMSE: 1.9836668429962319


### Conclusion
Based on the results, we can see that the XGBoost Regressor has the best performance in terms of accuracy, with the lowest MAE, MSE, and RMSE values. However, each of the models has its own strengths and weaknesses, and the choice of which model to use depends on the specific requirements and characteristics of the data.
