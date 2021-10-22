# Kickstarter-Analysis
Week 1 for Columbia's DA Bootcamp

# Kickstarting with Excel

## Overview of Project

	### Purpose
		The purpose of this analysis was to put into practice key functions of Excel which included, filtering and formatting the raw data given, creating pivot tables to analyze the statistics of the raw data, and to create visuals, pivot graphs, from pivot charts to express those results for our client named, Louise. And finally to familarize ourselves with GitHub, to commit our edits and upload our analyzed data into a repository.
	
	### Background
		Excel is a must-have skill when it comes to data analysis. It is the basis for collecting data, analyzing it, and displaying it to an audience for easier digestion. Through this exercise, we were able to learn common functions such as Filters, Sorting, VLOOKUP, Pivot Charts & Graphs, and more to organize bulk data into meaningful inferences that can be applied practically to solve problems, answer questions. 
	
		In this challenge, we were given the aim to help Louise find out how other play campaigns fared compared to their launch dates and funding goals using the Kickstarter dataset. The dataset contained information such as their fund goal amount, the success/fail/cancel/or live outcome of the kickstarter campaign, and the date of launch. Using the provided raw data, we needed to extract information to then run statistics for the counts of each outcome to answer Louise's inquiries. 
 
## Analysis and Challenges

	### Analysis of Outcomes Based on Launch Date
		Firstly, we extracted the date from the **UNIX timestamps** using the following formula below, then the year from the date using excel's year function: **year(cell)**. 

![Image](/Kickstarter_Analysis/Resources/unix_timestamp_to_excel_date.png

		To answer Louise's first queston of what the theater outcomes were based on the launch date, we created a **pivot chart** from the kickstarter worksheet that was able to filter by parent category (theater) and year, list the months as rows, and show the outcomes in columns. The pivot table showed counts for each month of the number of successes, fails, canceled theater campaigns, and those that were live (still active). We selected only the successes, fails, and canceled campaigns because there was no significance to view live campaigns since it was not applicable to Louise's question.
		
		
![Image2](/Kickstarter_Analysis/Resources/Theater_Outcomes_PivotChart.png)		
		Using the pivot chart, we then created a pivot line graph comparing the outcomes of each play campaign to its launch date.
		
![Image3](/Kickstarter_Analysis/Resources/Theater_Outcomes_vs_Launch.png)

	### Analysis of Outcomes Based on Goals
		Secondly, we compared the campaign outcomes to the goal fund amounts.

	### Challenges and Difficulties Encountered

## Results

	- What are two conclusions you can draw about the Outcomes based on Launch Date?

	- What can you conclude about the Outcomes based on Goals?

	- What are some limitations of this dataset?

	- What are some other possible tables and/or graphs that we could create?
