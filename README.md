# Kickstarter Analysis using Excel

## Overview of Project

- This project has two goals.
  1. The first goal is to see which months Theater campaigns are most successful.
  2. The Second goal is to look into which campaigns are able to succeed based on the goal amount requested.

### Purpose

- Louise is almost done with her fundraising project, and hired me to compare how her play is doing compared to other plays, using available kickstater Data.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

![OutcomesVsGoals](https://github.com/CaptCarmine/kickstarter-analysis/blob/main/resources/Theater_Outcomes_vs_Launch.png?raw=true)

- As seen in the graph above you can see that the months of May and Jun had the largest number of successful campaigns.

- It is also interesting to note that success seems to be cyclical, as the most successful months are late Spring/ early Summer, and the least successful is late Fall/early Winter .

### Analysis of Outcomes Based on Goals

![OutcomesVsGoals](https://github.com/CaptCarmine/kickstarter-analysis/blob/main/resources/Outcomes_vs_Goals.png?raw=true)

- The large trend surrounding Goal Outcomes, is that the more expensive the campaign, the less likely it is to succeed.
- The data though past 25,000 is less rich though as multiple categories have less than 10 data points. alss the greater than 50,000 has an extremely high delta between the data points probably probably pointing to some of those being outliers.

### Challenges and Difficulties Encountered

Their were two different points in which I had difficulty completing the assigmnent.

1. The first difficulty I encountered was figuring out how to apply the decending sort for the column labels in the pivot table. When I first completed the assignment,I missed that requirment. When I did realize it was needed I had difficulty understanding where to sort.I eventually was able to find the setting in the drop down in the colum labels, and resolve it.
2. The second difficulty I encountered was understanding how to generate the countifs code. There were multiple different filters, I had to add, and I needed to use the reference material.

```excel
=COUNTIFS(Kickstarter!$F:$F, "=Successful",Kickstarter!$R:$R, "=plays", Kickstarter!$D:$D, "<1000")
```

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
  1. The month of May or June are the months with the most successful campaigns.
  2. Regardless of number of total campaigns in a month the failures where in the 31 to 52 range.

- What can you conclude about the Outcomes based on Goals?
  1. You can conclude that the less expensive your campaign the more successful it will be.

- What are some limitations of this dataset?
  - for all the variables we did not have enough data. Looking at the outcomes based on goals specifically, 4 of the 12 ranges had less than 10 data points to compare. Also having a field with hours or cost associated to marketing the campaign would yield more interesting data as to whether that lead to success, failure, or cancelation .

- What are some other possible tables and/or graphs that we could create?
  - we could also add a box and whisker plot, which I believe would help identify outlier data points, as well as see if there is a correlation between success and quartile.
