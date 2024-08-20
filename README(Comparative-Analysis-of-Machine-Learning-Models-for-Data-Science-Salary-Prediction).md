# Comparative-Analysis-of-Machine-Learning-Models-for-Data-Science-Salary-Prediction

# Introduction

In this analysis, we aim to compare how different machine learning models perform in predicting salaries based on various job-related features. Our dataset includes information like job title, job category, salary currency, employee residence, experience level, employment type, work setting, company location, company size, and salary in USD.

# Data Preprocessing

To start, we tidy up the dataset. We encode categorical variables using LabelEncoder and split the data into training and testing sets. Additionally, we ensure all features are on the same scale by normalizing them with StandardScaler.

# Model Selection and Evaluation

We chose three machine learning models: Linear Regression, Decision Tree, and Random Forest, and put them through their paces. These models are trained on the training data and evaluated using Mean Squared Error (MSE) and R-squared (R²) score on the testing data.

Linear Regression:
This model does what it says on the tin - it establishes a linear relationship between the features and the target variable (salary). It gave us an MSE of around $97.48 million and an R² score of approximately 0.9765, telling us there's a strong linear connection between the features and salary.

Decision Tree:
The Decision Tree model tries to make sense of the data by splitting it based on different features. It didn't perform as well as Linear Regression, giving us an MSE of about $134.08 million and an R² score of around 0.9677, indicating it struggled a bit with the complexity of the data.

Random Forest: This model is like Decision Tree's big brother - it combines multiple Decision Trees to give us more accurate predictions. It came out on top with an MSE of approximately $87.23 million and an R² score of about 0.9790, showing it's the most accurate of the bunch.

# Conclusion

Based on our analysis, Random Forest seems to be the MVP here, closely followed by Linear Regression. Decision Tree, while not terrible, didn't quite measure up to the other two. Random Forest's success can be credited to its ability to handle complex relationships and reduce overfitting through ensemble learning.
