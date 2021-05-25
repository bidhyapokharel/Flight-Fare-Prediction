( Flight Fare Prediction)

**Short Description:**
This project lets you predict the flight price as per the model that we've prepared.

**Data Collection:**
Data for this project is taken from Kaggle.

**Data Cleansing:**
1. Remove the null values 
2. Convert the string value of Date and Time (Categorical Data) into integers.
(Exploratory Data Analysis)
 Catplot of Price and Airline
![alt text](https://github.com/bidhyapokharel/Flight-Fare-Prediction/blob/master/catplot.png?raw=true)

 Catplot of Price and Source
![alt text](https://github.com/bidhyapokharel/Flight-Fare-Prediction/blob/master/PriceSource.png?raw=true)

**Feature Selection:**   
Using Heatmap and ExtraTreesRegressor, feature selection was done checking out which one is best.
Heatmap (To compare which is more correlated to another)
![alt text](https://github.com/bidhyapokharel/Flight-Fare-Prediction/blob/master/heatmap.png?raw=true)

Checking the feature importance
![alt text](https://github.com/bidhyapokharel/Flight-Fare-Prediction/blob/master/feature.png?raw=true)

**Model Fitting:**
Fit the trained model using Random Forest.
(Scatter Image showing the y_pred and y_test)
![alt text](https://github.com/bidhyapokharel/Flight-Fare-Prediction/blob/master/feature.png?raw=true)

**Hyperparameter Tuning:**
RandomizedSearchCV is used for hyperparameter tuning.

**Save the model:**
Model was saved using Pickle since we might need it later.



