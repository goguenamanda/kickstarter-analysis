# Analysis of Kickstarter Campaigns
In this project, we looked at a variety of kickstarter campaigns to determine the variables that were related to specific trends.
---
![outcomes_month](path/to/outcomes_month.png)
According to the data, the most successful campaigns occurred in the month of May
---
![category_outcomes](path/to/category_outcomes.png)
In the United States, theatre was the most successful category, while music had the highest success-to-failure ratio. 
---
![us_theatre_outcomes](path/to/us_theatre_outcomes.png)
At a closer glance, we can see that although theatre was the most successful category in the United states, it also had an almost equivalent rate of failure.
---
![gb_theatre_outcomes](path/to/gb_theatre_outcomes.png)
In Great Britain, theatre campaigns had a higher success-to-failure ratio than in the United States.
---
![theatre_subcategory_outcomes](path/to/theatre_subcategory_outcomes.png)
Within Great Britain, the 'plays' subcategory of theatre had by far the most success.
---
Based on all of the above information, I would recommend that Louise run a kickstarter campaign in the month of May. I'd suggest that she run her campaign in Great Britain in the 'play' subcategory in order to increase the likelihood of running a successful campaign. 
---
---
# Kickstarting with Excel

## Overview of Project

In this project, I created tables and charts that compared theatre campaign outcomes based on the launch date and campaign outcomes based on goals organized by a range of dollars. 


### Purpose
The purpose of this analysis was to compare Louis’s play *Fever* to other campaigns based on their launch date and fundraising goals. 


## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

For the Deliverable 1 assignment, I created a pivot table and chart for Outcomes Based on Launch Date. I created a pivot table in a new sheet using the data from the ‘Kickstarter’ timesheet. I placed ‘Outcomes’ in the columns section and ‘Data Created Conversion’ in the rows section. I also placed ‘Outcomes’ in the values section and ‘Parent Category’ and ‘Years’ in the filters section. I filtered the ‘Parent Category’ section to only show ‘theater’. I deselected ‘live’ under column labels and set it to descending order. Using this data, I created a line chart with markers. I titled the chart “Theater Outcomes Based on Launch Date”. 

![theatre_outcomes_vs_launch](path/to/theatre_outcomes_vs_launch.png)


### Analysis of Outcomes Based on Goals

For the Deliverable 2 assignment, I created a table and graph that evaluated outcomes based on goals for plays. To do this, I set a range of numbers in dollars under goals to classify and organize the data into groups. I then determined the number of successful, failed, and canceled play projects per group of goals. To do this, I used the ‘=COUNTIFS’ function. I filtered the data by including the appropriate range, appropriate outcomes category, and to only include ‘plays’. After this, I found the total number of projects in each range. I used the ‘=SUM’ function to add the successful, failed, and canceled outcomes from each goal range. Next, I found the percent of each outcome possibility by dividing the appropriate outcome category by the total projects in each goal range. 

From this data, I created a line chart. I used the percentage successful, canceled, and failed as my data, set the percentages on the y-axis, and set the goal range on the x-axis. I titled the chart “Outcomes Based on Goals (Plays)”. 

![outcomes_based_on_goals_plays](path/to/outcomes_based_on_goals_plays.png)



### Challenges and Difficulties Encountered

In the Deliverable 1 assignment, one of the challenges I faced was figuring out how to sort the row labels to only include months. I used the link below to troubleshoot the issue and was able to group the data to only show the months in the rows section. 

[Microsoft Support]( https://support.microsoft.com/en-us/office/group-or-ungroup-data-in-a-pivottable-c9d1ddd0-6580-47d1-82bc-c84a5a340725?ui=en-us&rs=en-us&ad=us)


In the Deliverable 2 assignment, one of the challenges that I faced was filtering the data to ensure that they fell within the proper range, were organized by outcomes, and only included plays. I used the link provided below to do this.

[Microsoft Support](https://support.microsoft.com/en-us/office/countifs-function-dda3dc6e-f74e-4aee-88bc-aa8c2a866842?ui=en-us&rs=en-us&ad=us)


## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

When it comes to the ‘Theater Outcomes by Launch Date’ data, I found that the highest rate of successful theater campaigns were launched in May, whereas the lowest rate of successful theater campaigns were launched in October. The highest rate of failed theater campaigns were launched in October, whereas the lowest rate of failed theater campaigns were launched in November. 


- What can you conclude about the Outcomes based on Goals?

In regards to the ‘Outcomes Based on Goals’ data, I found that there was a 0% success rate when the goal range was $45,000-$49,999. 


- What are some limitations of this dataset?

One of the limitations to the ‘Theater Outcomes by Launch Date’ dataset was that it was not filtered by the ‘plays’ subcategory. This would have given our data a more refined angle that aligns with our purpose for the analysis. Another limitation would be the type of graph used in the ‘Outcomes Based on Goals’ worksheet. The graph is not very legible.


- What are some other possible tables and/or graphs that we could create?

The graph used in ‘Outcomes Based on Goals’ worksheet would be improved by instead using a stacked column chart. I’ve included an image below of the improved chart. 

![2outcomes_based_on_goals_plays](path/to/outcomes_based_on_goals_plays.png)


