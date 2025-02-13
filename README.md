# intern_project
#World happiness index analysis 


This project analyzes the World Happiness Index dataset to identify key factors influencing happiness scores across different countries. The dataset includes variables such as GDP per capita, social support, healthy life expectancy, freedom to make life choices, generosity, and perceptions of corruption.

Objectives

Perform data preprocessing, including handling missing values and removing outliers.

Visualize relationships between happiness scores and various factors.

Train and evaluate multiple regression models to predict happiness scores.

Optimize model performance using hyperparameter tuning.

Dataset

Source: World Happiness Report 2022

File: 2022.csv

Key Features:

Country or region: Name of the country.

Score: Happiness score based on survey data.

GDP per capita: Economic indicator.

Social support: Level of social security.

Healthy life expectancy: Expected lifespan in good health.

Freedom to make life choices: Individual freedom level.

Generosity: Charitable behavior.

Perceptions of corruption: Trust in government and business.

Data Preprocessing

Handling Missing Values: Checked for missing data and ensured data integrity.

Outlier Removal: Used the Interquartile Range (IQR) method to remove outliers in key numerical features.

Data Normalization: Standardized features using StandardScaler to improve model performance.

Exploratory Data Analysis (EDA)

Correlation Matrix: Identified relationships between variables using a heatmap.

Scatter Plots: Visualized feature relationships with happiness scores.

Box Plots: Checked for outliers and distribution of key variables.

Bar Plot: Compared happiness scores across countries.

Machine Learning Models

The following regression models were implemented:

Linear Regression

Decision Tree Regressor

Random Forest Regressor

Gradient Boosting Regressor

AdaBoost Regressor

K-Nearest Neighbors Regressor

XGBoost Regressor

Model Evaluation

Metrics Used:

Mean Squared Error (MSE)

Mean Absolute Error (MAE)

R-squared Score (R²)

Hyperparameter Tuning: Performed GridSearchCV to optimize model performance.

Results & Insights

GDP per capita, social support, and healthy life expectancy show a strong correlation with happiness scores.

Random Forest and XGBoost performed best in predicting happiness scores.

Countries with high GDP per capita and social support generally rank higher in happiness.

Installation & Usage

Requirements:

Python 3.x

Required Libraries:

pip install pandas numpy matplotlib seaborn scikit-learn xgboost

Running the Analysis:

python happiness_analysis.py

Conclusion

This project provides insights into factors influencing happiness worldwide and leverages machine learning models for predictions. Further improvements can include additional socio-economic factors and deep learning approaches.
