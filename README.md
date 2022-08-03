# Avocado-Price-Prediction
Accuracy 91% and RMSE 0.07, Using XGBRegressor
Problem Statement
Avocados seem to be increasingly popular among millennials. It was observed that over 2.6 billion pounds of avocado were consumed in the United States alone in 2020, as opposed to only 436 million pounds consumed in the year 1985, as per Statista. Avocados are seen as a healthy option and are popular for being a good source of “good fats”. The fruit can be spread on toast, eaten raw, or even consumed in the form of a shake. Guacamole, which is a Mexican dip, is also made from avocados. Like most other products, the price of avocados fluctuates based on season, region and supply, which is why it would be beneficial to have a machine learning model to monitor and predict avocado prices.
The table below represents weekly 2018 retail scan data for National retail volume (units) and price. Retail scan data comes directly from retailers’ cash registers based on actual retail sales of Hass avocados.
This data was downloaded from the Hass Avocado Board website in May of 2018 & compiled into a single CSV.
Starting in 2013, the table below reflects an expanded, multi-outlet retail data set. Multi-outlet reporting includes an aggregation of the following channels: grocery, mass, club, drug, dollar and military. The Average Price (of avocados) in the table reflects a per unit (per avocado) cost, even when multiple units (avocados) are sold in bags.
The Product Lookup codes (PLU’s) in the table are only for Hass avocados. Other varieties of avocados (e.g. greenskins) are not included in this table.

                           Some relevant columns in the dataset:
Date - The date of the observation
Average Price - the average price of a single avocado
type - conventional or organic
year - the year
Region - the city or region of the observation
Total Volume - Total number of avocados sold
4046 - Total number of avocados with PLU 4046 sold
4225 - Total number of avocados with PLU 4225 sold
4770 - Total number of avocados with PLU 4770 sold

The Dataset contains  18249 Records and 14 Columns.
There are no null values.
All the columns have count equal to 18249. Mean and median have high difference except for Average price stating that data has high skewness present. There is high variance in all the columns except for Average price and year column. Difference between min, max and interquartile ranges is uneven hence there are a no. of outliers present in the data.


Methodology
Step 1 - Identify The Problem
Step 2 - Exploratory Data Analysis
Step 3 - Distribution
Step 4 - Feature Importance
Step 5 – Outliers
Step 6 - Missing data
Step 7 - Select the model
Step 8 - Evaluate the model
Step 9 - Conclusion!

How helpful for Business!?
More awareness of the sales and prices of avocados can benefit the vendors, producers, associations, and companies. Price prediction based on sales would be a good input in the market to determine shifting of produce to locations where the fruit is more in demand or even encouragement of consumption in places where demand is not up to the mark. The idea here is to predict future prices based on data collected of past prices based on geographical location, weather changes, and seasonal availability of avocados. 
![image](https://user-images.githubusercontent.com/108526449/182685694-5e861bd2-ad95-4c6c-afa8-e52cce2e19dd.png)

