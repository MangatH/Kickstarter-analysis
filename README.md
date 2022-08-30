 # Kickstarting with Excel

## Overview of Project
The project is about analysis of different fundraising campaigns orgainised by Louise. This analysis will assist Lousie in taking her next fundraising campaign, based on the play 'Fever', in the right direction.

### Purpose
The main purpose is to analyse and visualise the data in accordance with the campaign outcomes based on their launch dates and funding goals. Another aspect to be noted here is that the analysis will also focus on the outcomes of the parent category 'theater' with respect to the funding goals, which will benefit Lousie, as she is planning another fundraising campaign  in the same category.

## Analysis and Challenges
The analysis was performed using various tools such as pivot tables and line charts. In addition to this various functions namely 'YEAR()' and 'COUNTIFS()' were used extensively.

### Analysis of Outcomes Based on Launch Date
In order to fathom the outcomes based on launch dates, it was quite important to extract the data based on different years. This was done using the function 'YEAR()', followed by creating a pivot table where the parent category and years were used as filters. Further, populating the rows and columns appropriately to have the best view of the outcomes.
<img width="1440" alt="Screen Shot 2022-08-29 at 12 53 29 AM" src="https://user-images.githubusercontent.com/111387025/187262698-527629a6-74c6-4723-8eee-21b0b7968d9a.png">

### Analysis of Outcomes Based on Goals
The outcome based on goals were analysed by finding out whether the campaigns were successful or a failure with regards to meeting their funding goals. For this purpose, the function 'COUNTIFS()' was used in order to draw out number of successful, failed and canceled campaigns on the selected data ranges of fundiung goals. Furthermore, based on this data the various percentages were calculated respectively. The line chart based on the combed dataset helped to have a better understanding about which months had the most successful campaigns, in contrast to the other months that were quite lagged behind.
<img width="1440" alt="Screen Shot 2022-08-29 at 12 57 39 AM" src="https://user-images.githubusercontent.com/111387025/187126292-b3922077-4dae-4226-abbe-47828ea43e5e.png">

### Challenges and Difficulties Encountered
It was a good brainstorming to analyse this extensive dataset. Precision is required to use functions such as 'COUNTIFS()', especially when applying it to a data range, as it requires the formula upgradation at every additional step according the data range in that row. https://user-images.githubusercontent.com/111387025/187128384-ac702ce7-a55f-47e2-a2a0-c7f6743da379.mov
The appropriate selection of filters and the elements of rows and columns in the pivot table is quite important for the best analysis.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

1. The month of May had the most successful campaigns in the theater category. On the other hand, the month of December had the least number of campaigns and ratio of success and failure was almost equal in this month.
2. While looking at the data quarterly, it is found that the second quarter of the year is quite favourable for launching campaigns, whereas the last quarter is least favourable in terms of the campaign being successful.

- What can you conclude about the Outcomes based on Goals?

Here it can be concluded that initially the percentage of successful campaigns was quite high in comparison to the failed ones. But later on, as illustrated with the line chart, it can be seen that the percentage of successful campaigns plunged and there were more failed campaigns, specifically in the goal range of 25000 to 29999. However, this trend reversed in the following goal ranges. The gap between the successful and failed campaigns was maximum in the goal range of 45000 to 49999.
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/111387025/187266742-dd66881c-2907-45ec-8380-970cf107cb2e.png)

- What are some limitations of this dataset?

I did not find any specific limitations with regard to the dataset. However, while analysing such an extensive dataset, it is essential to have a clear objective behind the analysis while being precise using the functions and tables. The appropriate selection of filters and data slicing, sometimes, becomes inevitable while analysing such datasets. 

- What are some other possible tables and/or graphs that we could create?

In addition to the tables used in the analysis, pie-charts can also be used to depict successful, failed and canceled campaigns month-wise. Bar chart is an another excellent option to do the comparison among different months. Furthermore, the analysis can also be divided quarterly to understand the performance of various campaigns and viewing them in a clustered column chart. Adding various color contrasts to the charts by using the format option can make the visualisation even more attractive.
