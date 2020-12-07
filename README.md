# Kickstarting with Excel

## Overview of Project
The client, Louise, has had her play 'Fever' come close to meeting a successful fundraising goal in a short amount of time.  She would like to know how this compares to other campaigns specifically as it relates to lauchdates and goal amounts. Using our Kickstarter dataset we will analyze.

### Purpose
The purpose of this project is to futher analyze our Kickstarter campaign data and help Louise visualize the outcomes of these campaigns based on launchdates and goal amounts. 

## Analysis and Challenges
To expand on our knowledge of our dataset we created a two new spreadsheets worksheets in our Kickstarter Campaign dataset (path/to/Kickstarter_Challenge1.xlxs) 
* Theater Outcomes by Date
Using a pivot table we sorted the data to show us only theatre campaigns and the months of the year where these campaigns were either successful, failed, or canceled. We then created a line chart to visualize these outcomes (path/to/Theater_Outcomes_vs_Launch.png) My main challenge in this section was having the date conversion section look appropriate to how the instructions intended. I had to adjust the pivot table and use references for quite some time before I was able to get it right. 
* Outcomes Based on Goals 
In this section of our analysis we narrowed down our data even more by focusing in on plays.  Using the the countif function we were able to visualize the percentage of successful, failed, and canceled plays based on the funding goal amount. I have to say that this section of the material was very difficult for me to master as I did not recall the countif function. After researching on the internet I was able to troubleshoot where I was going wrong and understand how it can be a very useful tool.

### Analysis of Outcomes Based on Launch Date
Using our visual tools, the pivot table and line chart (path/to/Theater_Outcomes_vs_Launch.png) the months April through August tend to see more successful outcomes. May and June see almost double the success than November, December, and January.  

### Analysis of Outcomes Based on Goals
Based on the data we have collected our 'Outcomes Based on Goals' chart tells us that most of the campaigns we have data on are have a greater percentage rate of sucess as their goal amounts decrease. Our failed campaigns seem to fall in the higher goal level amounts. The line chart that was created in this section displays successful patterns of campaigns and failures. (path/to/Outcomes_vs_Goals.png)

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
Louise, I would suggest that you begin your campaign in the month of May or June as the trend seems to show campaigns for theater doing well during that time of year.  I would avoid the month of December as my guess is that the many factors that go along with the holidays may interfere with having a successful campaign. 

- What can you conclude about the Outcomes based on Goals?
It appears to me that you will have a greater success rate if your funding goals are less than $5000.  This is not to say that other campaigns can not be successful but the data tells us that the percentages are better if you stay withing that range.  The data is also telling us that funding greater than $40000 very rarely succeeds.

- What are some limitations of this dataset?
The data does not tell us how much time was spent by the campaign organizers to reach their backers or any possible money they spent on advertising their campaigns. There is not a large sample size when it comes to plays with higher goals.  Is this because it isn't done or has the data not been gathered?

- What are some other possible tables and/or graphs that we could create?
* A chart showing the amount of backers needed to reach a goal with an average donation.
* Backers sorted by country to see if plays are more successful in certain parts of the world
