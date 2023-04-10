# Forecasting-Project
Project on forecasting crude oil prices
Oil is a product that moves in completely different directions for a single market event because oil prices are rarely based on real-time data and are instead driven by externalities, making forecasting it even more difficult. As the economy will be highly affected by oil prices, our model will help to understand the pattern in prices to help customers and businesses make smart decisions.

Crude oil price movements are influenced by a variety of factors. This dataset was retrieved from the U.S. Energy Information Administration.
The aim of this dataset and work is to predict future crude oil prices based on the historical data available in the dataset.
The data contains daily Brent oil prices from the 29th of January 1998 until the 29th of January 2023.


Objective of the Analysis
Because oil prices are rarely based on real-time data and are instead driven by externalities, it is difficult to forecast. As the economy will be highly affected by oil prices, our model will help understand the pattern in prices to help customers and businesses make smart decisions.
There are 6,518 records in the dataset without any duplicates.
The datafile contained 179 null values, which were handled by interpolation.


The 2008 financial crisis and the Great Recession that followed had a pronounced negative impact on the oil and gas sector as it led to a steep decline in oil and gas prices and a contraction in credit. The decline in prices resulted in falling revenues for oil and gas companies.
The price of a barrel of crude oil decreased from $133.88 to $39.09 in just a less than a year.
The recession led to a general drop in asset prices around the world as credit contracted and earnings projections fell.
At the same time, rising unemployment and lower spending led to less demand for oil by both consumers and businesses.


The initial drop in oil prices from mid-2014 to early 2015 was primarily driven by supply factors, including booming U.S. oil production, receding geopolitical concerns, and shifting OPEC policies. 
However, deteriorating demand prospects played a role as well, particularly from mid-2015 to early 2016. 
Oversupply of crude oil compared to demand caused the drop in Oil prices.
In 2020, worldwide demand for oil fell rapidly as governments closed businesses and restricted travel due to the COVID-19 pandemic.
An oil price war between Russia and Saudi Arabia erupted in March when the two nations failed to reach a consensus on oil production levels.


![image](https://user-images.githubusercontent.com/114068300/230824964-7ef67775-ab03-46ca-8878-86717f5235c7.png)


Autocorrelation is the correlation between a time series with a lagged version of itself. The correlation between the observation at the current time spot and the observations at previous time spots, while the ACF plots the correlation coefficient against the lag, and it’s a visual representation of autocorrelation. So here there is a strong correlation even for lag=60.
Out of all the models, ARIMA gave the lowest error. Hence use this model for forecasting![image](https://user-images.githubusercontent.com/114068300/230825102-55cbeaba-0203-4908-afcc-fcdd4309a729.png)
