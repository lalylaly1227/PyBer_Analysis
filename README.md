# PyBer_Challenge

## Overview of the analysis
The purpose of the new analysis was to investigate and provide visualization of the ride-sharing data, which was similar to Uber. We were given two datasets: 1. ride data with location, date and fare for every ride, and 2. city data which includes the type of city and the number of drivers. The objective was to compare number of rides and the fares in each city type: urban, suburban and rural. Additionally, we needed to create clear visualization using Matplotlib Library and provide recommendations to the CEO to address any inequalities among the city types.

### Resources
>> Data Sources: 
•	city_data.csv file
•	ride_data.cvs file

>> Software: Jupyter Notebook 6.4.8
•   Language Python 3/10.4 (PythonData)
•   Libraries: Pandas, Numpy, Matplotlib

## Results
Initially I gathered and group the data to get the total number of fares, rides and drivers. Then I group the totals by city type and got the averages for each.  Numbers and graphs can provide a lot of statistical data.  Data that can be used to make business decisions. It is clear that the urban cities have the largest revenue, but that does not necessarily point to being the most profitable or most efficient.  If you look closer at the average fare per ride, it is also clear that the rural cities make the most per fare.

 <img width="613" alt="Screen Shot 2022-06-14 at 4 19 00 PM" src="https://user-images.githubusercontent.com/105124485/173685204-b5032307-70cf-40f5-af89-7a13ee7a3db2.png">

![Overall Picture](https://user-images.githubusercontent.com/105124485/173685263-125c46e6-64e2-4aa0-9848-c8cb7a51be6b.jpg)

## Summary
Rural cities rides are more profitable. 

I would encourage the CEO to reduce the number of drivers in urban cities. You have a lot more drivers than rides provided (1,625 rides and 2,405 drivers); meaning that not all drivers are providing rides or collecting fares. Decreasing the number of drivers will increase the average fare per driver and bring the averages of the urban cities closer to the other city types.

We notice that the average fare cost in rural cities is also much higher; $55.49 compared to $16.57 in urban cities.  Maybe this is because in urban cities everything is closer together and the distances or time duration of the rides are shorter, thus producing lower fares. Those areas would also we great if we can define.

