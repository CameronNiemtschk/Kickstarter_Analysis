# Kickstarting with Excel

## Overview of Project
	In this project we were tasked to analyze data for multiple Kickstarter campaigns reported over the last few years. The projects contained a variety of data about it such as the goals, success, and type of project. For the project, the first goal was to create a pivot data for the data set in order to better organize the types of campaigns present and the amount. Furthermore, we were tasked to organize the campaign types by which month they were originally presented. Finally, the last part of the project was to successfully create a sheet to demonstrate the amount of play campaigns that were kickstarted and the percent of them that were successful in their fundraising goals.

### Purpose
	The purpose of this project was to successfully show the a comparison between the data and the campaigns. By analyzing the data and better organzing it, we can see the amount of campaigns that were kickstarted and filter them by type. Additionally, using additonal excel functions we can see the perctange of successful campaign types. This will allow for better understanding of the relationship between campaign type and success.

## Analysis and Challenges
	For the first part of the challenge, we created a pivot table for the data set. In order to first accomplish this, we had to first separate the category and subcategory cell using excel. This allowed for easier grouping in the pivot table and group parent categories together while still presenting what the subcategory was. Once this was accomplished, we had to find the date in which the campaign was officially started. This was on of the first problems that was encountered during project. The date was originally presented in an Epoch Unix time stamp. To convert the time stamp to a better understood time, we had to convert it using a formula. This gave a date that could then be better presented and then simplified using the YEAR () function in Excel.

### Analysis of Outcomes Based on Launch Date
	For this analysis, we created a pivot table of the data, specifically looking at the Parent category of each campaign and the month in which it was created. Furthermore, we looked out the goal outcome for the campaigns to see what there success was. For the results, we focused on the parent category Theater. Observing the data, we were able to see that the campaigns funded over the months were relativly constant, with the May and June being some of the highest months. Furthermore, December fell below the average. 

### Analysis of Outcomes Based on Goals
	The next part was to create another sheet and find the number of goals and their success. Using the COUNTIFS() formula in excel, we were able to successfully count the amount campaigns started for plays and their success. The count was grouped by range in which the campaigns initial fund goal was. Once a count was gathered for successful, failed, and canceled campaigns. Finally, we calculated the percent of total campaigns per range and create a graph to show the success versus goals. From here, we can determine the amount of campaign funding that was more likely to be successful.

### Challenges and Difficulties Encountered
Throughout the challegne, there were a few challeges that were encountered. One of the first challenges was the conversion of the EPOCH time into a more readible time and date. Upon first looking at the number I realized that the string of numbers were a date, but I was unable to figure out how to convert it in excel. It was not until searching for the answere did I figure out the simple answer. Another issue I had was creating the graphs, while the data was all present to create a graph required. I found that I was selecting the wrong data which created a completely different one. Reading the requirements again, we were able to figure out which data was appropriate to use.

## Results
	From the data sets that we created we can concluded that theater kickstarters have a realitivley high amount of success overall in terms of fundraising and are some of the easier campaigns to keep going. From the data we could see that a large majority of campaigns were consistently funded through out the months and at a variety of goals. While success goes up with the higher goal set, there is a cut off point in which goals begin to inhibit the success of a comapny.

- What are two conclusions you can draw about the Outcomes based on Launch Date?
	From the data that we were able to organize, we can conclude certain things from the data. For the first part of the project for the Theater Outcomes by Launch date, we can first conclude that for majority of the year, theaters are more likely to successfully funded. Through out majority of the year, the number of campaigns that were successfully funded always were noticeably higher. For every month, except December, the is gap between the two data sets. 

- What can you conclude about the Outcomes based on Goals?
	The first conclusion is that theater campaigns success is not limited to when someone starts the fundraising. While certain months are higher than others, there seems to be a direct relationship between the success and failed amounts for each month. A second conclusion that can be made from this is that canceled campaigns are highly unlikely to occur, throughout the month, canceled campaigns consistently stayed low. Meaning that if someone were to start a Kickstart for a theater, the odds of the campaign being canceled are highly unlikely.

- What are some limitations of this dataset?
	The limitations for the data that can be noted are that the subcategory for the theaters is not noted. While theater success is high overall, there is no telling if this success is caused by a specific type of subcategory.

- What are some other possible tables and/or graphs that we could create?
	The best way to counter this fault is to show the success percentage for the subcategories of theaters. This could show which subcategory is more likely to be successful and could help elaborate if a certain subcategory is affecting the original data set.