# Home-Value-Prediction

This project demonstrates the use of Linear Regression and Boosted Trees for predictive modeling. The dataset used in this project is a real estate dataset containing various property features and transaction details.

https://www.kaggle.com/c/zillow-prize-1/data

Evaluation
The performance of both models is evaluated using Root Mean Squared Error. This metric measures the average magnitude of the errors between the predicted and actual values, providing a sense of how well the models are performing.

Findings
In Linear Regression we have received a very low variance score(= 0) which made us think that Linear Regression model does not fit out dataset and we need to think about implementing some other methods for predicting and increasing the accuracy of the log error in the future. So, we decided to use LightGBM and XGBoost in order to predict the house values as these algorithms are better at capturing the intricate patterns and relationships in the dataset, leading to more accurate predictions
