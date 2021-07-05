## Background

The Los Angeles Dodgers are a Major League Basebell franchise located in Los Angeles. League games take place in large stadiums, where fans pay an admission fee to watch. These ticket sales and other on-site revenue sources make up a substantial portion of a franchise's total revenue. 

## Problem statement

Is there a promotional strategy would be effective for boosting attendance at Los Angeles Dodgers games? What has been working, and what can be changed?

## What data

We have a dataset of 81 records showing attendance numbers and several other properties of each game day. These properties include

- the date of the game
- the opponent
- the temperature
- whether it was a night game
- whether each of four promotional item types was offered

The promotional item types are cap, shirt, fireworks, and bobblehead.

## What methods

The aim is to increase profits which means increasing attendance in a cost-effective way. I searched for factors correlating with attendance. Regression was used to examine the relationship between temperature and attendance.

### Technology

The analysis was performed in a Jupyter notebook, leveraging the pandas, scipy, and seaborn libraries.

## What conclusions

The bobbleheads were the most effective promotional strategy. Also, while attendance positively correlated with temperature, analysis of the early fall revealed that this is likely due to customer schedules being more open during summer, rather than a customer preference for higher temperatures. In fact, higher temperatures may be depressing attendance. It is recommended to adopt or enhance heat mitigation strategies at stadiums for observation of the effect on attendance.

## What questions remain

The effect of a promotional strategy on other-day attendance cannot be determined from the data set. Attendance is high on days with bobbleheads, but this may simply be shifting business to that day rather than generating new business.

