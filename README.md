# Kickstarting with Excel
## Overview of Project and Purpose
In this project, we were tasked with analyzing the relationship between the launch date of a campaign and the outcome of the campaign using the category of "Theater" as well as the relationship between the outcome a campaign and the goal amount using to sub-category of "plays" to analyze the various outcomes of campaigns.
### Purpose
The purpose of this analysis was to see in which goal amount range had the most successful, failed, and canceled campaigns in terms of percenatge when using the sub-category of "plays," as well as to see which month was best to launch a new campaign under the category of "theater"
## Analysis and Challenges
### Analysis of Outcomes Based on Launch Date
To analyze the relationship between the outcomes of campaigns and the luanch date, I needed to create a pivot table which showed successful, failed, canceled, and grand total of campaigns broken down my months. After filtering the data by the category of theater, the pivot chart looked like this:
<img width="1440" alt="Screenshot of theater outcomes of pivot table" src="https://user-images.githubusercontent.com/96593480/147400557-2c85ad16-6dc2-415a-a1da-281a5700e8c1.png">
Using this pivot chart, I was able to create of a line graph which helped visually demonstrate which month was best to launch a campaign for the category of theater based on the number of successfull campaigns for each month.
### Analysis of Outcomes Based on Goals
To analyze the relationship between the outcome of camapigns and funding goals, I needed to create a range for funding goals. Doing this would demonstrate in which range the campaigns filtered by the sub-category of "plays" were most successful or unsuccessful by percentage. Using the countifs function, I was able to filter the data to count the number of successful or failed campaigns by the range, outcome, and sub-category. After doing this, I eneded up with a table:
<img width="1440" alt="Goal vs outcome screenshot" src="https://user-images.githubusercontent.com/96593480/147401129-3be8784a-b5b8-4693-ae53-37a377dbddcf.png">
Using this table, I was able to create a line chart to visually demonstrate which goal range led to the most successful and unsuccessful campaigns in terms of percentage for the sub-category of "plays"

### Challenges and Difficulties Encountered
The main challenges I faced during this project were the issues with the manipulated spreadsheet from Module 1 along with learning how to properly insert a line graph using only select data from a dataset. I overcame these challeneges by refering back to the original, non-manipulated, data set to ensure that line graph in the instructions match the one I created. After some trial and error, I was able to figure out how to select only certian data using the chart design tab.
## Results
Conclusions that can be drawn abourt for the Outcomes Based on Launch Date Line chart such as that the best month to launch campaigns under the category of "Theaters" is might be May as it had the most successful campaigns, but it also has a signifcant amount of failed campaigns for that month. Another conclusion that can be drawn is that December is not a good month to launch this type of campaign as it has a very similary number of successful and failed campaigns for that month.

One conclusion that can be drawn for the funding goal and outcome comparison is that a funding goal for a new campaign under the sub-category of "plays should be less than $5,000 as the data shows that the two ranges, "Less than 1000," and "1000 to 4999," had the most sucess in terms of percentage.

While we are able to analyze the given data to help us answer some questions, we still need to consider some limitations of the dataset such as outliers as they might an impact on overall analysis if not excluded.

While the two line graphs do offer some insight, a bar graph might be a better visualization to help others understand what they are looking better. We could also create another table for Outcome and Launch Date for the "theater" category to show the percentage of successful or failed campaigns for a specific month. This could give us even more a decisive conclusion.
