# Alma Better Capstone Project

# Bike Sharing Demand Prediction

# Overview
This project focuses on predicting the demand for bike sharing services in a given area based on various factors such as weather conditions, time of day, day of the week, and other relevant features. Bike sharing systems are increasingly popular in urban areas as an eco-friendly and convenient mode of transportation. Predicting bike demand helps operators optimize bike allocation, improve user experience, and anticipate future service needs.

# Table of Contents
1. Motivation
2. Data
3. Methodology
4. Results
5. Conclusion
6. Contributing

# Motivation
Bike sharing systems play a vital role in promoting sustainable transportation and reducing traffic congestion. Accurate demand prediction enables bike sharing operators to effectively manage their resources, ensure availability, and enhance customer satisfaction. This project aims to develop machine learning models that can forecast bike demand with high accuracy.

# Data
The dataset used in this project contains historical records of bike sharing usage, including information on the number of bikes rented, weather conditions, date, time, and other relevant features. This data is utilized to train and evaluate predictive models for bike demand prediction.

# Methodology
Various machine learning algorithms, such as linear regression, decision trees, random forests, and gradient boosting, are employed to develop predictive models for bike demand prediction. The models are trained on historical bike usage data and weather information and evaluated using metrics such as mean absolute error (MAE), mean squared error (MSE), and root mean squared error (RMSE).

# Results
The developed predictive models demonstrate promising performance in forecasting bike sharing demand, with evaluation results indicating high prediction accuracy and reliability. Detailed performance metrics and visualization of prediction results are provided in the project's documentation.

# Conclusion
1. The dataset contains 8760 records and 14 features.
2. There are 11 numerical featrures and 3 categorical features.
3. There is no missing values in the dataset
4. There is no duplicate values in the dataset
5. Most bikes were rented in summer season.
6. More bikes were rented when there was no holiday.
7. More bikes were rented on functioning day.
8. More bikes were rented on 3rd ,4th and 5th day of the week.
9. More bikes were rented on weekday.
10. More bikes were rented on year 2018.
11. Most bikes were rented in 6th and 7th month and least bikes were rented in 1st and 2nd month respectively.
12. Models implemented are 'Linear Regression', 'Decision Tree', 'Random Forest', 'Gradient Boosting', 'XGBoost', 'SVM', 'KNN', 'ElasticNet'.
13. MSE (Mean Squared Error): The lower the MSE, the better the model's performance. Models with lower MSE values are preferred.
14. MAE (Mean Absolute Error): Similar to MSE, lower MAE values indicate better performance.
15. R-squared and Adjusted R-squared: R-squared measures the proportion of the variance in the dependent variable that is predictable from the independent variables. Adjusted R-squared takes into account the number of predictors in the model. Higher values of R-squared and Adjusted R-squared indicate better fit.
16. Considering these criteria, you can rank the models as follows:
Best Model:
Decision Tree: It has the lowest MSE(19.56) and MAE(0.418950) values and the highest R-squared(0.999963) and Adjusted R-squared values(0.999963). This indicates that the Decision Tree model performs the best among the models listed.
Worst Model:
KNN (K-Nearest Neighbors): It has the highest MSE(20973.287557) and MAE(88.343265) values and relatively lower R-squared(0.949662) and Adjusted R-squared values(0.949109) compared to other models. Therefore, the KNN model seems to perform the worst among the models listed.
17. After hyperparameter tuning
Decision tree regressor:After hyperparameter tuning, the Decision Tree model demonstrated significant improvement. The mean squared error (MSE) reduced from 19.56 to 17.99.Additionally, both R-squared and adjusted R-squared values increased, suggesting that the tuned model better explains the variance in the data.
KNN (K-Nearest Neighbors):After tuning the KNN model, there was a notable improvement in its performance. The mean squared error (MSE) decreased to 13083.77 and with the R-squared value increasing to 0.9686.

# Contributing
Contributions to this project, such as feature engineering, model optimization, or additional analyses, are welcome! Please feel free to open an issue or submit a pull request with your suggestions or enhancements.
