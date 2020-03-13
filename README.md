# An Analysis of Kickstarter Campaigns
Performing analysis on Kickstarter data to uncover trends within crowdfunding campaigns. 

## Overview of Findings:
- Campaigns for Plays were more successful than other theater types. 
- The more successful theater campaigns have launch dates within the month of May.
- Based on the UK's musical theater market, the aim for a campaign goal should be close to the average of 4,000 euros.

## Reccomendation(s): 
- Launching a campaign in the month of May with a goal of approximately $4,5000 would lead to a successful Kickstarter.

### Challenge 

_Observations:_

- Outcomes Based on Goals: 
  - Highest success rate for smaller Plays are for pledge goals of either less than $1,000, or between $1,000 and $4,999. The second highest success rate applies more to the rare Play Kickstarters that require a significant amount of funding, which goals are between $35,000 and $44,999. 
  - Each chart line reflects each other due to each data set being part of the same whole. Could possibly hide the fail percentage data line from the chart and be able to interpret and focus on the success data more clearly.
  - The $15,000 to $20,000 goal has a 50% chance of succeeding or failing, so it seems to create a line of a suggested maximum of expected risk one should consider when creating goal within that range. 
  
  ![Outcomes Based on Goals](https://github.com/kgtillis/kickstarter-analysis/blob/master/Challenge_Outcomes%20Based%20on%20Goal.png)
  
- Outcomes Based on Launch Date:
  - It appears that the most successful theater campaigns have a launch date for May out of all other months, and the success rate declines rapidly towards over the summer months. 
   - Appears to be a limitation to the success rate, for a peak amount of Failed launches also have dates in May and amount remains somewhat consistent on to August, displaying a consistent failure rate for some Kickstarters. 
   
   ![Outcomes Based on Launch Date](https://github.com/kgtillis/kickstarter-analysis/blob/master/Challenge_Outcomes%20Based%20on%20Launch%20Date.png)

- Combined:
  - Based on both sheets, since there were 0 cancelled plays according to Goals, the data displayed within Launch Date outcomes shows that it was either Musical or Spaces that were cancelled more often for theater based Kickstarters. 
  - No Kickstarters were cancelled for the month of October, it was either a success or failure. 

__Conclusion:__ 
  What can be deduced from this analysis is that shorter campaigns (based upon smaller pledge goals of $5,000 and under) are more likely to be successful if started in the month of May. The next successful month would be February, and the last chance would be in October. 

_Limitations of the data set and suggestions for additional tables or graphs:_
- Unable to clearly determine how the length of a campaign contributes to its success or failure for the specified pulled data only establishes the successful launch start dates and goal ranges, and the charts do not specifically display the amount of days between start and finish for the successful campaigns. Would need to perform a function to calculate the length of days for the successful campaigns and confirm an average and minimum amount of days required for theater/play Kickstarters. 
- For the theater Outcomes Based on Launch Date, even though the chart shows the more popular months, it would help to add additional charts that further narrow down the peaks and canyons of the graph to see what type of theater production was the most successful for that month, and which of those that tended to fail. 
- Add an additional chart to display the decline in success from May to September in order to determine any trends in production types, in addition to another chart or table to display what type of theater productions have a consistent fail rate May through August range as well. 
- Would further investigate the deviations of the differences between success and failure rates and be able to supply a solid percentage of how much more successful a Kickstarter would be above other types. 
- Looking further into the successful Goal Outcome ranges for past Play Kickstarters and comparing their launch dates outcomes to see if both the goal amount correlates to the peak times of success. (i.e. Maybe backers happen to have more money to pledge at certain times of the year?) 
- Based on current Goal Outcomes, find the standard deviations of the success and fail ranges in order to remove the outliers within the data and provide a cleaner estimate of rates, since one failed Play Kickstarter with a high goal ($45,000 - $49,999) shouldn’t discredit the other successful goals that had amounts greater than it ($50,000 and above).
