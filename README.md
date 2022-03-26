# Kickstarting with Excel

## Overview of Project
### Purpose
The client, Louise, wants to know how the different campaigns developed in relation to the launch dates and funding goals.  With the use of data and charts, we are able to determine how the campaigns progressed.
## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
In this data and chart, we are able to see that a grand total of 1369 theater campaigns were launched.  Within the totals, 839 were successful, 493 failed, and 37 were cancelled.  We are also able to see which months of the year gathered the most interests among the outcomes.  In the pivot chart, we are able to see that most of the campaigns ended up being successful. With the attached line chart, we can determine campaigns in the summer seasons (especially May and June) were the most successful, while the winter seasons trended downwards, or little interest at all. 

![This is an image](https://github.com/sadayas/kickstarter-analysis/blob/main/Theater_Outcomes_vs_Launch.png)
### Analysis of Outcomes Based on Goals
With the data shown, the lower fundraising goals up to 15000$ were successful atleast above 50%.  Anything over 15000$ as a fundraiser goal had some difficulty finding funding, or even just failed.  None of the goals were canceled.  However, with the included line chart, we can see the higher total goals of ($35000-$4500) were successful campaigns.  The failed ranges began to trend up.

![This is an image](https://github.com/sadayas/kickstarter-analysis/blob/main/Outcomes_vs_Goals.png)
### Challenges and Difficulties Encountered
The challenges involved finding the correct filter, and filters effected the data.  This was evident in the goals outcome because it lead to missing data, and I had to understand that a certain filter will not only change one column, but several columns.  The correct terminology was also important with the use of COUNTIFS(), because a single word or number, can error the code.
## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
 Campaigns in the summer time are the best months for a play to be launched.  Winter dates will have difficulty in finding funding.
- What can you conclude about the Outcomes based on Goals?
Lower funding goals will be successful compared to the higher funding goal amounts.
- What are some limitations of this dataset?
We do not know which play was successful, failed, or canceled.  Or how much the funding goals were for the successful or failed months.
- What are some other possible tables and/or graphs that we could create?
We can possibly create tables to figure out which monetary goals were successful in what month.  We could use a box plot to compare the different funding levels.
