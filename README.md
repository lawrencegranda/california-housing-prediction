# California Housing Price Prediction Project

This project focuses on predicting housing prices in California using machine learning techniques. The most successful model proved to be a combination that used data normalization, KMeans clustering, and a RandomForest regressor.


## Project Description

The main objective of this project is to predict the median house value in California using various features such as housing location, age, population, households, and more. The project follows these key steps:

1. **Data Exploration and Preprocessing**: The data is loaded and explored to understand its structure and features. Preprocessing steps include removing outliers, handling missing data, and creating new features based on latitude and longitude.

2. **Data Normalization**: The data is normalized using Quantile Transformation to make it suitable for machine learning models.

3. **Feature Engineering**: New features are created based on the location of the housing units, such as dividing the region into quadrants and calculating aggregated statistics for each quadrant.

4. **Dimensionality Reduction**: Principal Component Analysis (PCA) is applied to reduce the dimensionality of the data.

5. **KMeans Clustering**: KMeans clustering is used to divide the housing units into different zones based on their geographical location.

6. **Model Building**: Various regression models are built, including Linear Regression, RandomForest Regressor, Bayesian Ridge, and more.

7. **Model Evaluation**: The performance of each model is evaluated using Mean Absolute Error (MAE) on both the original and normalized data.

8. **Model Selection**: The combination of data normalization, KMeans clustering, and RandomForest Regressor proves to be the most successful in predicting housing prices.


## Conclusion

The combination of data normalization, KMeans clustering, and RandomForest Regressor has proven to be the most successful model in predicting housing prices in California. After evaluating various regression models, the selected model achieved a Mean Absolute Error (MAE) of 27891.

**Mean Absolute Error (MAE)**: MAE is a metric used to measure the performance of a regression model. It calculates the average absolute difference between the predicted values and the actual target values. In the context of this project, the MAE of 27891 means that, on average, the model's predictions deviate by approximately $27,891 from the actual median house prices in California.

This model could be utilized to provide valuable insights to homeowners, real estate agents, and policymakers to make informed decisions about housing prices in different regions of California.


## Author Information

Name: Lawrence Granda Zarzuela

Project Duration: Dec 2021 to Jan 2022

Google Colab Link: [California Housing Price Prediction](https://colab.research.google.com/drive/1w53PHfnBU6eRvh9F6ZWTBK-oG63bzbsJ?usp=sharing)
