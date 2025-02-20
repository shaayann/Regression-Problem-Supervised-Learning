# Regression-Problem-Supervised-Learning
## House Price Prediction Using Machine Learning

## 1️⃣ Objective

Build a predictive model to estimate house prices based on various features (e.g., area, bedrooms, parking, etc).

## 2️⃣ Data Preprocessing

Dataset: Housing.csv

Handling Categorical Data:
Binary variables (yes/no) → Converted to 1/0.

furnishingstatus (multi-class) → Mapped to numerical values (furnished = 2, semi-furnished = 1, unfurnished = 0).

Other categorical variables → One-Hot Encoded.

Feature Scaling: Applied StandardScaler to numerical features.

## 3️⃣ Machine Learning Models

Random Forest Regressor (n_estimators=100)

XGBoost Regressor (n_estimators=100, learning_rate=0.1)

## 4️⃣ Model Evaluation (Performance Metrics)

Random Forest (R² = 0.611) → Explains 61.1% of price variation.

XGBoost (R² = 0.600) → Explains 60.0% of price variation.

Error Metrics (for both models):

MAE (Mean Absolute Error): Measures average absolute prediction error.

MSE (Mean Squared Error): Penalizes large errors.

RMSE (Root Mean Squared Error): Similar to MSE but interpretable in the original price scale.

## 5️⃣ Feature Importance Analysis

Top contributing factors to price prediction are visualized using feature importance plots for both models.

## 6️⃣ Visualization

Actual vs. Predicted Price Scatter Plot → Shows how well models perform.

Feature Importance Plots → Identify key features affecting price.
