⚽ Football Player Value Prediction (ML & DL Project)
📌 Overview

This project focuses on predicting football players’ market value (value_eur) using machine learning and deep learning techniques.
It includes full data preprocessing, exploratory data analysis, model comparison, hyperparameter tuning, neural network experimentation, and model interpretability using SHAP.

📊 Dataset

The dataset contains attributes of professional football players, including:

Age, overall rating, potential
Technical skills (pace, shooting, passing, dribbling, defending, physicality)
Club information
Market value and wage

Data is filtered to:

Remove missing or invalid values
Focus on professional-level players (overall > 60)
🧹 Data Processing
Handling missing values (e.g., goalkeeper attributes)
Feature selection
One-hot encoding for categorical variables
Feature scaling using StandardScaler
Train/test split (80/20)
📈 Exploratory Data Analysis (EDA)

Performed using matplotlib and seaborn:

Distribution of player market values
Wage comparison across top clubs
Correlation heatmap between features
🤖 Machine Learning Models

The following models were trained and compared:

Linear Regression
Decision Tree Regressor
Random Forest Regressor (with GridSearchCV tuning)
Evaluation metrics:
R² score
RMSE (for Random Forest)

Best performing model is selected automatically based on R² score.

🧠 Deep Learning

A Multilayer Perceptron (MLPRegressor) was used to compare different architectures:

(64,)
(128, 64)
(256, 128, 64)

Models were evaluated using:

R² score
RMSE
Loss curves visualization
🔍 Model Interpretability

SHAP (TreeExplainer) is used to explain feature importance and model predictions.

🛠 Technologies Used
Python
Pandas, NumPy
Scikit-learn
Matplotlib, Seaborn
SHAP
📌 Key Features
End-to-end ML pipeline
Hyperparameter tuning (GridSearchCV)
Deep learning comparison
Data visualization & EDA
Model interpretability (SHAP)
🚀 Results
Multiple ML models compared
Random Forest achieved best performance
Neural networks tested for benchmarking
Final model selected based on R² score
