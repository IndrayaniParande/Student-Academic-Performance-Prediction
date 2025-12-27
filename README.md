#### 🎓 Student Academic Performance Prediction

This project is an end-to-end machine learning regression system designed to predict a student’s Math score using demographic and academic features. The solution demonstrates the complete ML lifecycle — from data ingestion and preprocessing to multi-model training, hyperparameter tuning, model selection, and deployment.

📌 Problem Statement
Given a student’s background information and academic indicators, predict the Math score (0–100) accurately using machine learning techniques.

📊 Dataset Overview
The dataset contains student-level academic and demographic information with the following features:

Feature	Description
gender	Student gender
race_ethnicity	Student race/ethnicity group
parental_level_of_education	Highest education level of parent
lunch	Lunch type (standard / free or reduced)
test_preparation_course	Test preparation course status
reading_score	Reading score (0–100)
writing_score	Writing score (0–100)
math_score (target)	Math score to be predicted

🧠 Modeling Approach

The project follows a robust model comparison strategy by training and evaluating multiple regression algorithms with hyperparameter tuning.

🔹 Models Trained

The following regression models are implemented and compared:

Linear Regression
Decision Tree Regressor
Random Forest Regressor
Gradient Boosting Regressor
K-Nearest Neighbors Regressor
AdaBoost Regressor
XGBoost Regressor
CatBoost Regressor

🔹 Hyperparameter Tuning

Each model is trained using custom parameter grids to optimize performance.
Examples include:

Number of estimators
Learning rate
Tree depth
Distance metrics and weights (for KNN)
Loss functions (for boosting models)
Model evaluation is performed using train-test split and R² score as the primary metric.

🖥️ Deployment

A web-based interface allows users to:

Enter student demographic and academic details
Predict Math score in real time using the trained model
This makes the system accessible to non-technical users.
