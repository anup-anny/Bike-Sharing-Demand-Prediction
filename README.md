# Seoul-Bike-Sharing-Demand-Prediction
![image](https://user-images.githubusercontent.com/105309015/190987694-512904a7-3f4c-4f10-b5be-0ed2bb34df52.png)

# Problem Statement:
Currently Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. It is important to make the rental bike available and accessible to the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern. The crucial part is the prediction of bike count required at each hour for the stable supply of rental bikes.

# Data Description:
The dataset contains weather information (Temperature, Humidity, Windspeed, Visibility, Dewpoint, Solar radiation, Snowfall, Rainfall), the number of bikes rented per hour and date information.

# Attribute Information:

• Date : year-month-day

• Rented Bike count - Count of bikes rented at each hour

• Hour - Hour of the day

• Temperature-Temperature in Celsius

• Humidity - %

• Windspeed - m/s

• Visibility - 10m

• Dew point temperature - Celsius

• Solar radiation - MJ/m2

• Rainfall - mm

• Snowfall - cm

• Seasons - Winter, Spring, Summer, Autumn

• Holiday - Holiday/No holiday

• Functional Day - NoFunc(Non Functional Hours), Fun(Functional hours)

# Data Pipeline:

● Exploratory Data Analysis (EDA): In this part we have done some EDA on the features to see the trend.

● Data Processing: In this part we went through each attributes and encoded the categorical features.

● Model Creation: Finally in this part we created the various models. These various models are being analysed and we tried to study various models so as to get the best performing model for our project.

# Algorithms Used :

Regularized linear regression:

• Lasso regression

• Ridge regression

• Elastic net regression

Ensemble techniques:

• Decision tree regression

• Random-forest regression

• XG–Boost regression

• XG–Boost GridsearchCV

• Regression

# Conclusions:

• No overfitting is seen.

• When we compare the root mean squared error and mean absolute error of all the models, the XG- boost grid search CV regression model has less root mean squared error and mean absolute error, ending with the Adj. R-squared of 91% in test data. So, finally, this model is best for predicting the bike rental count on daily basis.

• For all the models, temperature and Functioning days were ranked as the most influential variable to predict the rental bike demand at each hour.
