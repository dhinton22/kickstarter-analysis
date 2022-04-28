# Kickstarting with Excel


## Overview of Project
The purpose of this analysis is to help Louise understand how different campaigns fared in relation to their launch dates and their fundings goals. 

## Project
Louise’s play Fever came close to its fundraising goal in a short amount of time. Now, she wants to know how different campaigns fared in relation to their launch dates and their funding goals. Using the Kickstarter dataset, I visualized campaign outcomes based on their launch dates and their funding goals. 

## Analysis and Challenges
I performed my analysis of all campaigns with subcategory "plays" to show how they fared in comparison to Louise's play "Fever". Using a pivot table, I compared all theater plays worldwide over a 9 year span 2009-2017. I determined that the most successful plays were launched between April and September with May being the peak month to launch each year. From this pivot table, I created a line graph 'Theater Outcomes Based on Launch Date' that clearly shows the increase of successful plays between April and May, while also displaying the incremental decrease in successful plays between May and September. For further analysis, I created a line chart that shows the outcomes based on goals. This chart outlines the goal amount range and the percentage of successful, failed, and canceled projects. I determined that roughly 96% of campaign launches failed that had goals greater than $20000. I struggled with calculating the percetage of total failed projects greater than $20000.


### Analysis of Outcomes Based on Launch Date
The month that launched the most successful Kickstarter for theater was May. However May, June, July, August, and October all had roughly the same number of failed campaigns launched. 

### Analysis of Outcomes Based on Goals
There were 1047 theater plays in the kickstarter project. Of the total plays, 76% of the successful theater plays have goals less than $1000 and 73% had goals between $1000 and $4999. However, the success percentage decreases drastically while the failed percentage increases with the goal amount greater than $19999. Therefore, only 6% of the total theater plays with goal amounts greater than $20000 were successful, while 94% of them failed. 

### Challenges and Difficulties Encountered
I was challenged by the countifs() formulas and providing an overview analysis of the dataset. 


## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
In conclustion, May appears to be the best opportunity to launch a successful theater play and reach funding goals. I would also avoid launching a theater play between September and November because the fail rate increases drastically.

- What can you conclude about the Outcomes based on Goals?
In conclusion, I would recommend to set goal amounts below $20000 for a higher success rate of the theater plays. 

- What are some limitations of this dataset?
One of the limitations I noticed is that the dataset is from projects spanned over 9 year period from 2009-2017. Instead, I would limit this data to 5 years to avoid convoluting the data.

- What are some other possible tables and/or graphs that we could create?
We could create a line graph that shows the amount pledged to projects over a calendar year with the pledged on the x-axis and months Jan-Dec on the y-axis. I would recommend this chart to analyze the amount pledged to each project during the year. This will assist with projecting future pledged amounts possible for a project. 

We could create a pie chart based on outcomes that shows the overall balance of successful, failed, and canceled outcomes. This will show the overall percentage of successful outcomes, failed outcomes, and canceled outcomes. 