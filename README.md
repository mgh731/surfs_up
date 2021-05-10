# Overview of the statistical analysis

The purpose of this analysis is to determine determine based on the statistical tables if the weather data shows that the surf and ice cream shop will be sustainable in June and December. Assuming that the June data represents the high point of summer and the December represents the high point of winter, we wanted to see if the temperatures and precipation would be favorable for business. 

## Method

We used the following to display these tables: sqlalchemy, pandas dataframes, python date time module, and the describe() function. 

We first filtered the data for the month's that we were interested in, then converted this temperature data to a list and imported into a Pandas DataFrame. This allowed us to use the describe function to see the statistical analysis. 

# Results

Below are the results for June and December temperatures. 

![June_Temps](/June_Temps.PNG)



![December_Temps](/December_Temps.PNG)


As you can tell, the numbers for both June and December do not vary too much despite the significantly different time of year that they are in. Also the Standard Deviation and percentiles are similar in the two tables signifying that there is not a big difference in temperatures between these two months. 

The one outstanding difference is the minimum temperature for December being 56 degrees vs the minimum temperature in June being 64 degrees. Assuming that 25% of the values for December fall under 69 degrees per the table, we are likely to expect more days where the temperature is this low in December. 

# Summary
Because these tables show a slight but not entirely dramatic difference between the temperature between June and December months it is not likely this should stop the ice cream and surf shop. 
