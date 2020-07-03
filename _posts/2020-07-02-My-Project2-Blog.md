---
layout: post
title: This is the blog for project 2
---
## Project Summary

In this project, I read in the news popularity data published by [Mashable](www.mashable.com) located in [UCI](https://archive.ics.uci.edu/ml/datasets/Online+News+Popularity), and convert the data into dataframe for plotting and exploratory analysis. This dataset summarizes a heterogeneous set of features about articles published by Mashable in a period of two years. The goal is to predict the number of shares in social networks (popularity). 
Please refer to the [Code Repository](https://github.com/mhe8/project2), and the READ.md is published as a [webpage](https://mhe8.github.io/project2/)
## Discussion

### what would you do differently?
As I mentioned in the project reports, those variables can be classified into different categories, so it's better to analyze the multi-colinearity within each groups, and pick up some representatives from each categories to train the models.


### what was the most difficult part for you?

I found the most difficult part is to decide which variables should be included into the models, although AIC is used for this purpose, but it's better to check other options as well.

### what are your big take-aways from this project?

My takeways:

+ Generally speaking, bagging (or other ensembling methods) is expected to generate higher accuracy, in this project, I didn't much differences.
+ Variable selection is very important for modelling the results, and R provides very easy way to do such analysis
