# Kickstarting with Excel

## Overview of Project

### Purpose
The purpose of the project was to find the best time to launch a Kickstarter campaign, and discover what monetary goal was most likely to be successfully funded. 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

Using Kickstarter campaign data, Excel, pivot tables, and line graphs, I created this [Outcomes Based on Launch Date Chart](resources/Theater_Outcomes_vs_Launch.png) to show historically what months the most successful theater campaigns were launched.

### Analysis of Outcomes Based on Goals

Using Kickstarter campaign data, Excel, the COUNTIFS function, and line graphs, I created this [Outcomes Based on Goals Chart](resources/Outcomes_vs_Goals.png) to show the percentage of successful play campaigns outcomes based on goals.

### Challenges and Difficulties Encountered

I was working with a large dataset that had all Kickstarter data, not just the US play infomation I was curious about. Dates needed to be converted into ledgible dates. In working with the COUNTIFS function, I discovered I needed to be very careful with my syntax. One comma out of place makes the function error out. 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

Looking at all the theatre data, May was the month with the most successful campaigns launched at 67% with June being a close second at 65%. December was the worst month for successful campaigns at 49%

- What can you conclude about the Outcomes based on Goals?

Looking at all the play data, plays with a goal of under $5,000 had a 73% success rate. Plays with a goal of $5,000 - $25,000 had a success rate of 54%. Plays with a goal over $25,000 had a success rate of 32%.

- What are some limitations of this dataset?

In the outcomes based on launch date chart, we included all theater data in the dataset not just plays. We also included world wide results, not just US results. In looking at the data, I see we included a bunch of failed campaigns that had pledges of less than $10. This may have skewed the results some. We might should have removed them as outliers.

- What are some other possible tables and/or graphs that we could create?

We could also have included a chart showing the number of backers and the amount of pledges for successful campaigns.
