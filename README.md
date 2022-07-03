# Kickstarting with Excel
## Overview of Project
### Purpose
As Louise’s play Fever comes close to the fundraising goal, she still aims to further review how successful other categories were by leveraging the same set of data. This project focuses on showcase to Louise how the outcomes of Theater fared by launched date and how Plays performed in relation to the goals
## Analysis and Challenges
### Analysis of Outcomes Based on Launch Date
I first broke down the theater shows by outcomes of successful, failed and canceled by launch date from January to December since the year of 2009. For example, 100 projects were successful in June during the year of 2009 to 2017, while 49 were failed and 4 were canceled. I have checked to make sure the total number of theater shows are 1369. Also, there were no cancelations in October. Furthermore, a line chart can better explain movements of Theater outcomes throughout the years. Usually, the theater shows had a peak season in May and June. Meanwhile, the number of failed shows had a correlated trend with the successful outcomes. 

![image](https://user-images.githubusercontent.com/107721712/177054508-03daed34-4b62-4d7f-80d8-3ca6431bd031.png)
### Analysis of Outcomes Based on Goals
 I also analyze outcomes of Plays based on goals. I break down the goals with 12 ranges from “less than 1000” to “5000 and more”. Then I separate the outcome types the same as the first analysis, including Successful, Failed, and Cancelled. To understand the relation of the outcomes to total projects, I further calculate the percentage of each type of outcomes to the total projects. As a result, a line chart can indicate the trend of outcomes by the goals. This chart shows that successful and failed goals had opposite trend. Plays didn’t have canceled projects at all based on the goal range. 
![image](https://user-images.githubusercontent.com/107721712/177053470-569449f2-e1d4-4162-924c-b2e5ab27aad6.png)
### Challenges and Difficulties Encountered
A challenge encountered in the “Theater Outcomes by Launch Date” was to review the completeness of data selected for the analysis. Any missed data can result in different implications on the theater outcomes. I overcame this challenge by confirming the data range of the pivot table as well as manually reconciling the total projects against the total of plays in the  “Kickstarters” worksheet.  Another challenge encountered was to replicate Countifs function among each type of outcomes and each range of goals to analyze “Outcomes Based on Goals”. I created the first Countifs function across the row of the range “less than 1000”. Then I adjusted the range criteria on the “Number Successful” column. Once I obtained the number of succsefull outcomes, I replicated the functions to other outcomes, and then changed the criteria from “successful” to other outcomes. 
## Results
### Outcomes Based on Launch Date 
Theaters had better outcomes with launch date during May and Jun. Meanwhile, failed outcomes had a similar movement as successful outcomes. Cancellations were stable with even no cancellation in Octobers. Therefore, Lucy should invest more resources during the busy seasons to better manage the failed projects. 
### Outcomes Based on Goals
Plays didn’t have any cancellations based on the goals, so percentage successful and percentage failed were always added up to 100%. The percentage successful generally increased as the goals increased, except for the goals from $35,000 to $44,999. Lucy should investigate on what were the reasons dragging down the outcomes for these two ranges. 
### Limitations and Recommendations
Theater outcomes can not implicate the movements across years as each year may show different trends. I recommend filtering some years and comparing the outcomes in these years. 
Regarding the plays outcomes based on goals. the sum of “Total Projects” was not equal to the total projects under “plays” sub-category. It was due to live outcomes missed in the analysis. I recommend creating another pivot table to filter plays, and outcomes as rows, then count the outcomes as values. The pivot table can help to check the sum of successful and failed outcomes is equal to the total projects in the “Outcomes Based on Goals”. 

![image](https://user-images.githubusercontent.com/107721712/177053763-1c6cc0e2-6c10-4ecf-83de-5d1354f58123.png)
