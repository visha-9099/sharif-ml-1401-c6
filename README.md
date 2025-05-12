📚 Sharif ML 1401 - Competition C6: Predicting Target Values in Scientific Data
The sharif-ml-1401-c6 project is part of the Sharif University of Technology Machine Learning Course Competitions (1401 Series). 
In this specific competition (C6), participants are challenged to develop regression models that can accurately predict a target value from scientific or experimental data. 
The task is inspired by real-world applications in engineering and applied sciences, where learning complex relationships between variables is essential for modeling, forecasting, and optimization.

🎯 Objective
The goal of this challenge is to use a provided dataset to train a machine learning regression model that can estimate a continuous target variable (y) based on a diverse set of input features. 
The model must generalize well and achieve high predictive performance on unseen test data.

🧪 Dataset Overview
The dataset includes:

Numerical and possibly categorical features representing characteristics of physical, chemical, or process-oriented data.

A target column (y) that reflects a measurable outcome, such as temperature, efficiency, or concentration.

A split between train and test datasets, provided in CSV format.

🧵 Workflow
1. Exploratory Data Analysis (EDA)
Summary statistics, null value check

Visualizations of distributions

Feature correlation analysis

Outlier detection

2. Preprocessing
Handling missing values (if any)

Feature scaling using StandardScaler or MinMaxScaler

One-hot encoding or ordinal encoding for categorical data

3. Modeling Approaches
Linear Regression

Ridge & Lasso Regression

Decision Tree Regressor

Random Forest Regressor

Gradient Boosting Machines (XGBoost, LightGBM)

Neural Networks with TensorFlow/Keras

4. Evaluation
K-Fold Cross-Validation

Root Mean Squared Error (RMSE)

R² Score

Learning curves and residual plots

🧠 Highlights
Model interpretability: SHAP values and feature importance were used to understand which features most influenced predictions.

Hyperparameter tuning: Used GridSearchCV and Optuna to improve performance.

Model ensembles: Averaging and stacking multiple models to reduce variance and increase accuracy.

📈 Final Results
Achieved strong predictive performance on the private leaderboard using ensemble gradient boosting models. 
The model generalizes well and is capable of capturing both linear and non-linear relationships in the data.


🛠️ Technologies Used
Python 3.x

Pandas, NumPy

Scikit-learn

XGBoost / LightGBM

Matplotlib, Seaborn

SHAP (Model Explainability)
