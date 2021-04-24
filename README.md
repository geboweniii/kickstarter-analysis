# An Analysis of Kickstarter Campaigns

## 1.	Purpose
Louise, a playwright with an interest in crowdfunding productions, has tasked this analyst with the job of reviewing crowdfunding data for the purpose illustrating how different campaigns fared in relation to their launch dates and funding goals. The goal of this effort is to provide her the insights necessary to plan future crowdfunded projects with the greatest chance for success.

## 2.	Analysis and Challenges
This analyst was provided structured crowdsource data in a Microsoft Excel file. The data contains pledged funding and funding goal information for over four thousand productions occurring between 2010 and 2017. Funding outcomes were determined by the success or failure of the producers to acquire enough pledged financing in relation to their funding goal. This data served as the sole source for this analysis.

## 3.	Limitations of Data
The funding data provided required minimal reformatting. Deadline and launch dates required conversion from Unix format to standard date format in order to facilitate effective analysis. Production categories and subcategories were concatenated strings requiring this analyst to partition the data into distinct fields in order to meaningfully refine and aggregate relevant areas of the overall dataset for accurate analysis. The dataset contains well defined empirical data. The age of the crowdfunding efforts represented in the data, the most recent of which was in 2017, was not relevant to this analysis but should be considered in any review of the results.

## 4.	Theater Outcomes by Launch Date
The first part of the analysis focused on the performance of theater productions over the course of a calendar year. Only theater productions were included and outcomes were plotted based on launch date. The resulting line chart reveals theater productions with May launch dates have the greatest success. Successful results decline throughout the rest of the calendar year. This trend leads to a near equal results between successful and failed productions launching in December.
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/82056100/115974683-5f3e6200-a52c-11eb-8d88-88e8be5ba125.png)

### 4.1	Conclusion #1
Theater productions appear to see the most success in the months of May and Jun. This is likely due to the weather changes and the onset of the vacation season. Theater-goers appear most ready to enjoy that entertainment most in the early summer months. 

### 4.2	Conclusion #2
Theater productions launching in December fail almost as often as they succeed. This reflects a busy holiday season for theater goers who appear less interested in productions opening in that time of the year.

## 5.	Outcomes Based on Goals
The second part of the analysis focused on the outcomes of plays based on funding goals of the production. Only data in the play subcategory was included in the results. Data were grouped based on outcome and funding goal. Outcome percentages were calculated in each funding goal range producing the following results.
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/82056100/115974682-577ebd80-a52c-11eb-8993-989abb63d93e.png)

### 5.1	Conclusion #1
The chart reveals that plays with funding goals below $4,999 enjoy the most success. Productions with goals between $35,000 and $44,999 also have a higher percentage of success. However, low cost productions appear to see the greater success rate.

## 6.	Recommendations
Based on the results of this analysis, producers should prioritize plays with lower funding goals that are targeted to launch in May. The limited scope of this effort would suggest there is value in additional review of the provided data with particular focus on the number of backers for each play produced. Additional visuals in the form of box charts reflecting the average number of backers for each funding goal range would provide valuable insights into the amount of networking required to produced a successful outcome.
