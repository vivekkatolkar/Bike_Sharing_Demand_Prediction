# Bike_Sharing_Demand_Prediction
Analysis Of Data In Bike Sharing Demand Prediction


#Inrtoduction

Currently Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. It is important to make the rental bike available and accessible to the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern. The crucial part is the prediction of bike count required at each hour for the stable supply of rental bikes.


#Problem statement

We are tasked with predicting the number of bikes rented each hour so as to make an approximate estimation of the number of bikes to be made available to the public given a particular hour of the day.


#Overview of the data

 We are given the following columns in our data:

Date : year-month-day

Rented Bike count - Count of bikes rented at each hour

Hour - Hour of the day

Temperature-Temperature in Celsius

Humidity - %

Wind Speed - m/s

Visibility - 10m

Dew point temperature - Celsius

Solar radiation - MJ/m2

Rainfall - mm

Snowfall - cm

Seasons - Winter, Spring, Summer, Autumn

Holiday - Holiday/No holiday

Functional Day - No(Non Functional Hours), Yes(Functional hours)


#Steps involved

Installing libraies and getting the dataset.

Performing EDA (exploratory data analysis).

Drawing conclusions from the data.

Preprocessing the data.

Training different models.

Evaluating metrics of all the models.



#Algorithms used

Linear Regression

Decision Tree Regressor

Random Forest Regressor

Extra Trees Regressor


#Conclussion

We used R2-score to understand which model fit our data better, and the scores are as follows:

Linear Regression - 0.77221

Decision Tree Regressor - 0.57645

Random Forest Regressor - 0.98974

Extra Trees Regressor -  0.62611

Its evident from above that the Extra trees regressor model performed well in fitting the data with R2-score of 0..62. The model which performed poorly was elastic net regularization with R2-score of 0..61.
