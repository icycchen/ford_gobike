# FordGoBike Dataset Exploration
## by Chuhang Chen


## Dataset

This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area.

There are 2.3 million bike sharing records in this dataset. The main features are duration, start time, and user types. Other features like start and end station location and customer information like gender and birth year are also included. A tiny part of the records are removed due to uncertainty of the validaty of these records.


## Summary of Findings

In the exploration, I found the distribution in duration time for trips centered around 10 minutes. The average duration for trips depends on a lot of elements, including month of a year, day of a week, hour of a day and user type. 

There is a strong relationship between the time and number of trips. Most of the trips taken during summer time from May to November. During the two major holidays, ThanksGiving and Christmas, the number of usage will decrease dramatically. Also, compared to weekends, the number of trips are much larger. The last, most of the trips take during rush hour. Similarly, the number of trips is related to user types, whether they own a membership or not.

The last thing I found is, there no strong relationship show between the user gender with the number of trips or duration.

## Key Insights for Presentation

For the presentaion, I focus on the both of the time of the trips taken and the user types for the trips. I start by introducing the bike_sharing service and followed by a pattern for the distribution of number of trips aloing the time. 
After that, I introduced the distribution duration time and how it compared to the number of trips in terms of the month, day of a week, hour of a day. From this comparison, I will introduce the difference brought by different usage of this service and different customer base for different time.
Last, I introduce the user types. Using pointplot and cluster bar chart to explain how the user types influence the usage times and usage duration.
