## Overview of our Kickstarter Analysis

### Purpose

After originally reviewing over 4000 Kickstarter campaigns to help Louise, a playwright, launch her own campaign; she fell just short of her goal. Louise has asked me to review the same Kickstarter data again to specifically determine how other campaigns fared based on launch dates and funding goals.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date:

In order to find relevant campaign results for Louise, I created a pivot table of campaigns and their outcomes based on the month they were launched. The data was filtered to include all years, but only campaigns in the Theatre parent category to better align with her own campaign.
With that, the following  line chart identified when the best months to launch a campaign are. 

![Outcome Based On Launch Date](https://github.com/jmmadson/kickstarter-analysis/blob/main/Resources/Theatre_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals:
Louise didn’t reach her crowdfunding goal, causing her to want to dig deeper into the trends of what goals are most likely to succeed. To analyze this, I took the campaign goals and put them into dollar ranges, adding a count of how many successful, failed and canceled campaigns fell into them. Using a filter to show only data for play campaigns the following line chart shows what goal amounts are most likely to be successful.  

![Outcomes vs Goals](https://github.com/jmmadson/kickstarter-analysis/blob/main/Resources/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered:
The biggest challenges for me was knowing what to look for. Data can be misleading, for example: 
While there looks to be a high percentage of successful campaigns in the $35,000 - $45,000 range - that was for a small set (nine) of Kickstarters, whereas the less than $5000 budget campaigns includes 720 Kickstarter campaigns. The smaller budget projects have more data points to make that a less risky choice, but if you are only looking at the chart you may make an incorrect assumption. 

![Campaigns by Goal Data](https://github.com/jmmadson/kickstarter-analysis/blob/main/Resources/Campaigns_By_Goal_Data.png) 

## Results
### Conclusions for Outcomes based on Launch Date:
After reviewing the data, I have determined that the most successful campaigns were launched in May, with June and July right behind them. We recommend launching the next campaign then. 

Additionally, October and December had almost the same amount of failed as successful campaigns and therefore are not recommended months to start a Kickstarter campaign. 

### Conclusions for the Outcomes based on Goals:
When the data was reviewed through the lens of goals vs outcomes, I found that campaigns with goals under $5,000 have the best chance of being successful and funded. 

### Dataset Limitations:
- The newest data included in this data set is from 2017, meaning it's over four years old. Newer data may provide much different results. 
- The amounts used in the data set were in both US Dollars & British Pounds which likely skewed some of the ranges.

### Additional analysis tables and charts:
- We could create the same graphs for the US only, where Louise’s play will take place to dial in the relevance of the results. 
- I would also create a table showing the difference between funded and goal amounts in failed campaigns compared to the same difference between funded and goal amounts in successful campaigns. That may help identify a goal to set so that at a minimum - even if her goal isn’t met the pledged amount covers her budget. 


