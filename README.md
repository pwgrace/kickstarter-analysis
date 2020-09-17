# kickstarter-analysis
Performing analysis on kickstarter data to uncover trends

## Overview of Project

The purpose of this project is to analyze Kickstarter Campaign data to gather insights into theater/plays campaign outcomes based on their launch date and funding goals. 

## Analysis and Challenges

### Outcomes Based on Launch Date

To visualize theater outcomes based on launch date, a pivot table was created such that the rows indicated month launched and the columns indicated the outcome as “successful”, “failed”, or “canceled”. The outcomes were filtered to include only “theater” categories, and an optional year filter was created as well. We ran into a challenge when the dates were individual dates in the original data set but it was solved by grouping by months rather than days in the pivot table.

![](Data_Bootcamp/Module 1/Launch Date Screenshot.png)

### Outcomes Based on Goals

A table was created to count the number of successful, failed, and canceled projects so that the percentages of each outcome could be determined. There were no issues encountered. An issue would have arisen if there had been typos in the  outcome categories. The data would have required prior cleaning.

## Results

### Outcomes Based on Launch Date

It is recommended from the analysis of outcomes based on launch date that the launch date be targeted for May or June. It is also recommended that a launch date in the time period of November, December, and January be avoided. 

### Outcomes Based on Goals

It is recommended from the analysis of outcomes based on the goal that the goal should be less than $5,000 to maximize success. 

### Limitations and future recommendation

The data is missing the last 3 years of campaigns, it was taken in early 2017. It is recommended that updated tables be generated including the more recent data. It would also be beneficial to look at outcomes based on length of campaign and campaigns close to meeting their goal. 
