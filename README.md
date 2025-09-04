# Gradient-Boosting-Regressor


# Boston Housing Price Prediction (Gradient Boosting)

## Overview
This project uses the **Boston Housing Dataset** to predict house prices (`MEDV`) using various regression models. After performing **Exploratory Data Analysis (EDA)** and preprocessing, I trained and evaluated **Gradient Boosting Regressor**, which gave the best performance.


##  Dataset
- **Features:** CRIM, ZN, INDUS, CHAS, NOX, RM, AGE, DIS, RAD, TAX, PTRATIO, B, LSTAT  
- **Target:** MEDV (Median value of owner-occupied homes in $1000s)

## Exploratory Data Analysis (EDA)
- Univariate Analysis (distribution plots, histograms)
- Bivariate Analysis (feature vs target scatter plots)
- Multivariate Analysis (correlation heatmap)
- Feature importance via correlation and model insights


##  Preprocessing
- Handling missing values  
- Standardization using `StandardScaler`  
- Train-test split (80/20)  


## Models Trained
- Linear Regression (baseline)  
- Ridge, Lasso, Elastic Net  
- Decision Tree Regressor  
-  Gradient Boosting Regressor (best performer)  


## Results (Gradient Boosting)
- **MAE:** 1.86  
- **MSE:** 5.93  
- **RMSE:** 2.43  
- **R² Score:** 0.92  

## Visualizations
1. **Feature Importance Plot**
2. **Actual vs Predicted Plot**
3. (Optional) Residual Plot

##  Key Insights
- Gradient Boosting captured **non-linear patterns** better than linear models.  
- Features like **LSTAT, RM, PTRATIO, NOX** had the highest importance.  
- The model explains ~92% variance in house prices, showing strong predictive power.  

## Technologies Used
- Python (pandas, numpy, matplotlib, seaborn)
- scikit-learn (GradientBoostingRegressor, StandardScaler, metrics)

##  Next Steps
- Hyperparameter tuning with GridSearchCV  
- Compare with XGBoost, LightGBM, CatBoost  
- Deploy as a simple **Streamlit app** for price prediction  

