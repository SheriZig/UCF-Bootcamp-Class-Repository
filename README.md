# Analysis of Kickstarter Campaigns

## Overview of Project
After reaching the Kickstarter fundraising goal for her play ‘Fever’, Louise is interested in the outcomes for other campaigns based on their launch dates and fundraising goals. 
### Purpose
The purpose of this analysis is to determine the various outcomes (successful, failed, canceled) based on fundraising goal and when the campaign was launched. The analysis will provide Louise with reality-based research to assist her in the decision-making process for future projects that require fundraising. 
## Analysis and Challenges
The analysis was conducted on a database that consisted of 4113 datapoints that included a wide variety of categories and subcategories. For the purposes of this analysis, the dataset was filtered to only include the ‘Theater’ category and ‘Plays’ subcategory. The date range of the data was between 2010 and 2017. 

### Analysis of Outcomes Based on Launch Date

![image](https://user-images.githubusercontent.com/88912539/131234260-063b2e8c-b7cd-4ae3-b169-fce7c9f14bba.png)

The analysis revealed that between 49% and 67% of the campaigns analyzed were successful. December had the lowest percent with 49% or 37 successful campaigns out of 75 launched campaigns. May had the highest percent with 67% or 111 successful campaigns out of 166 launched campaigns.   

The analysis revealed that between 31% and 47% of campaigns analyzed failed. May had the lowest number of failed campaigns with 31% or 52 out of 166 campaigns. The highest percent of failed campaigns were in December with 47% or 35 out of 75 campaigns. 
### Analysis of Outcomes Based on Goals

![image](https://user-images.githubusercontent.com/88912539/131234257-98643011-5388-4e09-aa3d-ec63b31c471a.png)

The majority of successful Kickstarter campaigns had a fundraising goal of less than $5,000 with greater than 70% success rate. Fundraising goals between $35,000 to $45,000 had some success with 67% of the campaigns successful. However, it should be noted that there were a small number of campaigns of this size. There were 9 campaigns and 6 were successful. 
### Challenges encountered during analysis
When defining the criteria for the =CountIF function, if the analyst does not use <= and >= the data returned will not be correct. Also, a challenge could be created if all the datapoints are not accounted for in the number of successful, failed, canceled and total projects calculations.
## Results 
### Conclusions for outcomes based on Launch Date
The best time to launch a campaign is in the Spring. There is a steady increase in successful campaigns beginning in March and steadily increasing with the peak in May. Notice that the successful campaigns are more than double the number of failed campaigns. The number of successful campaigns decreases for the rest of the year with a small uptick in October. 
I would conclude that the launch date has an impact on the outcome of the campaign. 
### Conclusions for outcomes based on fundraising goal
When setting the fundraising goal for a Kickstarter campaign, the chances of a successful campaign increase for goals below $5,000. The trend for successful campaigns remains above the number of fail campaigns up to $20,000. Above $20,000 more campaigns fail than succeed with the small exceptions noted in the $35,000 to $45,000 range. 
### Limitations of the supplied dataset
The dataset lacked any geographic information which can affect the fundraising efforts. Geographic locations can play a role in the spending habits of backers. 
The most current data is 4 years old. It is unknown what impact current data would have on the conclusions drawn based on the supplied dataset. The additional data would be helpful in determining if economic conditions for the timeframe would reveal any significant changes in the analysis.
### Additional tables and/or graphs that may be suitable
A year over year analysis would be beneficial.  

An analysis of the whole dataset instead of a subset of the records for only theater/plays would be helpful to determine how Kickstarter campaigns perform overall. 

An analysis of outcomes for geographic locations would provide a valuable datapoint. 
