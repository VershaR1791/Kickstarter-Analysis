# Kickstarter with Excel
Performing analysis on Kickstarter data to uncover trends
## Overview of Project
Louie is a playwright who wants to start crowdfunding campaign to fund her latest play called ***Fever***. She has a budget of approximately $10,000. She wants to analyze the kickstarter website data which provides different datapoints for over 4100 campaigns.
### Purpose
The excel data available is large and difficult to skim through easily to help answer key questions for Louise. The right data needs to be extracted from the large dataset and analyzed.
The following analysis will help Louise analyze kickstarter website data to set her up for success. The analysis will -
- help understand how different campaigns fared in relation to the launch date and funding goals of the campaign
- provide a visual representation of the campaign outcomes vs launch date and funding goals
Louise can use the results of the analysis to plan the fundraising campaign for her play. The challenges of the data will also be laid out for Louise to ensure she is aware of the risks.
## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
This analysis will help Louise understand the outcome of fundraising campaigns basd on which month of the year the campaign was launched.The analysis filters all campaigns which fall under the subcategory *'theatre'* and have outcomes of either *'successful'*, *'failed'* or *'canceled'*. This is done through use of *pivot table* function. The table provides a count of the campaigns under each of the outcome category across all the months.
The pivot table data is also plotted into a *pivot chart* which helps visually understand the trends in outcomes based on the launch month. The line graph below provides a visual representation of number of campaigns for each outcome and the trend across each month. 

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/84694664/123526450-01520600-d6a6-11eb-884b-6beb59fd1b57.png)

### Analysis of Outcomes Based on Goals
This analysis summarizes the data based on goal range from less than 1000 to greater than 50,000, categorzing it into subdivisions of 5000. Using COUNTIFS function the number of *'successful'*, *'failed'* or *'canceled'* outcomes are found. The outcome data is also converted into percent of the total projects in that range.
The following line graph helps visualize the data of outcomes vs goal.

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/84694664/123526693-96a1ca00-d6a7-11eb-81db-802dc4077960.png)

### Challenges and Difficulties Encountered
This analysis does not take into account several other factors which may help Louise frame a better fundraising campaign. For instance the trends based on country will be helpful for Louise to plan based on where her play will be launched.Further, the analysis aggregates the goal amount of the campaigns irrespective of the currency of the country.
To create the outcomes based on goal table it was cumbersome to create it manually. Automating the process to get the results through code would have reduced time and possibility of human error.
It is challenging to help Louise determine how much she should expect as an average donation and during what time of the year. This would require in depth analysis of the successful plays and find the ones with a similar storyline. Understanding the trend in average donation will help her create a more specific fundraising campaign.
Additionally, this analysis does not help Louise plan for how long she should run her fundraising campaign.

## Results

### Conclusions about the Outcomes based on Launch Date
 - The most successful fundraising campaigns are in the month of May. Overall the sucessful campaigns in comparison to failed ones is over 50% for the months of May, June and July. There is a decreasing trend in successful campaigns from May to September with a slight increase again in October. This is possibly due to theater season which runs typically from September to May and the fundraising campaign is in preparation for that. The success rate rising again in October could be associated with last minute funraising campaigns for plays during Holiday season in November and December.
 - The number of campaigns failing each month is statistically insignificant. The failure rate in relation to the total number of the campaigns during the actual theatre season (September to May) is higher than during May to July.

Louise should launch her fundraising campaign in the month of May-July to see a higher success chance.

### Conclusions about the Outcomes based on Goals
- The highest successful campaign (76%) is when the campaign goal is lesser than 1000. The success rate decreases steeply as the campaign goal amount increases.
- However the success rate increases to 67% for goal amount of 35000 to 50000. On reviewing the actual data it can be seen that the dataset is very small (a total of 9 campaigns with 6 successful ones). This cannot be the only result to draw a conclusion.

Louise should keep her goal within 5000 to ensure a successful campaign.

### Limitations of this dataset
To create a successful fundraising campaign one must also be able to target the right donors. This dataset does not provide any details on the different type of donors and why they are donating. For Louise to narrow down the analysis it would have been helpful to have additional category of genre within the plays.

### Some other possible tables and/or graphs
Some additional analysis based on countries can help Louise review trends and make changes in her fundraising strategies, if required. Below are 2 graphs for US and Great Britain whose results are slighlty different especially for Great Britain. This can be easily extracted by adding a simple filter of *'Country'* to the pivot table in *'Analysis of Outcomes Based on Launch Date'*

![GB](https://user-images.githubusercontent.com/84694664/124361715-81282500-dbfe-11eb-98b8-06c04e37bc6e.png) 

![US](https://user-images.githubusercontent.com/84694664/124361717-838a7f00-dbfe-11eb-843a-ef893fe3bee5.png)
