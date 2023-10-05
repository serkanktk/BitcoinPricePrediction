# Statistical Analysis of Bitcoin and Dogecoin Price Movements

## Introduction:

This project provides insights into the price movement of Bitcoin and its correlation with other factors, including the prices of Dogecoin. This analysis utilizes data preprocessing, data visualization, hypothesis testing, and machine learning to predict future price movements.

1) Correlation Analyses:
- Bitcoin Analysis:
Daily low prices vs. close prices: Analyzing the relationship between the low and closing prices of Bitcoin on a daily basis.
Trading volume vs. open prices of the next day: A look into how the trading volume affects the opening price of the following day.
Daily high prices vs. open prices: Exploration of the relationship between daily high prices and the opening prices of Bitcoin.
- Dogecoin Analysis:
Daily high prices vs. open prices: Investigating the correlation between the daily high prices of Dogecoin and its opening prices.
2) Machine Learning Models:
- Objective:
Predict the opening price of Bitcoin for 2021-07-07 using historical data from the preceding 30 days.

- Features Used:
Training the models using features derived from Dogecoin's data: high, low, open, and close prices.

- Models Deployed:
  - K-Nearest Neighbors (kNN)
  - Decision Tree Regressor
  - Linear Regression
  - Random Forest Regressor
    
3) Hyperparameter Tuning:
Optimizing models using GridSearchCV:
  - Random Forest Regressor
  - K-Nearest Neighbors (kNN)
  - Decision Tree Regressor

4) Results:
- Statistical Correlations:
Significant correlation observed between various price metrics of Bitcoin and Dogecoin.
E.g., The high price of Dogecoin is notably correlated with its opening price.
- Machine Learning Predictions:
Using several models, predictions were made for the opening price of Bitcoin on 2021-07-07. The outcomes for each model are as follows:

  - kNN: Prediction post hyperparameter tuning.
  - Decision Tree: Prediction post hyperparameter tuning.
  - Linear Regression: Direct model prediction.
  - Random Forest: Prediction post hyperparameter tuning.

5) Conclusion:
Correlation analyses elucidate the interplay between different price points of both Bitcoin and Dogecoin. Furthermore, the machine learning models were adept at predicting Bitcoin's opening price for a specified date, emphasizing their potential in predicting price movements based on past data.

6) Reproduction Note:
For replicating the results, ensure the necessary datasets and Python libraries (like Pandas, Matplotlib, Seaborn, and Scikit-Learn) are in place.


