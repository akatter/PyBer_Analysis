# PyBer Analysis - Module 5 Challenge

## Overview of the Analysis

The purpose of this analysis is to create a summary of ride-sharing data by city type, divided by urban, suburban and rural data. The second objective of the analysis is to create a multiline graph of the total weekly fares by city type, which will illustrate the differences on how to analysis the different city types for ride share analysis.

## Resources Used
- Data Source: city_data.csv, ride_data.csv
- Software: Python 3.7.6, Visual Studio Code 1.63.2, Conda 4.11.0, Jupyter Notebook 6.4.6

## Results

The original analysis results can be found in the original PyCitySchools.ipnyb file. The corrected analysis with the results of Thomas High School's 9th Grade results omitted can be found in PyCitySchools_Challenge.ipnyb.

### Rideshare Summary Table by City Type

A summary dataframe was produced as a part of the analysis as shown below.

![PyBer Dataframe Summary](Analysis/PyBer_citytype.png)

One significant trend is that as cities get more dense from rural to urban, the trends are as expected. Urban centers have more rides, drivers available and total amount of fares. However, perhaps for competition, denser areas have lower average fares. Another important note is the comparison of average fare per ride and average fare per driver, where rural and suburban cities have a higher average per driver compared to the urban zone that has a higher average fare per ride. This may indicate how many drivers there are in each location that focus on long-distance or short-distance trips.

### Total Fares over Time by City Type

The second item produced for analysis was a multiline plot to illustrate the total fares between 2019-01-01 through 2019-04-28. These were binned into weekly data points and divided by city type.

![Multiline Plot of Total Fares by City Type, Weekly](Analysis/PyBer_faresummary.png)

The plot illustrates clearly as how a city is denser from rural to urban, the total fares recieved increase, with urban zones having the highest total fares. Overall the trends for all three types were similar with similar dips and highs. Although Urban and suburban zones had a more noticable dip at the beginning of the year compared to rural zones.



## Summary

Based on the results, there are some suggestions that can be made based on the table and graph provided. 

One suggestion based on the table is that there are more drivers then rides in the urban zone. This may be useful for times where ridesharing may peak, such as during holiday periods, however there may be more drivers then necessary in the regions. While it may not require changing, it could indicate the opposite approach in that more advertising can be made to recruit drivers in rural and suburban zones.

The second possible suggestion based on the chart is that the week of Feburary 24th showed a peak of all three city types. Investigating the dates of that, as well as other peaks and lows on the graph, can help ensure that future years can continue to capitalize on the peak or minimize each dip by preparing for it with methods to encourage travel during dips in rides or increase visibility of the app for peak days.

Another possible suggestion is comparing how the average fare per driver and average fare per ride change, as the per ride cost is greater in urban zones and lower in rural and suburban zones. This may indicate that Rural and suburban zones are lacking in drivers who wish to make shorter trips, and there are fewer drivers in urban zones willing to make longer trips compared to frequent smaller ones. Another focus of recruiting drivers could be used to address this imbalance, or a system to encourage customers to try using PyBer for shorter trips in suburban and rural zones rather then other transportation methods.

