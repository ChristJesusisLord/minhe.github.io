---
layout: post
title: This is the blog for project 1
---
## Project Summary

In this project, I read in the NHL data with `JSONLITE` api, and convert the data into dataframe for plotting and exploratory analysis. My initial analysis shows that the wins v.s. the home wins are almost linear related, and this linear relationship holds with game type. 
Please refer to the [Code Repository](https://github.com/mhe8/project1), and the READ.md is published as a [webpage](https://mhe8.github.io/project1/)
## Discussion

### what would you do differently?
I would like to transpose the data and create a table contains the result_type ('win','homewin','tie','hometie','loss','homeloss') and another column result_count, and do the analysis for each home v.s. total results.


### what was the most difficult part for you?

I found the most difficult part is to intepreter the win histogram fo each team, as we have 38 teams, it's difficult to see the results when putting them into one graph.

### what are your big take-aways from this project?

My takeways:

+ `jsonlite` is an API easy to use, and the result can be easily converted in dataframe
+ The percentage of win at home is the similar to overall win percentage
+ Game type doesn't have big impact on the win percentage
