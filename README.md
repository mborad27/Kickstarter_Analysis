# Kickstarter Campaigns: An Analysis via Launch Dates and Funding Goals
## Overview of Project
Louise has sent us a Kickstarter Excel Data File with a plethora of information regarding campaigns. She is curious to know how different campaigns performed based on their launch dates and funding goals. 
### Purpose
This report was created to discover information about the outcomes of theater campaigns based on their launch dates as well as play outcomes based on their initial funding goals.
## Analysis and Challenges
### Analysis of Outcomes Based on Launch Date
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/92230478/137996639-627871b7-6c80-484c-814f-93bb6e3f6404.png)


The data we pulled to design this chart is filtered with the parent category “Theater” and the launch dates as only the month (not year). The chart displays the number of “successful”, “failed”, and “canceled” campaigns for each month. The launch date years were extracted using the `` YEAR()`` function. We are able to see trends in our data over time with this line chart.
### Analysis of Outcomes Based on Goals
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/92230478/137996624-1face8a7-09d2-4afa-9356-705c8844b0d8.png)

The data that we arranged for this chart consists of the funding goal ($) and the percentage of “successful”, “failed”, and “canceled” campaigns for the category of “Plays”. This data was retrieved using the ``COUNTIFS()`` function as well as the ``SUM()`` function. This chart shows us trends over funding goals.
### Challenges and Difficulties Encountered
A challenge that could possibly be discovered for Theater Outcomes based on Launch would be on the pivot table with the Row “Years” not showing the months. This can be remediated by grouping certain items in that box. For Outcomes Based on Goals, a challenge that I encountered was also in the pivot table where it would arrange the x-axis (Goal $) in alphabetical order. This took the goal values out of order and my chart looked very confusing. To correct that, I selected manual sort and rearranged the goal values in chronological order. 
## Results
### Outcomes based on Launch Date
The month of May had the most successful Theater campaigns, followed by June and July. However, May was also the month with the highest number of failed campaigns. In addition, October had no campaigns being canceled. May is the most popular month for theater campaigns to open as it has the highest total and December is the least popular month to launch.
### Outcomes based on Goals
The play campaigns with a funding goal of Less than $1000 had the highest percentage of success, followed by the goal of $1000 to $4999. The campaigns with a funding goal of $45000 to $49999 had the highest failure percentage followed by the Greater than $50000. The lower funding plays are performing better than the ones with a larger funding.
### Limitations
For both theater outcomes vs. launch date and play outcomes vs. funding, there were some campaigns that were currently "live" so we were missing information from those. The data that we having is only applicable to campaigns that have already happened and ended.
### Recommendations
Another graph that can be utilized to display this information would be a clustered column. This type of chart will have a side-by-side comparison for the amount of "successful", "failed", and "canceled" campaigns with the x-axis having either date or funding goal and the y-axis being percentage or count. For Outcomes based on Goals we can also use a Box-and-whisker plot for each category: "successful", "failed", and "canceled". It would assist us in knowing what the mean, median, and quartiles are in the funding goals for each category. In addition, since we've already looked at theater outcomes vs. launch dates and play outcomes vs. funding goal, we can create a new table to look at the theater campaign's launch dates vs. funding goals as well as the play campaign's launch dates vs. funding goals. With this new information, we will have a clearer understanding to support our report to Louise. 

