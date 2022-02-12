# kickstarter_excel
 Use kickstarter data to inform and help a campaign organizer to reach their funding goals.

## Overview Of Project 
Louise’s play Fever came close to its fundraising goal in a short amount of time, we will help her to know how different campaigns fared in relation to their launch dates and their funding goals

### Analysis and Challenges
Before starting do the analysis based on the goal and based on the luanch date we need to organize the sheets, I added extra columns to convert the luanched date and the due dates to readable date 
I did the analysis based on luanch date to check how the season affect the successful of the campaign and did the analysis based on the goal range to see if her campaign goal estimation will be within the range 

### Analysis of Outcomes Based on Launch Date
In order to do the chart of the launch date we had to focuos of the (successful, failed and canceled) of the theater campaigns based on luanch date and to do that we had change the dates columns to readable ones then do the pivot table of the data set, the pivot chart can be filtered by removing the outcomes of live campaigns, modifying the rows to only show the months of the year and filtering the parent category to show data for “theater” only

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/98668175/153695538-f921eadc-b9b1-475e-b497-10217445d0ba.png)

### Analysis of Outcomes Based on Goals
To do this analysis we need to creat a new sheet and new table, The table containg the goal ranges , ranging from less than $1,000 up to greater than $50,000. we used the COUNTIFS function utilized to capture the outcome and goal data for the “plays” subcategory, to determine the number of successful, failed and canceled campaigns based off the corresponding funding goal. Based off this data, the total number of successful, failed and canceled projects could easily be calculated by using the SUM function. Upon calculating the percentage of successful, failed and canceled projects, a line chart was created to visualize the data.

![Outcomes_vs_Goals png](https://user-images.githubusercontent.com/98668175/153695546-cd52930c-385e-4cf7-adc6-63ef588cd677.png)

### Challenges and Difficulties Encountered
The main challenge I encountered is settle the Pivot Table fields in MS Excel, selecting the most appropriate filter, column, row and value fields is essential. I did couple of mistakes before getting to the required result. Prior to creating a Pivot Table, it is necessary to have a sense of which data needs to be summarized, along with how the data should be presented.

## Results
