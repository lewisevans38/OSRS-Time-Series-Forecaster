# OSRS-Time-Series-Forecaster
This project uses XGBoost and the APIs on https://oldschool.runescape.wiki/w/RuneScape:Real-time_Prices to create a time series that can forecast the next hour value of AvgHighPrice, AvgLowPrice, AvgHighVolume and the AvgLowVolume.
The two auxilliary files help with interfacing with the APIs. One (terribly) named LatestPriceDatabaseBuilder creates a database of every listed item. The other more aptly named Grabber, pulls the time series of the specific inputted item from the API
giving hour wise increment values of the aforementioned columns. 

This project although small was an absolute blast to do and maybe will even make me filthy rich.
