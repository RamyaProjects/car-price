# Car Price Prediction
**Overview**

This project aims to predict car prices using various machine learning models including Linear Regression, Random Forest, Decision Trees, and Bagging Regressors. It involves exploratory data analysis (EDA), preprocessing, feature engineering, model building, evaluation, and hyperparameter tuning.

**Technologies Used**

- Python
- NumPy, Pandas
- Scikit-learn
- Statsmodels
- Matplotlib, Seaborn
- GridSearchCV for hyperparameter tuning

**Workflow**

**1. Exploratory Data Analysis (EDA)**
- Initial understanding of feature distributions.
- Identification of correlations, outliers, and multicollinearity.

**2. Data Preprocessing**
- Categorical Encoding: Using pd.get_dummies().
- Boolean Mapping: Converted True/False to 1/0.
- Feature Scaling: StandardScaler applied to features like Mileage.
- Train-Test Split: 70-30 split using train_test_split().

**3. Feature Engineering**
- Multicollinearity Check: Used Variance Inflation Factor (VIF).
- Recursive Feature Elimination (RFE): To select top-performing features.
- Manual Feature Elimination: Based on VIF and high p-values.

**Models Implemented**
  - Linear Regression
  - OLS Regression
  - Random Forest Regressor
  - Decision Tree Regressor
  - Bagging Regressor
 
**Model Evaluation Metrics**
Each model was evaluated using:
- R² Score: Proportion of variance explained.
- RMSE (Root Mean Squared Error)
- MAE (Mean Absolute Error)
- MSE (Mean Squared Error)

**Plots included:**
- Distribution plots of predicted vs actual values.
- Residual plots for linear regression.

