# PyBer_Analysis

## Overview 
During the course of this challenge, we assisted the CEO of PyBer - a ride sharing service. The goal was to help the CEO understand the following: 
* Number of rides taken 
* Total available rides 
* Price fares based on location (urban, suburban, rural). 
The scope of the work included: Python, Pandas, and Matplotlib. Utlizing these tools, I was able to create a summary DataFrame and a multi-line graph of the total fares for each city type.

## Learning Objective
The purpose of this challenge was to showcase and create the following:
1. Create an array of charts including: Line, Bar, Scatter, Bubble, Pie, and box-and-whisker plots. *I utlized Matplotlib for this.* 
2. Adding and Modifying features of the Matplotlib charts. 
3. Adding error bars to the line and bar charts. 
4. Identifying the mean, median, mode. *I utlized Pandas to determine this.*

## Results

### Summary DataFrame 
![image](https://user-images.githubusercontent.com/102767530/179123190-752a350b-fde4-4baa-8f9b-f58993399cbd.png)
1. As we review the summary there is a notable spike of usage from one environment - being Urban cities. The urban data showccased the most total drivers than total rides. This may have caused the the reduced impact due to supply and demand of drivers vs. riders. From the data, we can also note that Urban average Fare per Ride is notably reduced than Suburban and Rural drivers. 
2. The Rural city data showed the opposite of the Urban Cities data. The rural city had fewer total drivers than total rides, which allowed to have the average fare per driver to be the highest. 

### Total Fare by City Type 
![image](https://user-images.githubusercontent.com/102767530/179123959-dc9217aa-a24b-4843-b9d7-e3734dace862.png)

The above data is a visual representation of the DataFrame. It showcases the trends for each city as well. 

### Trends
1. All of the 3 different environments had a spike near end of February. After the peak, the Urban city data showcased a persistant of a high until April. However, for the other cities - it was a steady decline after March. 

## Summary + Recommendations
* The results of the summary reflected that the Urban City - though more compact, had the lowest average fare per ride and Rural Cities, since they have more land mass and locations are farther to reach, had the highest average fare per ride. 
**Recommendation - PBber should inlcude mileage in their fares - similiar to NYC Taxi Cabs. This will allow us to collect more data and analyze more insights**

* Review the data, since there was far less total drivers than total riders in the Urban city scape - it is implied the drivers didn't have much work to support their job. 
**Recommendation - PyBer to amplify their marketing tactics to spread awareness of their business. This will attract more consumers.**
