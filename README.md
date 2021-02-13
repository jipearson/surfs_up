# surfs_up

## Overview of Project
- While on Vacation in Hawaii last year I found a new passion for surfing. I have come up with a plan to open a Surf n' Shake shop that will allow me to move there. After engaging a potential investor, surfer W. Avy, he has one concern; the weather. In order to solidify his investment, W. Avy wants us to run some analytics on a weather dataset he has from the beautiful island of Oahu. Through our analysis we provide Mr. Avy with an abundance of information (highlighted below).
  - Precipitation summary statistics
  - The number of stations being used to produce the data 
  - The most acitve stations 
  - The low, high, and average temperatures. 
- To make the information easier to access we push our results to the web using flask. 
- Finally W. Avey wants us to produce summary temperature data for the months of June and December in Oahu, in order to determine if the surf and ice cream shop business is sustainable year-round.

## Analysis Results
### June temperature statistical summary.
![](images/june_stats.PNG) 
### December temperature statistical summary.
![](images/dec_stats.PNG) 

### Total Rides
From our analysis set we find that there were 2,375 total rides completed. 
- 1,625 were in urban areas 
- 625 were in suburban areas
- 125 were in rural areas<br/>

The Chart below shows the percent of the total number of rides that each city type represents.
![](analysis/Total_Rides_pc.png) 
<br/>

### Total/Average Fares
The fare total generated from all rides was $63,538.68
- $39,854.38 were in urban areas for an average of $24.53 per ride
- $19,356.33 were in suburban areas for an average of $30.97 per ride
- $4,327.97 were in rural areas for an average of $34.62 per ride.<br/>

The Chart below shows the percent of the total number of rides that each city type represents.
![](analysis/Total_Fares_pc.png) 
<br/>

### Driver Totals and Fares
After summarizing the data we find that there were 2,973 total drivers accross all city types. 
- 2,405 were in urban areas and generated fares of $16.57 on average.
- 490 were in suburban areas and generated fares of $39.50 on average.
- 78 were in rural areas and generated fares of $55.48 on average.<br/> 

The Chart below shows the percent of the total number of drivers for each city type.
![](analysis/Total_Drivers_pc.png) 
<br/>

### Fare Trend (January - April)
The graph below shows the weekly fares totals by city type during the first 4 months of 2019. 
![](analysis/Pyber_fare_summary.png) 
<br/>

## Summary and Recommendations
After reviewing the analysis results we have found several trends. 
- Although only 5.3% of rides are in rural areas these rides account for nearly 7% of total fares generated. The average rural fare is over $10 higher than in urban ares, simply put riders in rural areas are having to travel further and pay more to get to their destinations.. The high fare does not correlate to high driver counts as only 2.6% of drivers are in rural areas. 
- While 86% of rides and 63% of fares come from urban areas nearly 81% of drivers can be found in urban areas. Because of the high supply of drivers given the demand the average fare per driver is only 42% of those in suburban areas and  less than 30% of those in rural areas. To find a better equilibrium we should do one of, or a combination of the following. 
<br/>
Based on these trends we suggest the following. (2 and 3 can work independently or in tandem) <br/>
1. Increase in rural driver pay to incentivize more drivers, this will help us capitalize on high fares. <br/>
2. Decrease the fare for the rider to increase the demand and meet the driver supply. <br/>
3. Slightly decrease the portion of the fare that goes to the driver. This will decrease the driver supply but will not impact the demand for rides, the company's per ride margins will increase. 
