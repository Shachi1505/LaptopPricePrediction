Laptop Price Prediction Model
By Shachi Singhal

Regression Model
Objective is to forecast a numeric value (price), laptop price prediction is classified as a regression task. The output of the model would be a continuous value representing the predicted price. We will calculate R^2 score. R² Score is used for regression problems and measures how well the model explains the variability in the target variable. Note: Accuracy is calculated for classification problems, like disease prediction, email smap etc.

ML ALGOS USED:
Linear Regression: A linear regression model predicts a continuous output variable based on linear relationships with input features, aiming to minimize the sum of squared differences between observed and predicted values.
K-Nearest Neighbors (KNN): KNN is a non-parametric and instance-based learning algorithm that predicts the value of a new observation by averaging the values of its k nearest neighbors, determined by a distance metric.
Decision Trees: Decision Trees recursively partition the data into subsets based on feature values, creating a tree-like structure where each internal node represents a feature, each branch a decision rule, and each leaf node a prediction.

BOOSTING Methods:
XGBoost (Extreme Gradient Boosting) and Gradient Boosting: They sequentially builds a series of decision trees to minimize a loss function and correct errors made by preceding models, using gradient descent optimization.

 Conclusion
After intense data cleaning and preprocessing, I developed a robust laptop price prediction model using a dataset comprising 1,303 laptops and 12 key features, including CPU, RAM, and GPU. Beginning with Linear Regression, I attained an R² score of 80%. Subsequently, employing K-Nearest Neighbors (KNN) improved the score to 81.4%, followed by Decision Trees yielding 88.6%. Implementing advanced boosting techniques such as XGBoost and Gradient Boosting further enhanced performance, achieving an R² score of 86.4%. Finally, leveraging a Voting Regressor ensemble method produced the highest R² score of 89.3%. This approach underscores the efficacy of combining diverse algorithms to achieve superior predictive accuracy in regression modeling.
