# Solar-Power-Generation-Forecasting-Using-ML
📌 1. Project Overview

Predict short-term solar power generation using ML models.

Improve energy planning, grid stability, and solar plant efficiency.

Use weather parameters (irradiance, temperature, humidity, etc.) to forecast AC/DC power.

Compare multiple ML models under identical preprocessing and training conditions.

Deploy the most accurate model (Random Forest) based on evaluation metrics.


📌 2. Problem Statement

Solar power output is highly variable due to unpredictable weather.

Traditional forecasting methods are often inaccurate.

Poor predictions cause grid imbalance and energy losses.

Need a robust AI/ML-based model to estimate output reliably.


📌 3. Project Objectives

Build accurate ML models for solar power prediction.

Analyze impact of weather features on energy generation.

Identify the best-performing algorithm among LR, DT, RF, XGBoost, LGBM.

Apply advanced preprocessing and hyperparameter tuning.

Deliver an energy-efficient, sustainable solution for smart grids.

📌 4. Dataset Details

File: final_combined_Data_CI.csv

Total Records: 136,476

Features: 10 columns (Date-Time, Plant ID, Temperatures, Irradiance, AC/DC power, etc.)

Data collected from multiple solar power plants using real sensor logs.


📌 5. Data Preprocessing

Handling missing values (mean/median imputation).

Outlier removal for irradiance & power spikes.

Time-based feature extraction (Hour, Day, Month).

Feature scaling using StandardScaler / MinMaxScaler.

Correlation analysis & feature selection.

80:20 Train–Test split.


📌 6. Machine Learning Models Implemented

Linear Regression – baseline model.

Decision Tree Regressor – handles nonlinear patterns.

Random Forest Regressor – Best performer with highest R² ≈ 0.9998.

XGBoost Regressor – fast gradient boosting model.

LightGBM – high-performance boosting for large datasets.


📌 7. Model Optimization

Hyperparameter tuning using GridSearchCV.

Parameters tuned: n_estimators, max_depth, learning_rate, etc.

Applied 5-fold cross-validation for reliable performance.


📌 8. Evaluation Metrics

MAE – Mean Absolute Error

MSE – Mean Squared Error

RMSE – Root Mean Squared Error

R² Score – Variance explained by the model


📌 9. Model Performance Summary

From the comparison table:

Linear Regression → Good baseline, lower accuracy.

Decision Tree → High accuracy but risk of overfitting.

Random Forest → BEST (R² = 0.9998, lowest RMSE).

XGBoost & LightGBM → Strong results with fast training.


📌 10. Champion Model: Random Forest

Best at capturing nonlinear relations.

Low MAE & RMSE; high generalization.

Most stable under cross-validation.

Excellent visualization match between predicted vs actual AC Power.


📌 11. Applications

Smart energy management systems.

Solar plant optimization & maintenance.

Real-time load balancing for power grids.

Renewable energy forecasting dashboards.


📌 12. Societal Impact

Promotes clean energy adoption & reduces carbon footprint.

Supports SDG 7 & SDG 13 for sustainability.

Enables cost-efficient energy planning.

Encourages innovation in AI-driven climate solutions.
