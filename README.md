# Kickstarting with Excel

## Overview of the Project
The provided analysis assesses 1,066 Kickstarter campaigns to help an up-and-coming playwright, Louise, to start her own successful crowd-sourcing campaign.
She is interested in ascertaining whether there are any useful insights to be gleaned from the statistics of previous successful and unsuccessful campaigns, in the hopes that she can raise enough money to fund her own campaign succesfully.
She should likely be looking for two things: advice on how/when to start her Kickstarter campaign, and whether she believes the campaign will likely be successful (e.g. should she begin looking for other sources of fundraising). 
This analysis should give her insights into when might be the most succesful launch date for her campaign, what her financial goal should be, and whether she is statistically likely to achieve that goal, based on other campaigns.

## Analysis and Challenges

The final analysis was performed to assess outcomes (success, failure, or cancellation) based on two factors: launch dates and initial goal. 
The analysis was performed using basic functions in Excel, including pivot tables and summary charts. 
The chart on Outcomes by Launch Date was filtered to make sure that only campaigns that fell into the theater category were added, and then was sorted based on the month the campaign was launched. One challenge that one might come across with this chart is how to sort by month. The table automatically sorts by year and quarter and those options must be removed. 
The chart on Outcomes by Goals was sorted by the sizes of the monetary goals, which were bucketed into roughly 12 categories (less than $1000 - over $50,000). 
In order to complete this, the `COUNTIFS` feature was used to count the number of campaigns that matched the category and outcome. 

## Results

### Theater Outcomes by Launch Date 

The below graph is the final result of the Theater Outcomes by Launch Date.

![Theater Outcomes by Launch](https://github.com/sophiehearn/kickstarter-analysis/blob/main/Images/Theater_Outcomes_vs_Launch.png?raw=true)

From this, Louise can conclude that more successful campaigns are launched in the summer, and very few successful campaigns are launch in the winter, particularly December.
Although this data is only correlative at this point, it would be sensible to surmise that she should try to begin her campaign as close to May as is feasible for her schedule.
She can also see that the majority of campaigns are successful. This should give her some hope for the outcome of her campaign. 

### Outcomes Based on Goals

The below graph shows the Outcomes Based on Goals.

![Outcomes Based on Goal](https://github.com/sophiehearn/kickstarter-analysis/blob/main/Images/Outcomes_vs_Goals.png?raw=true)

From this, Louise can see that the majority of campaigns under $15,000 do meet their goal, as well as campaigns from $35,000 - $45,000. Since Louise's goal is only $10,000, this is encouraging news. 
That being said, smaller goals than $10,000 are more likely to succeed, and because Kickstarter uses an all-or-nothing model, it may still be prudent to choose a smaller goal here on Kickstarter, if she believes she can meet some of the additional $10,000 needed elsewhere.

### Limitations of the Dataset

Although this analysis may help Louise understand some of the fundamental decisions of when and at what goal to launch her Kickstarter campaign, it does have its limitations. The existing dataset contains blurbs about the plays, whether they were "spotlighted" or chosen as staff picks, and how long the campaigns lasted.
A more sophisticated analysis of these data points might help Louise make additional decisions about how to prepare the campaign blurb and how long to run the campaign. It could also tell her whether there were any common characteristics of campaigns that were "spotlighted" or picked by staff, and whether either of these options helped garner more support.
Louise might then be able to cater her campaign to be a more likely candidate for a staff pick or spotlight.
The dataset itself does not provide information on how these campaigns were publicized beyond Kickstarter. Likely Louise will have to do some additional work outside of the platform to direct potential donors to the site - it could be useful to have information on whether donors were clicking through from emails, social media, QR codes, or finding it through the Kickstarter site itself.
With the data provided, it looks like Louise has a reasonable chance at success with her campaign, but she will likely need to put in more effort elsewhere to get the results she's hoping for.


