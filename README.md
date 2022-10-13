# An Analysis of Kickstarter Campaigns
Analysing Kickstarter campaigns' outcomes based on their goals and launch date in the US, particularly plays
## Visuals of Campaign Outcomes in the US
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/113739316/195683736-bfcccb13-bbdd-4a4b-a109-8c786e72aa3c.png)In the above line graph, you can see that campaigns with higher goals had a greater fail rate as opposed to campaigns with lower goals. 
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/113739316/195685531-2438837a-43b9-49fe-ba8f-d76ec4cd9163.png) In the above line graph, we are analysising the outcome of theatre based on launch date by month. We see a peak of success during the month of May. We can also see more theatre campaigns were successful than not throughout the year.
A challenge during the analysis for me was using the =countifs() formula to capture plays within goal ranges. I was able to apply the function to goals less than 1000 and greater than 5000, but then I got stuck applying the function to the ranges. Once I was able to apply the function, finding the sum and percentage was rather easy.
### Results
Two conclusion I can draw from the Theatre Outcomes by Launch Date are
- There are more successful threate campaigns than those that failed
- Theatre Campaigns during the month of May were the most successful overall
From the Outcome Based on Goals, we can conclude that if play campaigns set a high goal it is more liekly to fail.
Some limitations within the dataset is determining what would be the cause of a canceled campaign. In our analysis, we can see that theatre had canceled campaigns while plays did not. So we are unable to determine if the cause of canceled campaigns is impacted by the goal set. 
Another graph we could have used to analyze are data is a stacked bar graph. A stacked bar graph would give us an easier and quicker view of which theatre campaigns did better in a given month. 
