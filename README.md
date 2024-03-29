# House Price Prediction

1. EDA with Pandas and Seaborn
2. Find features with strong correlation to target
3. Data Wrangling, convert categorical to numerical
4. Apply the basic Regression models of sklearn
5. Use gridsearchCV to find the best parameters for each model
6. Compare the performance of the Regressors and choose best one

# Exploratory Data Analysis

#### Get an overview of the feature (Numerical and Categorical) and first look on the target variable (SalePrice)
1. Data Information 
2. Distribution of the Target Variable
3. Grouping Categorical and Numerical Features
4. Data Cleaning (Dealing with Missing Values)

#### Relation of all features to Target Variable
1. Numerical feature correlation coefficient to Target Variable
2. Categorical Feature Relations with Target Varible 

#### Determine the columns that show strong correlation to SalePrice
1. All Numerical Features
2. Determine Features with large correlation to SalePrice_lg

# Data Wrangling / Data Munging
1. Dropping all the freatures with weak correlation with SalePrice
2. Convert Categorical Features to Numrical Features
3. Correlation with all features with SalePrice including converted Categorical Features
4. Creating dataset for ML model with least multicollinearity.
5. Standardizing categorical featuers 

# Modeling Deployment
1. Model Selection with GridSeachCV
2. Linear Regression
3. Ridge Regression 
4. Lasso Regression
5. Elastic Net
6. Stochastic Grandient Descent
7. DecisionTressRegressor
8. RandomForestRegressor
9. KNN Regressor
10. GaussianProcessRegressor
11. Comparison plot: RMSE of all models

# Ensembled Learning
1. Algotithms based on Boosting.
2. Gradient Boosting (GBM)
3. Extreme Gradient Boosting (XGBoost)
4. Light GMB (LGBM)
5. CatBoost
