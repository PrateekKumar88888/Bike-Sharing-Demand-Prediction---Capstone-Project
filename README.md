# Bike-Sharing-Demand-Prediction---Capstone-Project
# Problem Statement
Currently Rental bikes are introduced in many urban cities for the enhancement of mobility comforts. It is important to make the rental bike available and accessible to the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a mojor concern. The crucial part is the prediction of bike count required at each hour for the stable supply of rental bikes.
# Features Information
- Date -  year-month-day
-Rented Bike count - Count of bikes rented    at each hour
-Hour - Hour of he day
-Temperature-Temperature in Celsius
-Humidity - %
-Windspeed - m/s
-Visibility - 10m
-Dew point temperature - Celsius
-Solar radiation - MJ/m2
-Rainfall - mm
-Snowfall - cm
-Seasons - Winter, Spring, Summer, Autumn
-Holiday - Holiday/No holiday
-Functional Day – NoFunc (Non Functional Hours), Fun (Functional hours)
# Introduction
The dataset contains weather information (Temperature, Humidity, Windspeed, Visibility, Dewpoint, Solar radiation, Snowfall, Rainfall), the number of bikes rented per hour and date information.In this project, we train a model to predict the number of bike rentals at any hour of the year given the weather conditions.We first build several individual regression models such as Linear, Lasso, Ridge, Random Forest, Gradient Boost and XGBoost.
# Data Pipeline
Exploratory Data Analysis (EDA): In this part we have done some EDA on the features to see the trend.
Data Processing: In this part we went through each attributes and encoded the categorical features.
Model Creation: Finally in this part we created the various models. These various models are being analysed and we tried to study various models so as to get the best performing model for our project.
# Comparison
When we compare the root mean squared error and mean absolute error of all the models, Random forest Regressor and Gradient Boosting gridsearchcv gives the highest R2 score of 99% and 95% respectively for Train Set and 92% for Test set. So, finally this model is best for predicting the bike rental count on daily basis.
# Conclusion
During the time of our analysis, we initially did EDA on all the features of our dataset. We first analysed our dependent variable, ’Rented Bike Count and also transformed it.
Bike rental count is mostly correlated with the time of the day as it is peak at 10 am morning and 8 pm at evening.
The result of our evaluation are: 
       -No overfitting is seen. 
       -Random Forest Regressor and Gradient Boosting gridsearchcv gives the highest R2 score of 99% and 95% respectively for Train Set and 92% for Test Set.
