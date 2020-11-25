# Air-Quality-Index-Prediction

#### • A Machine Learning Web App created with Tkinter.
#### • Do ⭐ the repository if it helped you in anyway.
 
 
 ![AQI](https://user-images.githubusercontent.com/65092456/100265844-dd470e80-2f76-11eb-95b0-04cce694df12.JPG)
 
 ## Overview
 
Think of the AQI as a yardstick that runs from 0 to 500. 
The higher the AQI value, the greater the level of air pollution and the greater the health concern. 
For example, an AQI value of 50 or below represents good air quality, while an AQI value over 300 represents hazardous air quality.

I have built this app which takes various input data in regard to the temperature of a given area and returns the quality index of 
the air or we can say the health of the air.


## Data source description

I have scrapped the data using BeautifulSoup library. The data is a daily data since January 2015 till August 2020, 
and it is the data belonging to four metro cities namely Mumbai, Bangalore, Delhi and Kolkata.

After cleaning the scrapped data, I have built the model with 3695 data points and the attributes are:

•	Average temperature

•	Maximum temperature

•	Minimum temperature

•	Average relative humidity

•	Total rainfall

•	Average visibility

•	Average wind speed

•	Maximum sustained windspeed


## Approach

After scrapping the data, I have applied pre-processing and EDA on data. 
And then have used regression algorithm for model building purpose.

To fit the data, the regression models that we wish to compare are Linear Regression and Random Forest Regressor. 
I have split the entire data frame into 80% training set and 20% test set, where I hold out the test set for final model evaluation.

The best score I got for the model was using Random forest regressor and using that model I have further deployed the project.
Later, I have built a small app using Tkinter as shown in the preview above.





