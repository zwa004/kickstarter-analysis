# Kickstarting with Excel

## Overview of Project
In this project we were presented a dataset of Kickstarter campaigns which inlcuded campaign goals, success/failure parameters, and other data. Using this information, we created a few brief analyses to help a user determine what time of year and what campaign amount would be most suitable to start a Kickstarter.

### Purpose
The purpose of this project is to visualize outcomes of kickstarter campaigns under specific conditions like pledged amount and categories. 

## Analysis and Challenges
The primary challenge of this dataset was the large number of values. Box and whisker plots caused hangs in Excel. C

### Analysis of Outcomes Based on Launch Date
The number of failed theater campaigns varied between roughly 55 and 35 campaigns while the variance of successful campaigns was larger, between approximately 110 in April and 40 in December. The number of canceled campaigns was relatively unchanged by the starting month. 

### Analysis of Outcomes Based on Goals
Generally, campaigns that had higher funding were successful while the opposite is true for failed campaigns. Rarely did failure/success rate cross 70%. 

### Challenges and Difficulties Encountered
Coding in "countifs" was a little tedious. Need to find a better way to do copy a formula and easily change arguments. 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
1. Over the course of any given year, successful and failed campaigns mirrored each other in all but one month. There were fewer failed campaigns in November than December vs more successful campaigns in November.

2. The most likely month for a successful campaign to start seems to be May while the most likely month for a failing campaign to start is Novemeber.

- What can you conclude about the Outcomes based on Goals?
The line graph suggests that a campaign is more likely to succeed than fail when approximately less than $15,000 or when $35,000 to $44,999 is pledged to any given play funded on Kickstarter.

- What are some limitations of this dataset?
Dataset limitations include backer population analysis (location, demographic, etc.) and backer pledged amount. How were the pledges distrubuted? Were there some wales who pledged 90% of a Kickstarter? Were they more communally funded? 

- What are some other possible tables and/or graphs that we could create?
We could create a success/failure bar graph filtered by country, % funded vs. pledged histogram, and/or table of successful campaigns based on category.  