# kickstarter_excel
 Use kickstarter data to inform and help a campaign organizer to reach their funding goals.

## Overview Of Project 
Louise’s play Fever came close to its fundraising goal in a short amount of time, we will help her to know how different campaigns fared in relation to their launch dates and their funding goals

### Analysis and Challenges
Before starting do the analysis based on the goal and based on the launch date we need to organize the sheets, I added extra columns to convert the launched date and the due dates to readable date 
I did the analysis based on launch date to check how the season affect the successful of the campaign and did the analysis based on the goal range to see if her campaign goal estimation will be within the range 

### Analysis of Outcomes Based on Launch Date
In order to do the chart of the launch date we had to focus of the (successful, failed and canceled) of the theater campaigns based on launch date and to do that we had change the dates columns to readable ones then do the pivot table of the data set, the pivot chart can be filtered by removing the outcomes of live campaigns, modifying the rows to only show the months of the year and filtering the parent category to show data for “theater” only

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/98668175/153695538-f921eadc-b9b1-475e-b497-10217445d0ba.png)

### Analysis of Outcomes Based on Goals
To do this analysis we need to create a new sheet and new table, The table contains the goal ranges , ranging from less than $1,000 up to greater than $50,000. we used the COUNTIFS function utilized to capture the outcome and goal data for the “plays” subcategory, to determine the number of successful, failed and canceled campaigns based off the corresponding funding goal. Based off this data, the total number of successful, failed and canceled projects could easily be calculated by using the SUM function. Upon calculating the percentage of successful, failed and canceled projects, a line chart was created to visualize the data.

![Outcomes_vs_Goals png](https://user-images.githubusercontent.com/98668175/153695546-cd52930c-385e-4cf7-adc6-63ef588cd677.png)

### Challenges and Difficulties Encountered
The main challenge I encountered is to settle the Pivot Table fields in MS Excel, selecting the most appropriate filter, column, row and value fields is essential. I made couple of mistakes before getting to the required result. Prior to creating a Pivot Table, it is necessary to have a sense of which data needs to be summarized, along with how the data should be presented.

## Results
What are two conclusions you can draw about the Theater Outcomes based on Launch Date? 
After I did the analysis and chart I noticed that the success rate of launching a theater campaign is highest in May and June. I also conclude that the months of October, November and December prove to have a steady decline in the overall success rate of launching campaigns, and noticed increasing in failed campaigns during that period, while not having campaigns canceled in October and about a 50% success/fail rate in December.

What can you conclude about the Outcomes based on Goals?
In analyzing the data, it can be concluded that the rate of success is higher for campaigns with a funding goal that is less than $5,000. Campaigns with a funding goal of less than a $1,000 up to $4,999 had a success rate ranging from 70% to 73%, while campaigns with higher funding goals didn’t have nearly as high of a success rate.

What are some limitations of this dataset?
The global dataset contains of more than 4,000 data points, only part of the data points pertain to plays. By increasing the data points across all categories and subcategories, not just the theater category and plays subcategory, the results will be more statistically relevant. Due to the lack of data, it is difficult to assess the full scope of the success of the campaigns. In order to truly have a better understanding of the success of theater projects, pertaining to plays, it would be helpful to gather data from a variety of other crowdsourcing platforms.

What are some other possible tables and/or graphs that we could create?
Conducting a comparative analysis of theater campaigns, as it relates to the 8 other parent categories would be helpful. analysing the subcategory data under the parent category of theater would also be useful to determine the overall success of plays in comparison to the other subcategories. By following the steps for analysis, tables and pivot tables can be generated to help visualize the data and ultimately organize it by utilizing a graph.



