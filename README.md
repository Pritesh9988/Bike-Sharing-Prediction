# Bike-Sharing-Prediction
Project title -  Seoul Bike Sharing Demand Prediction

Problem statement – 
                    Currently Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. It is important to make the rental bike available and accessible to the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern. The crucial part is the prediction of bike count required at each hour for the stable supply of rental bikes.

Data Description – 
•	Date : year-month-day
•	Rented Bike count - Count of bikes rented at each hour
•	Hour - Hour of the day
•	Temperature-Temperature in Celsius
•	Humidity - %
•	Windspeed - m/s
•	Visibility - 10m
•	Dew point temperature - Celsius
•	Solar radiation - MJ/m2
•	Rainfall - mm
•	Snowfall - cm
•	Seasons - Winter, Spring, Summer, Autumn
•	Holiday - Holiday/No holiday
•	Functional Day - NoFunc(Non Functional Hours), Fun(Functional hours)

Data Analysis –
•	From data analysis we observed that requirement of bike is highest at evening time and very low at early morning.
•	In whole month bike sharing requirement is near about same except starting of month.
•	In middle of the year Bike requirement is on its peak. 
Models Used – 
•	Linear Regression – Lasso, Ridge
•	Elastic Net
•	Decision Tree
•	Random Forest
•	Gradient Boosting
•	XGBoost

Final Conclusion –
●	The Rented Bike count is highly correlated with temperature i.e. in summer more no. of bikes gets rented as compared to winter. Whereas it seems that the rentals are independent of the wind speed and the humidity, because they are almost constant over the months. So people mainly rent bikes on nice days and nice temperature.
●	we use different algorithms to build model with high accuracy to predict count of rented bikes. so by comparing results from different algorithm we found that XGBoost algorithm gives best results.XGBoost has highest accuracy 96% and lowest RMSE,MAE with respect to other algorithms. So finally this model is best for predicting the bike rental count on daily basis.


