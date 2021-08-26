# An Analysis of Kickstarter Campaigns

## Overview of Project

### Performing analysis on Kickstarter data to determine how different campaigns fared in relation to their launch dates and their funding goals

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
I organized the information of the number of successful, failed, and cancelled outcomes based on their Kickstarter launch date using a pivot table. I then sorted and examined the newly organized information, and fiiltered the information to look exclusively at theater projects. I then graphed the findings in a line graph to visualize the total number of each outcome across the timeline.

![Theater_Outcomes_Based_on_Launch_Date](resources/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals
I constructed a table to gather and organize the information of the number of successful, failed, and cancelled outcomes based on what funding goals. I had the table group the results based on predetermined ranges of their funding goal, and filtered the data to look exclusively at plays by using the COUNTIFS function. I calculated the total projects in each funding goal range using the SUM function. I calculated the percentage of successful, failed, and cancelled projects for each funding goal range accordingly. I then graphed the findings into a line chart to visualize the relationship between the goal amount ranges and the percentage of successful, failed, or canceled projects.

![Outcomes_Based_on_Goals](resources/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered
This data was clean, but I might have had to clean the data to uncover any potential outliers. I also ran into a challenge thinking about other graph styles to visualize the "Outcomes Based on Goals" findings that may be more suitable than a line graph.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
	1. Theater Kickstarters which launched between April & August had the most successful outcomes with a peak for ones that started in May.
	2. Theater Kickstarters launched in December had a significantly lower success rate than any other time of year.

- What can you conclude about the Outcomes based on Goals?
	1. Projects for plays with fundraising goals of under $5,000 had a much higher chance of success.

- What are some limitations of this dataset?
	1. The dataset has a small sample size prior to the year 2014, and for projects with funding goals above $15,000 which makes it more difficult to determine any trends.
	2. The dataset does not cover the full scope of a project. Presumably projects with fundraising goals of less than $5,000 vs goals of over $50,000 have different desires which perhaps should not be compared to each other.
	3. The dataset does not take into account any other factors that may have effected the project's outcome, such as environmental or economical conditions at the time of launch.

- What are some other possible tables and/or graphs that we could create?
  	1. A stacked column graph visualize the "Outcomes Based on Goal" findings as opposed to the line graph may be more appropriate.
	2. A theater "Outcomes Based on Launch Date" table & graph based on percentages instead of just total outcomes.
	3. Similar graphs based on other categories besides theater and plays to see if these trends follow across all Kickstarter categories.
