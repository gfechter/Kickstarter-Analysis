# Kickstarting with Excel

## Overview of Project

### Purpose
The purpose of this project was to analyze prior Kickstarter campaigns to determine the best time to launch a new campaign and what goal to target to increase the odds of success for launching a new campaign. Specifically, campaigns for theater and plays were analyzed. Additionally, after the client launched a new campaign, further information about how campaigns fared based on their funding goals and launch dates was analyzed.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
The fundraising campaign launched was to fund a play; therefore, theater campaigns and play campaigns were specifically analyzed. The outcomes of theater campaigns were analyzed based on the launch date. To analyze theater campaigns based on launch date, the first step taken was to create a new column that showed the year the campaigns were launched. Then, a pivot table was created that showed the number of successful, failed, and canceled campaigns per month for every year campaigns were launched. A line graph was created to visualize the data, which is displayed below. 

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/103774401/166126450-2cc1d84e-c33a-4b9d-bda7-04579fd25416.png)

### Analysis of Outcome Based on Goals
The outcomes of play campaigns were analyzed based on goal amount, as the client launched a play campaign. To analyze play campaigns based on goals, data from the Kickstarter sheet regarding successful, failed, and canceled campaigns based on fundraising goal was pulled to a separate excel sheet. Then, the number of campaigns based on and goal was converted to a percentage. The percentages were used to create a line graph, which is displayed below. 

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/103774401/166126453-a39dfb26-b361-4c59-9406-06eb6b280c13.png)

### Challenges and Difficulties Encountered
One challenge associated with this project was ensuring the formulas were correct for the outcomes based on goal analysis. Without the correct formulas, the numbers and the chart could be incorrect. The best way to find errors is to retrace steps and see if there was anything missed. 

## Results

### Conclusions
The outcomes of theater campaigns based on launch date indicate a few things. Overall, theater campaigns are more likely to succeed rather than fail. The most common month to launch a campaign was May followed by June, July, and August. The most successful month to launch a campaign was May. The worst month to launch a campaign is in December as the number of successful campaigns and the number of failed campaigns were nearly equal. 

For outcomes of play campaigns based on goals also indicate several things. Campaigns with goals less than $1,000.00 were 75.81% successful and campaigns with goals between $1,000.00 and $4,999.00 were 72.66% successful. This indicates that play campaigns with goals under $4,999.00 were very successful and the most successful campaign goals. Campaign with goals between $35,000.00 to $39,999.00 were 66.67% successful, and campaigns with goals between $40,000.00 to $44,999.00 were 66.67% successful. Campaigns with goals between $5,000.00 to $19,999.00 were all at least 50% successful ($5,000.00 to $9,999.00 were 55.03% successful, $10,000.00 to $14,999.00 were 54.17% successful, and $15,000.00 to $19,999.00 were 50% successful). The least successful campaign goals were between $45,000.00 and $49,000.00 were 0% successful. The second least successful campaign goals were $50,000.00 or more with a 12.50% success rate. Therefore, it seems that campaign goals of less than $10,000.00 are most successful, and so, for a new campaign the target goal for a campaign should be less than $10,000.00. 

The most popular month to launch a campaign with the highest chance of success is in May. Campaigns with goals of less than $10,000.00 have the highest chance of being successful. 

### Limitations
There are several limitations. The first is that there could be factors outside of launch month and goal that made a campaign successful. Without looking into other possible factors, there is no way to conclusively determine that launching in a certain month and with a certain goal will lead to a successful campaign. There is a positive correlation between launch month and a successful campaign as well as a positive correlation between campaign goal and a successful campaign. However, it cannot be concluded definitively that the launch month and campaign goal are the two factors that lead to a successful campaign. 

Another limitation is the size of the data analyzed specifically for outcomes based on goals. The number of campaigns with goals under $20,000.00 is much higher than campaigns with goals over $20,000.00. There were 985 campaigns with goals less than $20,000.00 whereas there were only 62 campaigns with goals over $20,000.00. Therefore, there are simply not enough campaigns with goals over $20,000.00 to draw any conclusions that can be accepted as true. Furthermore, displaying outcomes based on fundraising goals through percentages is somewhat misleading as it gives weight to outliers. Looking at the graph, there is no way to know the number of campaigns per goal range. 

### Other Possible Tables and Graphs
There are a few other tables and graphs that would be beneficial. It would be beneficial to add a table that shows both the number of successful, failed, and canceled campaigns and the percentages of successful, failed, and canceled campaigns per goal range. This table would add needed information to contextualize the outcomes based on goals line graph. Another additional table and graph that would be valuable to add would be the amount of time it took to reach the campaign goal. This would be beneficial as the client would have information about how long it would take to reach the campaign goal. 
