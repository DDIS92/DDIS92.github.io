---
layout: post
title: 5 Things to Remember When Analyzing Data
---


Whenever you have a project that involves data analysis, there are 5 steps (at minimum) that you should follow. These steps offer the foundation for any analyst to properly pick apart the data and produce reliable and valid results. In this blog, we will be using examples from a project that I was working on. The goal of this analysis was to try to determine what factors influenced average ranking numbers in the year 2000.

1.Define a Problem Statement: You should decide what you are trying to analyze. This should always be your first step in the project. Make sure that the question is defined via the SMART goals:

a.	Specificity: Specify as best as you can what you want to analyze. This will make it easier for you to come up with results. Here are some examples of implementing specificity when coming up with a problem statement:

  i.	Specify a particular relationship between variables that you want to test out. Alternatively, specify which variable you are trying to predict. In my project, I was trying to determine patterns and trends in the average rank number based on certain variables. 
  
  ii.	Specify which variables you are using as metrics. This includes the dependent variable (i.e. the variable that you are trying to predict/analyze) and the independent variables (i.e. the variables that you hypothesize are factors that influence the dependent variable). In my case, my independent variables were the genre of the song, the months that the song was entered and peaked, and the length of the song.
  
  iii.	Specify the year that you wish to examine. This will give anyone that is interested in your research some context. My dataset was for the year 2000.

b.	Measurability: You need to make sure that your answer can be quantified. This allows you to assess whether or not you can answer the question, and how well you have answered the question.

c.	Attainability: Can you attain all of the data that you need? Can you use the methods required to analyze and interpret the data?

d.	Reproducibility: Can your results be reproduced by someone else? This is important as it is hard to trust results that can only be reproduced by one person. Your reputation might be damaged if you neglect to consider this.

e.	Time-Bound: Often, you do not have the freedom to work on your analysis forever. You need to meet deadlines. Can you complete your analysis in the given time period? 

2.Know What the Dataset Contains: It’s important to know what information your dataset has. Following this step allows you to:
  
a.	Focus your analysis on the most important variables. This is also part of step 3 (i.e cleaning the data).

b.	Understand the data types. This may or may not influence you to manipulate variables to best suit your needs. 

c.	Decide what methods of statistical analysis are practical in the given time frame. You cannot work on this data forever, so you have to find practical and meaningful methods of measuring data.


3.Clean the Data: Datasets are usually messy. Values might be missing, nonsensical, or vague. Cleaning is a tedious, but necessary, process to ensure that your analysis goes smoothly. There are lots of ways to clean data. You can remove missing values, fill them with your own, or even obtain them from other trustworthy data sources. It is important to explain why you cleaned the data (or certain variables within the dataset), how you cleaned it and why you cleaned it the way you did.

In my case, I had 76 columns of data, but half of these columns were full of missing values. I decided to remove some of these values as I thought that filling these missing values with predicted values would heavily skew the data and lead to misleading conclusions.


4.Plot Graphs, Tables and Charts: Visualizations help show patterns in the data and convey a lot of information without being unnecessarily complicated. Keep in mind that these visualizations are subject to how you manipulate your variables. Remember to state your assumptions when presenting data to make sure that you do not mislead anyone looking at the graph. Below are some examples of trends/patterns that I observed. Keep in mind that half of my data was omitted because it was missing.

[Average Ranking No. by Genre](https://github.com/DDIS92/DSI-HK-1/blob/master/projects/project-02/starter-code/Average%20Ranking%20By%20Genre.png) - Since I had over 300 songs, I decided to use the average ranking number. A higher number means a lower rank on the billboard. The Rock Genre has the lowest average ranking number, which might suggest that rock songs are usually going to be a hit.

[Average Ranking No. by Months Entered](https://github.com/DDIS92/DSI-HK-1/blob/master/projects/project-02/starter-code/Average%20Ranking%20by%20Months%20Entered.png) - In this graph, I was trying to determine the trend of rankings over the year 2000. The average ranking number increased over the year, suggesting that it might be better to enter the song as early as you can.


5.Decide Which Method(s) of Higher Level Analysis You Are Going to Use: There are a lot of higher level methods of analysis (e.g. regression models, hypothesis testing, normalization tests, etc.). However, these should be implemented once you understand what you want to test and know which variables to test. These should be considered after you have done all of the other steps as it is simply a matter of deciding which one to use based on the cleaned data.

That's all for today. I hope that this gave you a better understanding as to how to approach a project involving data analysis. If you would like to see my Notebook for this project, please click on [this link](https://github.com/DDIS92/DSI-HK-1/blob/master/projects/project-02/starter-code/Siddarth%20Anand%20Billboard%20Project.ipynb)	
