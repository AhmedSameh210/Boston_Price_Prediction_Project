# Boston Price Prediction Project
This project aims to predict the prices of houses in Boston using various machine learning models. The data was preprocessed using exploratory data analysis, feature engineering, and feature selection. Six models were trained, including linear regression, KNN regressor, decision tree regressor, random forest, XGBoost, and SVR. XGBoost was chosen for deployment as it provided the best accuracy at 90%.

# Tools Used
The following tools were used for data preprocessing and analysis:

Python (version 3.7)
Numpy (version 1.16.4)
Pandas (version 0.24.2)
Matplotlib (version 3.1.0)
Seaborn (version 0.9.0)
Scikit-learn (version 0.21.2)
XGBoost (version 0.82)
Exploratory Data Analysis
The dataset used for this project is the Boston Housing dataset available in scikit-learn. The dataset contains 506 rows with 13 features including crime rate, average number of rooms per dwelling, and nitric oxides concentration.

A profile report was generated using Pandas profiling to visualize the distribution of each feature, detect missing values, and identify correlations between features. This profile report helped to identify features that required cleaning and preprocessing.

# Feature Engineering and Selection
The following feature engineering and selection techniques were used:

Correlation analysis using Seaborn to identify features with high correlation to the target variable
# Models
The following machine learning models were trained to predict the prices of houses in Boston:

* Linear Regression
* KNN Regressor
* Decision Tree Regressor
* Random Forest
* XGBoost
* SVR
# Model Selection
The performance of each model was evaluated using RMSE and R-squared metrics. The XGBoost model provided the best accuracy at 90%. Therefore, it was chosen for deployment.
A user option was created to allow users to enter the required features and display the predicted price.

# Conclusion
This project demonstrates the importance of exploratory data analysis, feature engineering, and model selection in machine learning projects. The XGBoost model provided the best accuracy for predicting the prices of houses in Boston. The user option allows users to easily enter feature inputs and obtain a predicted price.
