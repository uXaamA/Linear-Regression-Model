# Linear-Regression-Model
Ordinary Least Square Method
This project demonstrates the implementation of a linear regression model using the Ordinary Least Squares (OLS) method. Below is an overview of the steps performed in the project:

Exploratory Data Analysis (EDA): Initially, I performed EDA to understand the dataset, identify any patterns, and handle missing or irrelevant data. This step also includes data visualization techniques to explore the relationships between features and target variables.

Data Preprocessing: After analyzing the data, I prepared it for modeling by handling missing values, encoding categorical variables (if necessary), and normalizing or scaling features to improve model performance. (but in this project we i used data from the kaggle that's why for this data we didnt need to do this as the data doesnt have any missing value and catergorical data)

Model Training: The data was split into training and testing datasets. I then fitted the linear regression model using the training data.

Model Evaluation: Once the model was trained, it was evaluated using the testing data. The performance of the model was measured using R-squared (R²) and Mean Squared Error (MSE), which are common evaluation metrics for regression models.

Coefficients and Intercept: The model's coefficients and intercept were checked to understand the relationship between input features and the target variable.

Performance Visualization: The actual values were plotted against the predicted values to visually assess the model's accuracy. This helps to identify how well the model generalizes to new, unseen data.

Loss Distribution: Finally, the loss distribution was analyzed to understand how the errors (residuals) are distributed, providing insights into the model's performance and any potential improvements.

This project serves as a basic yet effective implementation of linear regression and provides an overview of essential steps such as EDA, model training, and evaluation.
