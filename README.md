# capstone-project-Machine-learning-
#Title: Bike Sharing demand Prediction
# Introduction & objective 
Currently Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. It is important to make the rental bike available and accessible to the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern. The crucial part is the prediction of bike count required at each hour for the stable supply of rental bikes.Objective of this project is to correctly predict Bike to be rented in differnt time periods,differnt climatic conditions in Seoul City.
# Rental prediction model can be done by using differnt machine learning Regression algorithms.
# This project aims to correctly predict bike demand in near future so that we can make necessary arrangemets beforehand.
# By employing exploratory data analysis (EDA) and robust machine learning regression algorithms,
# we will unveil hidden insights in customer behavior, enabling us to target campaigns with laser-sharp precision.
# This translates to higher engagement, deeper customer relationships, and optimized marketing ROI.
# Dataset & Variables
Describing DataSet
The dataset contains weather information (Temperature, Humidity, Windspeed, Visibility, Dewpoint, Solar radiation, Snowfall, Rainfall), the number of bikes rented per hour and date information.

Attribute Information:
Date : year-month-day
Rented_Bike_Count - Count of bikes rented at each hour
Hour - Hour of he day
Temperature-Temperature in Celsius
Humidity - %
Windspeed - m/s
Visibility - 10m
Dew point temperature - Celsius
Solar radiation - MJ/m2
Rainfall - mm
Snowfall - cm
Seasons - Winter, Spring, Summer, Autumn
Holiday - Holiday/No holiday
Functional Day - NoFunc(Non Functional Hours), Fun(Functional hours)
# Machine learning models used for Prediction
Linear Regression, Ridge,Lasso and Elastic Regression, Decision Tree , Random Forest , AdaboostRegressor , GradientBoosting Regressor, KNN,XG Boost.
# Conclusion 
*Model Name	Adjusted R-Square
0	XgBoost Regression	91.41
1	Random Forest	78.80
2	Decision Tree	78.80
3	Ridge Regression	72.51
4	Lasso Regression	72.49
5	Multilinear	69.46
6	Elastic Net Regression	69.41
7	Polynomial	66.70
8	Adaboost	63.33
**Numerous performance metrics, such as R Square, Adjusted R Square, Mean Squared Error, and Root Mean Squared Error, are available for assessing the efficacy of regression models. The choice of the metric should be determined through comprehensive discussions with domain experts. In this instance, the model's predictive performance is evaluated using Adjusted R Square. It is noteworthy that alternative metrics can also be applied to appraise the model.

It is observed that the XGBoost Regressor yields the highest Adjusted R Square value among the models considered. Consequently, the recommendation is to employ XGBoost Regression for predicting rental bike demand based on r square

