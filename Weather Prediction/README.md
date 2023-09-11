# Weather Prediction using ridge regression

Overview:
  
  In this project, we predict the average temperature using the historical data. It is a supervised machine learning model.
  
  For this project, we took the dataset of Toronto City, from 4th June 2002 to 11th February 2023, from National Centers for Environmental Information which is an official website of United States Government (https://www.ncei.noaa.gov/access/past-weather/toronto). 
  The dataset contains Station code, City, Longitude, Latitude, Elevation, Date, Precipitation, SnowDepth, Maximum, Minimum and Average temperatures with many missing values.
  
  We read the data using Pandas, taking the date column as index for easy calculations and lookup. Initially we clean the data making it suitable for machine learning model.
  And then by using Ridge regression model we predict the average temperature. A Ridge regressor is a regularized version of a Linear Regressor. This model has an average of 4.18 error from the actual temperature.
  
To learn more about Ridge Regression:
  https://machinelearningcompass.com/machine_learning_models/ridge_regression/
  https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.ridge_regression.html

Refer to the documentation of the dataset to to understand the dataset.

To see dataset in kaggle: https://www.kaggle.com/code/jibinmadayil/weather-prediction
