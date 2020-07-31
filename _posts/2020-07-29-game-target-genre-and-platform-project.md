---
layout: post
---

# Data Analyst Project What Game Should We Build First

Objective

>In this project I would like to determine what genera and platform we should use for our first video game launch.

Data Source

>I will be using historical sales data of previous video games across all platforms.

Collection Method

>I will “SSH” remote access our cloud server to run a search on existing data with a filter to copy lines containing key words (i.e. video game platforms) to a new file.  I will “SCP” the new file to my computer for further analysis. I will also search free data sources such as Kaggle for pertinent data. 

ssh -i /path/my-key-pair.pem my-instance-user-name@my-instance-public-dns-name

awk '/list/' file1 > file2

scp -i /path/my-key-pair.pem my-instance-user-name@my-instance-public-dns-name:~/SampleFile.txt ~/SampleFile2.txt

Analysis Methods

>I will use Tableau Prep to clean filter and join the pertinent information from all source files. I will use Tableau Desktop to create visualizations and create an interactive live dashboard for future analysis of platforms.
Using Tableau create line chart of average unit sales per game per platform from 2000 to 2015. Time line based on available data and relevance to existing platforms. Next build bar graph of overall platform performance over that fifteen-year period. From the chart we can see the most consistent platforms in current circulation. 
Also using Tableau Desktop create a line chart of genre performance per game from 2000 to 2015. As well as a bar graph of the overall genre performance over the fifteen-year period.
Given these 2 sets of analysis I will create a chart of the three most relevant platforms and three most relevant genres. From here we can target a distinct platform and genre for our next game. 
For additional cross reference I will also build an interactive dashboard for these existing charts and a pie chart showing the contribution of each genre for a given platform in given year range and a title list to search for specific titles and genres for a given platform in a given year or year range. Total projected working time 32 hours.        

<img src="/images/project-1/per-platform.jpg" alt=""/>

<img src="/images/project-1/platform-rank.jpg" alt=""/>

<img src="/images/project-1/per-genre.jpg" alt=""/>

<img src="/images/project1/genre-rank.jpg" alt=""/>

<img src="/images/project-1/top-targets.jpg" alt=""/>

<img src="/images/project-1/genre-contribution.jpg" alt=""/>

<img src="/images/project-1/title-list.jpg" alt=""/>

https://public.tableau.com/profile/travis.crowell#!/

Results

> Per current relevancy I decided to look specificaly at years 2000-2015. Looking at my platform ranker the top sales per title was actually the game boy platform with very few titles released in 2000 and 2001. I'll focus on the three next best brands Playstation, Xbox, and WII. Looking at my genre ranker for theese three brands within my year range I find the top three genre per title are Shooter, Platform, and Sports.
Looking at the per platform and per genre page you can see the buyer preferances change over the years. looking at best performers I can chart the performance of theese three genres across the platforms I choose. to see a very specific story I'll look at PS3, XBOX360, and WII. In the top performing category of shooter Xbox360 and PS3 perform better, While WII has had some break out years in sports and platforms. switch to Title names and you can like theese peeks to specific titles.
With this clear picture my recomendation would be to creat a first person shooter with features simillar to Halo or Call of Duty. First released on Xbox brand then if possible add to Playstation. I would save the nintendo platform for a second release that is a platform genre or sports ganre.   