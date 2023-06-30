# XAU-USD-Price-Prediction

This project aims to predict the closing price of XAU/USD (Gold vs US Dollar) based on historical data. The dataset used in this project is loaded into a pandas DataFrame and contains information about the time and closing price of XAU/USD.

# Data Exploration and Visualization

The project begins with data exploration and visualization using various Python libraries. Numpy and Pandas are used for data manipulation, while Matplotlib and Seaborn are used for plotting graphs. The dataset is loaded into a DataFrame, and basic information about the DataFrame, such as column names, shape, and description, is displayed. Null values are checked, and a correlation matrix is created to explore the relationships between variables.

A plot of the XAU/USD closing prices over time is generated using Matplotlib. The dates are properly formatted on the X-axis, and the plot includes a grid for better visualization.

# Data Preprocessing and Model Building

The next step involves preparing the data for model training. The dataset is split into features (X) and the target variable (y). The features are normalized using MinMaxScaler. The dataset is further split into training and testing sets using the train_test_split function.
A Linear Regression model is then instantiated and fitted to the training data. Predictions are made on the test data using the trained model.

# Evaluation Metrics

To evaluate the performance of the model, several evaluation metrics are calculated: Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared (R2) score. These metrics provide insights into the accuracy and performance of the model in predicting the XAU/USD closing prices.

# Hyperparameter Tuning

To optimize the performance of the Linear Regression model, hyperparameter tuning is performed using GridSearchCV. The best hyperparameters are determined, and the model is retrained with the optimal configuration.

# Model Performance Evaluation

The performance of the best model is evaluated using the same evaluation metrics as before: MSE, MAE, and R2 score. These metrics allow us to compare the performance of the optimized model with the initial model.

# Results and Visualization

Finally, the actual and predicted prices are plotted to compare the performance of the model visually. The plot displays the XAU/USD closing prices over time, with the actual prices shown as blue lines and the predicted prices as green lines. This provides a clear visualization of how well the model predicts the actual prices.

# Conclusion

In this project, a Linear Regression model is used to predict the closing prices of XAU/USD based on historical data. The model is evaluated using various metrics and optimized through hyperparameter tuning. The final model's performance is compared to the initial model, and the actual and predicted prices are visually represented.

This README file provides an overview of the project, its objectives, and the steps involved. It serves as a guide and documentation for users and contributors interested in understanding and replicating the project.

