---
title: "Post: Standard"
categories:
  - Post Formats
tags:
  - Post Formats
  - readability
  - standard
---

Data Analyst Project What Game Should We Build First
Objective
	In this project I would like to determine what genera and platform we should use for our first video game launch.

Data Source
	  I will be using historical sales data of previous video games across all platforms.

Collection Method
	I will “SSH” remote access our cloud server to run a search on existing data with a filter to copy lines containing key words (i.e. video game platforms) to a new file.  I will “SCP” the new file to my computer for further analysis. I will also search free data sources such as Kaggle for pertinent data. 
ssh -i /path/my-key-pair.pem my-instance-user-name@my-instance-public-dns-name

awk '/list/' file1 > file2


scp -i /path/my-key-pair.pem my-instance-user-name@my-instance-public-dns-name:~/SampleFile.txt ~/SampleFile2.txt

Analysis Methods
	I will use Tableau Prep to clean filter and join the pertinent information from all source files. I will use Tableau Desktop to create visualizations and create an interactive live dashboard for future analysis of platforms.
	Using Tableau create line chart of average unit sales per game per platform from 2000 to 2015. Time line based on available data and relevance to existing platforms. Next build bar graph of overall platform performance over that fifteen-year period. From the chart we can see the most consistent platforms in current circulation. 
	Also using Tableau Desktop create a line chart of genre performance per game from 2000 to 2015. As well as a bar graph of the overall genre performance over the fifteen-year period.
	Given these 2 sets of analysis I will create a chart of the three most relevant platforms and three most relevant genres. From here we can target a distinct platform and genre for our next game. 
For additional cross reference I will also build an interactive dashboard for these existing charts and a pie chart showing the contribution of each genre for a given platform in given year range and a title list to search for specific titles and genres for a given platform in a given year or year range. Total projected working time 32 hours.        
