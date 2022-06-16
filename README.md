# An Analysis of Kickstarter Campaigns: Performing analysis on Kickstarter data to uncover trends

## Overview of Project
  This analysis sought to look through a large database of data from prior crowdfunded projects to find patterns in the data to help our client best optimize their future crowfuned projects. It is our goal to come up with the best possible startagy with the data avalible to give them the greatest chance at making their project come to fruition. We used a few diffrent methods to demonstrait trends that could be used to help boost the succsess rate of their project.

## Analysis and Challenges
For my analysis of the data I made two graphs that should give useful insight into the level of funding that should be persued along with when the best times to seek funding are(see figure one and two below respectively). For the Outcomes vs Goals figure the main calcuations used to make it where done useing the COUNTIFS function. The specfifc code i used to accoplish what i wanted was `=COUNTIFS(Kickstarter!$F:$F, "successful", Kickstarter!$D:$D, ">=1000", Kickstarter!$D:$D, "<=4999", Kickstarter!$R:$R, "plays")` which essentially says count how many successful kickstarters with funding between 1,000 and 4,999 that where in the catigory plays. I then used This basice code but with diffrent varibles such as "failed" or looking inbeetweeen diffrent values to populate a table that could be used to calculate the percent of crowdfunded plays that where successful, failed or where cancled at diffrent ranges of funding goals. The only real road block I hit ehre was figuring out how to use the COUNTIFS function correctly. I did a little googling and found [https://www.ablebits.com/office-addins-blog/2014/07/10/excel-countifs-multiple-criteria/](url)
### Figure 1
![figure1](https://github.com/Louis-E-Martin/Kickstarter-analysis/blob/main/resources/Outcomes_vs_Goals.png)
### Figure 2
![figure2](https://github.com/Louis-E-Martin/Kickstarter-analysis/blob/main/resources/Theater_Outcomes_vs_Launch.png)
