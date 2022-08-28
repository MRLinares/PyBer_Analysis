# PyBer Analysis

## Overview

How ride-share data differs by city type and how it can be levaraged to make decisions.

### Data Needed
#### &emsp; For each city type:

&emsp; • Total number of rides 

&emsp; • Total number of drivers

&emsp; • Total fares  

&emsp; • Average fare per ride 

&emsp; • Average fare per driver 


### Resources:

Software: Python, Pandas, Matplotlib, Anaconda, and Jupyter Notebook.
Data: ride_data.csv, city_data.csv


## Results

The data represents totals for the year 2019, The image below is a view of the data by city type.  Calculating totals for drivers, fares, and rides for each city type allowed mw to find the average fare per ride and average fare per driver.  The pie charts visualize the percentage of total rides and fares each market represents.  While the total rides for the Suburban and Rural markets represent 26.8% and 5%, respectively (29.8% total), they represent 37.3% in their respective share of the revenue (30.5% and 6.8%, respectively).



#### &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;PyBer Summary Chart

&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;![PyBer_summary_df](https://user-images.githubusercontent.com/108758105/186734046-971f2788-9b68-4c35-9b34-67eb7474ede1.png)


![Fig6](https://user-images.githubusercontent.com/108758105/186740597-55414a7b-5767-48d2-999f-03b039b14327.png)
![Fig5](https://user-images.githubusercontent.com/108758105/186741336-01a886a4-8498-4201-9a61-a3265822d3f7.png)





Below is a view of weekly fare totals by city type which was accomplished by grouping the the total fare with respect to date and city type.

![PyBer_fare_summary](https://user-images.githubusercontent.com/108758105/186734074-4c34ec46-4891-4597-9c50-fd6e5ff40322.png)



## Summary

President's week is where every city type experiences a spike in revenue.  I recommend increasing fares this week or making more cars available to see whether we are at market equilibrium or we can further optimize profits.  

While the Rural market may represent a small fraction of total fares, the high fare per ride and even higher fare per driver numbers represent a promising opportunity.  Sending more drivers during these peak times may result in exponential profit growth.  The New Year, for example, brought the lowest revenue for the Suburban and Urban market, resources can be re-allocated for this week and placed into Rural markets to see if can boost revenue.  Or maybe this is an opportunity for higher-level fleet maintenance and safety inspections.

Easter seems like a possible growth opporunity for the Suburban market given the large spike leading up to it and after (many times a recess period for schools). Given the proximity to the Urban markets, resources can easily be sent across town to provide a possible boost in profits, especially given the higher fare per driver and ride.
