# Kickstarting with Excel

## Overview of Project

### Purpose
This project analyzes Kickstarter campaigns that launched between 2009 and 2017 to identify actionable ways to implement a Kickstarter campaign for a play that will reach its amount pledged goal before the campaign deadline.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
One way to leverage this data is to identify the ideal time of year to launch a Theater campaign. Based on the sample of 1,369 completed Kickstarters, more successful campaigns launched in late spring through summer. Over 40% of successful theater campaigns launched in the months of May through August. 

![Theater_Outcomes_vs_Launch](https://github.com/skyeryser/kickstarter-analysis/blob/main/resources/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals
The success of Kickstarters that were subcategorized as "plays" is related to the campaign goal. Kickstarters for plays with goals less than $14,999 are more likely to succeed than fail. If the set goal is between $15,000 and $19,999, the campaign had a 50% chance of success, and a 50% chance of failure. For higher budget productions, the ideal campaign goal is between $35,000 and $44,999. After this point, increasing the goal will significantly reduce the campaign's chances of success.

![Outcomes_vs_Goals](https://github.com/skyeryser/kickstarter-analysis/blob/main/resources/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered
The original data needed cleaning up and interpreting prior to performing the analysis. One example is that all the date values were written as unix timestamps and needed to be converted to a readable date format for them to be legible.
Another challenge with this analysis was choosing which areas within the data to focus the analysis. It helped to limit the project to the subcategory of plays, however there are still other avenues to explore such as region and average donation that may offer even more insight.

## Results

- It is ideal to launch a theater campaign during the summer when the weather is warmer in the Northern Hemisphere. The best two months to launch a campaign are in May and June. The worst time to launch a campaign is in winter from December 

- The highest number of successful plays have Kickstarter goals under $14,999. There were a total of 6 successful campaigns with goals between $35,000 and $49,999.

- One limitation of this dataset is that the majority of the data was collected from regions in the Northern Hemisphere. In order to gain a balanced perspective of the ideal months to launch a theater Kickstarter, it would help to collect more information from countries in the Southern Hemisphere where seasonality is the opposite.

- Further analysis of the highest average donation will add more insight to this project. Adding charts that depict the highest average donation by region and season would indicate the ideal location and time to launch a Kickstarter with a higher campaign goal.
