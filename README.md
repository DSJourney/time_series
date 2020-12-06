# Time Series

This project was created to learn about time series. I am taking a public dataset called [Sales in Stormy Weather](https://www.kaggle.com/c/walmart-recruiting-sales-in-stormy-weather/data)

The dataset was put together by [Walmart](https://www.walmart.com/) the retail corporation that operates a chain of hypermarkets, discount department stores, and grocery stores

You have been provided with sales data for 111 products whose sales may be affected by the weather (such as milk, bread, umbrellas, etc.). These 111 products are sold in stores at 45 different Walmart locations. Some of the products may be a similar item (such as milk) but have a different id in different stores/regions/suppliers. The 45 locations are covered by 20 weather stations (i.e. some of the stores are nearby and share a weather station).

The competition task is to predict the amount of each product sold around the time of major weather events. For the purposes of this competition, we have defined a weather event as any day in which more than an inch of rain or two inches of snow was observed. You are asked to predict the units sold for a window of ±3 days surrounding each storm.

Field descriptions
- date - the day of sales or weather
- store_nbr - an id representing one of the 45 stores
- station_nbr - an id representing one of 20 weather stations
- item_nbr - an id representing one of the 111 products
- units - the quantity sold of an item on a given day
- id - a triplet representing a store_nbr, item_nbr, and date. Form the id by concatenating these (in that order) with an underscore. E.g. "2_1_2013-04-01" represents store 2, item 1, sold on 2013-04-01.

Here's the decryption key: Work4WalmarT
