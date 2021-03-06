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

# Forecasts

### Los Angeles
![alt text](https://github.com/AdamLiscia/Forcasting-Rental-Prices/blob/master/Photos/09%20-%20LA%20City.png)
![alt text](https://github.com/AdamLiscia/Forcasting-Rental-Prices/blob/master/Photos/07%20-%20LA%20Graph.png)
![alt text](https://github.com/AdamLiscia/Forcasting-Rental-Prices/blob/master/Photos/08%20-%20LA%20Results.png)
---
### Chicago
![alt text](https://github.com/AdamLiscia/Forcasting-Rental-Prices/blob/master/Photos/12%20-%20CHI%20City.png)
![alt text](https://github.com/AdamLiscia/Forcasting-Rental-Prices/blob/master/Photos/10%20-%20CHI%20Graph.png)
![alt text](https://github.com/AdamLiscia/Forcasting-Rental-Prices/blob/master/Photos/11%20-%20CHI%20Results.png)
---
### Binghamton
![alt text](https://github.com/AdamLiscia/Forcasting-Rental-Prices/blob/master/Photos/15%20-%20BING%20City.png)
![alt text](https://github.com/AdamLiscia/Forcasting-Rental-Prices/blob/master/Photos/13%20-%20BING%20Graph.png)
![alt text](https://github.com/AdamLiscia/Forcasting-Rental-Prices/blob/master/Photos/14%20-%20BING%20Results.png)
---
### Philadelphia
![alt text](https://github.com/AdamLiscia/Forcasting-Rental-Prices/blob/master/Photos/18%20-%20PHIL%20City.png)
![alt text](https://github.com/AdamLiscia/Forcasting-Rental-Prices/blob/master/Photos/16%20-%20PHIL%20Graph.png)
![alt text](https://github.com/AdamLiscia/Forcasting-Rental-Prices/blob/master/Photos/17%20-%20PHIL%20Results.png)
---
# Predicting Futute Median Rent

### Philadelphia
![alt text](https://github.com/AdamLiscia/Forcasting-Rental-Prices/blob/master/Photos/19%20-%20PHIL%20Future%20Graph.png)
![alt text](https://github.com/AdamLiscia/Forcasting-Rental-Prices/blob/master/Photos/20%20-%20PHIL%20Future%20Code.png)
---
### Chicago
![alt text](https://github.com/AdamLiscia/Forcasting-Rental-Prices/blob/master/Photos/21%20-%20CHI%20Future%20Graph.png)
---
# Future Improvements
- Add exogenous variables to make a more complete model
- Build an interface where a user can enter a city and receive the forecast for that city
