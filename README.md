# FIT3152 2025S1 Assignment 2

1. **Data Preprocessing**:
   - No missing values; low-variance features (e.g., `A19`, `A01`) identified.
   - Class imbalance addressed via SMOTE oversampling and scaling.

2. **Models Evaluated**:
   - **Baseline Models**: Decision Tree, Naïve Bayes, Bagging, Boosting, Random Forest.
   - **Optimized Models**: Random Forest (tuned) and LightGBM (best performer).

3. **Performance Highlights**:
   - **LightGBM**: Highest accuracy (0.93), recall (0.91), and AUC (0.976).
   - **Random Forest (Optimized)**: Balanced metrics (Accuracy: 0.91, F1: 0.90).
   - **Simple Rules**: High recall (0.78) but low accuracy (0.50).

4. **Feature Importance**:
   - Top predictors: `A26`, `A07`.
   - Least important: `A19`, `A01` (omitted in final models).

## **Conclusion**
LightGBM outperformed others after hyperparameter tuning and handling class imbalance. Feature selection and resampling were critical for improving minority class detection.
