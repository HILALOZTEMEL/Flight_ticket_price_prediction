# Flight ticket price prediction

This project contains a machine learning model that predicts flight ticket prices. Its aim is to assist users in predicting ticket prices for specific flight routes and dates. The project is developed using the Python programming language and various data science libraries.

## Dataset
The dataset used for this project can be accessed from the [data-source-link](https://www.kaggle.com/datasets/nikhilmittal/flight-fare-prediction-mh). The dataset contains both training and test data in CSV format. After downloading the dataset, please copy it to the project folder.


## Model Training
In this project, several machine learning algorithms have been used to experiment with different models. These are as follows:

Random Forest Regressor
Gradient Boosting Regressor
Support Vector Regressor (SVR)
XGBoost Regressor
Each model has been trained with the training dataset. During the training process, hyperparameter tuning and model performance evaluation have been conducted.

## Model Performance Results:

Random Forest Model:

Mean Squared Error (MSE): 4045733.42
Mean Absolute Error (MAE): 1170.70
R-squared: 0.8017
The Random Forest model achieved relatively low MSE and MAE values, indicating that it is performing well in predicting the flight ticket prices. The R-squared value of 0.8017 suggests that approximately 80.17% of the variance in the target variable can be explained by the model.

Gradient Boosting Model:

Mean Squared Error (MSE): 4266933.33
Mean Absolute Error (MAE): 1489.76
R-squared: 0.7908
The Gradient Boosting model also demonstrates reasonable performance with lower MSE and MAE values. The R-squared value of 0.7908 indicates that around 79.08% of the variance in the target variable can be explained by this model.

SVR Model:

Mean Squared Error (MSE): 20835587.37
Mean Absolute Error (MAE): 3610.78
R-squared: -0.0213
The SVR model shows a significantly higher MSE and MAE, indicating less accurate predictions compared to the other models. Moreover, the negative R-squared value of -0.0213 suggests that the model does not perform well in capturing the variations in the target variable.

XGBoost Model:

Mean Squared Error (MSE): 3098512.36
Mean Absolute Error (MAE): 1145.32
R-squared: 0.8481
The XGBoost model yields good performance with relatively low MSE and MAE values. Additionally, the high R-squared value of 0.8481 indicates that approximately 84.81% of the variance in the target variable can be explained by this model.

Overall, the XGBoost model appears to be the most promising choice due to its lowest MSE and MAE values and the highest R-squared score among the models evaluated. It provides the best predictive capability for flight ticket prices in this project. However, further analysis and evaluation may be necessary to fully assess the models' generalization to unseen data and their suitability for real-world applications.




