# Solar-Power-Generation-Forecasting-Using-ML
📌 1. Project Overview

1] Predict short-term solar power generation using ML models.

2] Improve energy planning, grid stability, and solar plant efficiency.

3] Use weather parameters (irradiance, temperature, humidity, etc.) to forecast AC/DC power.

4] Compare multiple ML models under identical preprocessing and training conditions.

5] Deploy the most accurate model (Random Forest) based on evaluation metrics.


📌 2. Problem Statement

1] Solar power output is highly variable due to unpredictable weather.

2] Traditional forecasting methods are often inaccurate.

3] Poor predictions cause grid imbalance and energy losses.

4] Need a robust AI/ML-based model to estimate output reliably.


📌 3. Project Objectives

1] Build accurate ML models for solar power prediction.

2] Analyze impact of weather features on energy generation.

3] Identify the best-performing algorithm among LR, DT, RF, XGBoost, LGBM.

4] Apply advanced preprocessing and hyperparameter tuning.

5] Deliver an energy-efficient, sustainable solution for smart grids.

📌 4. Dataset Details

File: final_combined_Data_CI.csv

Total Records: 136,476

Features: 10 columns (Date-Time, Plant ID, Temperatures, Irradiance, AC/DC power, etc.)

Data collected from multiple solar power plants using real sensor logs.


📌 5. Data Preprocessing

1] Handling missing values (mean/median imputation).

2] Outlier removal for irradiance & power spikes.

3] Time-based feature extraction (Hour, Day, Month).

4] Feature scaling using StandardScaler / MinMaxScaler.

5] Correlation analysis & feature selection.

6] 80:20 Train–Test split.


📌 6. Machine Learning Models Implemented

1] Linear Regression – baseline model.

2] Decision Tree Regressor – handles nonlinear patterns.

3] Random Forest Regressor – Best performer with highest R² ≈ 0.9998.

4] XGBoost Regressor – fast gradient boosting model.

5] LightGBM – high-performance boosting for large datasets.


📌 7. Model Optimization

1] Hyperparameter tuning using GridSearchCV.

2] Parameters tuned: n_estimators, max_depth, learning_rate, etc.

3] Applied 5-fold cross-validation for reliable performance.


📌 8. Evaluation Metrics

MAE – Mean Absolute Error

MSE – Mean Squared Error

RMSE – Root Mean Squared Error

R² Score – Variance explained by the model




📌 9. Champion Model: Random Forest

1] Best at capturing nonlinear relations.

2] Low MAE & RMSE; high generalization.

3] Most stable under cross-validation.

4] Excellent visualization match between predicted vs actual AC Power.


📌 10. Applications

1] Smart energy management systems.

2] Solar plant optimization & maintenance.

3] Real-time load balancing for power grids.

4] Renewable energy forecasting dashboards.



