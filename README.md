# Forcasting-Rental-Prices
Time Series Analysis on the Zillow Rental Index

![alt text](https://github.com/AdamLiscia/Forcasting-Rental-Prices/blob/master/Photos/01-%20Zillow.png)

# Overview
- Obtained a Kaggle dataset on median real estate rental prices in hundreds of U.S. cities
- Goal was to forecast real estate prices for selected U.S. cities in the future
- Performed Time Series Analysis in order to make forecasts

![alt text](https://github.com/AdamLiscia/Forcasting-Rental-Prices/blob/master/Photos/02%20-%20For%20Rent.png)

# EDA
- There doesn't appear to be any seasonality
- A log transformation seems to be appropriate

![alt text](https://github.com/AdamLiscia/Forcasting-Rental-Prices/blob/master/Photos/03%20-%20EDA.png)

# Obtaining Stationary Data
- Want your data to be independent of time when forecasting
- We did this by transforming the data
- Transformations removes trends and cycles from the data


![alt text](https://github.com/AdamLiscia/Forcasting-Rental-Prices/blob/master/Photos/05%20-%20All%20The%20Transformations.png)


![alt text](https://github.com/AdamLiscia/Forcasting-Rental-Prices/blob/master/Photos/04%20-%20Dickey%20Fuller%20Results.png)

# ACF and PACF

![alt text](https://github.com/AdamLiscia/Forcasting-Rental-Prices/blob/master/Photos/06%20-%20PAC%20ACF.png)
![alt text]()
