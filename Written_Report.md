# Kickstarter Challenge 

## Overview of Project
Lauise is doing a project compaign and she wants to know how different campaigns fared in relation to their launch dates and outomes in theater data. 
Using the Kickstarter dataset she would like to observe the relationship betweeen outcomes and launch date. 

### Purpose
To access the relationship between outcomes and launch month from Theater data. 

## Analysis and Challenges
The data were analysed on excel using PivotTable and line chart was created for visualization.  

### Analysis of Outcomes Based on Launch Date 
Based on the analysis the number of Successful outcomes was higher than failed and canceled outcomes.  
May was the maximum (111) successful launched month in theater data. 


- What are two conclusions you can draw about the Outcomes based on Launch Date?

  Launch date/month has great impact on outcomes (successfu, failed or canceled)   
  Launching theater in Spring (April to June) can achieve a successful outcomes. 


### Analysis of Outcomes Based on Goals
Number Successful, Failed and Canceled were populated Using COUNTIFS function from Goal amount and Subcatagory, play columns. Then percentage of each outcome was
calculated. Finally, a line chart was created to visualize the relationship between the goal amount range and the percentage of successful, failed and canceled projects. 

### Challenges and Difficulties Encountered
In line chart the value of x-axis from 0 to 14 was supposed to be the goal amount ranges. This was one of the challanges to reflect the goal amout ranges in x-axis. 

## Results

The line char shows that percentage of successful was higher for goal ranges from less than 1,000 to 9,999 and from 35,000 to 44,999. 
The number of canceled projects was 0 in all goal amount ranges. Projects above 45,000 goal ranges were failed much. 

- What can you conclude about the Outcomes based on Goals?
Generally, campain at lower goal ranges (0 to 14,999) increase the percentage of successful rate.   

- What are some limitations of this dataset?
Data contain missing value; like blurb and the data don't represent all continenets. 
- What are some other possible tables and/or graphs that we could create?
Table and graphs can be created to see the relationship between outcomes and years. 
