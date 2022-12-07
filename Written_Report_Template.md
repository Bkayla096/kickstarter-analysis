# Kickstarting with Excel

## Overview of Project

### Purpose
This project is to figure whether is any correlation with the outcomes of Theater Kickstarters and the launch date as well as see about relation between the outcomes and the goals of the crowd funding campaign. 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
When Conducting my analysis on the outcomes in relation to the Launch date, I used a Pivot table to focus on specifically theater results. One of Challenges I faced was changing the rows to months instead of years to make the chart later more reader friendly. After some additional research, I was able to group the data into months instead all the individual dates. 

### Analysis of Outcomes Based on Goals
The analysis of the Goal related outcomes had me using a formula I had never used before. The COUNTIFS function was very helpful in this particular anylysis. It allowed me to set my parameters and conditions without a series of nested IF statements that allow for significant errors. Another issue I ran into with this data set came when it was time to calculate the percentages. This particulare date gave me some trouble and I thought I had data that was requiring I divide by 0, so I fixed that problem by using the IFERROR function. Although unneeded in this particular set, it was good practice for the future. 

### Challenges and Difficulties Encountered

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
- Based on the graph, named "Outcomes based on Launch Date", we can see that overall theater based crowd funding does well. The results of how many get successfully funded also appears to be related to the season with peak preformance being between April and August.

- What can you conclude about the Outcomes based on Goals?
- There is a similar success rate for projects that need less than $1000 and the much higher $35000-$39999. A conclusion that can be drawn from that information falsely equates the two data points. The graph doesn't show the total projects so it appears both goals are equally viable. 
- 
- What are some limitations of this dataset?
- I would posit that some the limitations of the data is that it doesen't also show the incentives that often come with kickstarter campaigns. The incentives available will affect how much people are willing to help fund a project. 

- What are some other possible tables and/or graphs that we could create?
A Stacked bar Graph be helpful for more visualization to compare how many successes in each our goal categories. A box plot may also be helpful to help with the previous concern mentioned with the potential outliers. 
