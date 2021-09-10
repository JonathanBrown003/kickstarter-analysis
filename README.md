# Kickstarting with Excel

![Theater_Image](https://raw.githubusercontent.com/JonathanBrown003/kickstarter-analysis/main/Resources/Theater_Image.jpg)

## Overview of Project

Louise would like to determine the efficacy of campaigns from past data in relation to their respective launch dates and funding goals. The main category and subcategory analyzed in this project were “theater” and “plays,” respectively. Louise will use this analysis for future determinations of fundraising efforts.  

### Purpose

This analysis may determine future fundraising efforts aimed at the theater category and play subcategory. The goal structure and launch date of future fundraising campaigns will be influenced by the data and trends expressed in this analysis.     

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

Theater outcomes certainly peak in total number during the launch months of May and June. Approximately 67% of campaigns were successful with a launch date of May (111/166) while roughly 65% of campaigns were successful with a launch date of June (100/153). There may be a correlation to theater campaigns being successful in the months of May and June. Another noteworthy observation is the total number of campaigns launched in these 2 months far surpassed other months for the theater category.

![Theater_Outcomes_vs_Launch](https://raw.githubusercontent.com/JonathanBrown003/kickstarter-analysis/main/Resources/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals

At first glance, 0 campaigns were canceled for the play subcategory in the time we collected data. This indicates consistency and professionalism in the initial setup of the fundraising campaigns to have all completed whether they were successful or failed. There is an obvious correlation with high percentage successful campaigns based on goal amount and lower fundraising goals relative to the other campaigns. For instance, 76% of campaigns aimed to raise less than $1,000 were successful while 73% were successful which had a goal between $1,000-4,999. 

![Outcomes_vs_Goals](https://raw.githubusercontent.com/JonathanBrown003/kickstarter-analysis/main/Resources/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered

One particular challenge was the embedding of images in the README.md section of GitHub. I tried numerous google searches for clarification and used the exact syntax provided in the module but the image wouldn’t embed but instead was a clickable link to view on a separate tab. I finally figured it out by clicking on the particular image in the "resources" folder that I wanted to embed then copying the image link. The general navigation through GitHub for a new user is challenging but this should subside with experience. 

The nesting of functions within Excel has always brought challenges for me personally but the class demonstrations and breakout sessions greatly improved my understanding of how to execute nested formulas. 

This Help page was helpful in working through nested formulas: [Microsoft Help - Nested Formulas](https://support.microsoft.com/en-us/office/use-nested-functions-in-a-formula-9d7c966d-6030-4cd6-a052-478d7d844166)

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

A recommendation to Louise would be to initiate more campaigns in May and June due to the high percentage of successful campaigns and total number of successful campaigns as well. Successful campaigns peaked in May and June while also having a good success rate for both launch months. 

Another recommendation to Louise would be to analyze the data in strictly percentage successful terms. This would ensure a more accurate representation of the data because the total number of campaigns launched would not be a factor, just percentage successful.

- What can you conclude about the Outcomes based on Goals?

Lower fundraising goals showed a markedly higher successful percentage than higher goal campaigns. Scheduling more frequently occurring, lower goal campaigns would likely result in more dollars raised and fewer failed campaigns. 

- What are some limitations of this dataset?

A limitation of the Outcomes by Launch Date data set is the usage of the raw total number of successful campaigns. The total number of successful campaigns may not necessarily be the appropriate indicator. As I summarized above, “Another noteworthy observation is the total number of campaigns launched in these 2 months far surpassed other months for the theater category.” You would expect to see a higher raw number of successful campaigns during May and June because so many more campaigns were launched relative to other months. 

The more fitting indicator would be the percentage of successful campaigns in relation to the total number launched. This way, you could ascertain which months have a higher percentage of successful campaigns than May and June, respectively. This may help Louise capitalize on those months. 

- What are some other possible tables and/or graphs that we could create?

I would create an additional pivot table for Launch Dates Based on Outcome to show the percentage of successful campaigns by launch month. We could then create a line chart to plot the data points for each month to immediately spot trends in the data. This would be a more efficient use of this data (percentage rather than total number) for reasons I highlighted above. 

For Outcomes Based on Goals, I would create a bar chart to show the goal on the X-axis and percentage successful on the Y-axis. This would help visualize the percentage differences between successful campaigns. You could then drill down on each goal to determine reasons for high percentage success rate and the lower percentage success rates. For instance, there’s an unusual success rate for  higher goal campaigns between $35,000 to $39,999 and $40,000 to $44,999.
