# Kickstarter with Excel
Performing analysis on Kickstarter data to uncover trends
## Overview of Project
Louie is a playwright who wants to start crowdfunding campaign to fund her latest play called ***Fever***. She has a budget of approximately $10,000. She wants to analyze the kickstarter website data which provides different datapoints for over 3800 campaigns.
### Purpose
The excel data available is large and difficult to skim through easily to help answer key questions for Louise. The right data needs to be extracted from the large dataset and analyzed.
The following analysis will help Louise analyze kickstarter website data to set her up for success. The analysis will -
- help understand how different campaigns fared in relation to the launch date and funding goals of the campaign
- provide a visual representation of the campaign outcomes vs launch date and fundinf goals
Louise can use the results of the analysis to plan the fundraising campaign for her play. The challenges of the data will also be laid out for Louise to ensure she is aware of the risks.
## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
This analysis filters all campaigns which fall under the subcategory *'theatre'* and have outcomes of either *'succesful'*, *'failed'* or *'canceled'*. This is done through use of *pivot table* function. The table provides a count of the campaigns under each of the outcome category across all the months.
The pivot table data is also plotted into a *pivot chart* which helps visually understand the trends in outcomes based on the launch month.

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/84694664/123526450-01520600-d6a6-11eb-884b-6beb59fd1b57.png)

### Analysis of Outcomes Based on Goals
This analysis summarizes the data based on goal range from less than 1000 to greater than 50,000, categorzing it into subdivisions of 5000. Using COUNTIFS function the number of *'succesful'*, *'failed'* or *'canceled'* outcomes are found. The outcome data is also converted into percent of the total projects in that range.
The following line graph helps visualize the data of outcomes vs goal.

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/84694664/123526693-96a1ca00-d6a7-11eb-81db-802dc4077960.png)

### Challenges and Difficulties Encountered

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

- What can you conclude about the Outcomes based on Goals?

- What are some limitations of this dataset?

- What are some other possible tables and/or graphs that we could create?
