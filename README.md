# Kickstarter Analysis using Excel

## Overview of Project

- This project has two goals.
 1.The first goal is to see which months Theater campaigns are most successful.
 2.The Second goal is to look into which campaigns are able to succeed based on the goal amount requested.

### Purpose

- Louise is almost done with her fundraising project, and hired me to compare how her play is doing compared to other plays, using kickstater Data.

## Analysis and Challenges

afaf

### Analysis of Outcomes Based on Launch Date

![OutcomesVsGoals](E:/Data_UM/Modules/1_Module_Week/kickstarter-analysis/resources/Theater_Outcomes_vs_Launch.png)
Based on what we were able to find on from the date given .

### Analysis of Outcomes Based on Goals


![OutcomesVsGoals](E:/Data_UM/Modules/1_Module_Week/kickstarter-analysis/resources/Outcomes_vs_Goals.png)
afafa

### Challenges and Difficulties Encountered

Their were two different points in which I had difficulty completing the assigmnent.

1. The first difficulty I encountered was figuring out how to apply the decending sort for the column labels in the pivot table. When I first completed the assignment,I missed that requirment. When I did realize it was needed I had difficulty understanding where to sort.I eventually was able to find the setting in the drop down in the colum labels, and resolve it.
2. The second difficulty I encountered was understanding how to generate the countifs code. There were multiple different filters, I had to add, and I needed to use the reference material.

```excel
=COUNTIFS(Kickstarter!$F:$F, "=Successful",Kickstarter!$R:$R, "=plays", Kickstarter!$D:$D, "<1000")
```

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

- What can you conclude about the Outcomes based on Goals?

- What are some limitations of this dataset?

- What are some other possible tables and/or graphs that we could create?
