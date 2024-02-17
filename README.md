# Sales-Prediction-linear-Regression-Model

The provided Python code focuses on building a Linear Regression model to predict sales based on advertising spending in TV, radio, and newspaper. Here's a concise summary:

Import Libraries:

Pandas and NumPy for data manipulation, train_test_split for data splitting, LinearRegression for modeling, and metrics such as mean_squared_error and r2_score for evaluation are imported.
Load and Explore Dataset:

The advertising dataset is loaded from the specified path.
The first few rows of the dataset are displayed to understand its structure.
info() is used to explore the dataset, including data types and missing values.
Select Features and Target Variable:

Relevant features ('TV', 'Radio', 'Newspaper') and the target variable ('Sales') are selected.
Data Splitting:

The dataset is split into training and testing sets (80% training, 20% testing).
Model Training:

A Linear Regression model is instantiated and trained on the training set.
Prediction and Evaluation:

The trained model is used to make predictions on the test set.
Mean Squared Error (mse) and R-squared Score (r2) are calculated to evaluate the model's performance.
Visualization:

A scatter plot is created to visualize the predicted sales against the actual sales in the test set.
Visualization Display:

The scatter plot is displayed for visual exploration.
In summary, this code demonstrates the application of a Linear Regression model for predicting sales based on advertising spending. It includes data loading, exploration, feature selection, model training, prediction, evaluation, and visualization. The scatter plot provides a visual representation of the model's predictive performance.
