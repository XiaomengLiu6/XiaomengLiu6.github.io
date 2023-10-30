layout:Page
---
This is the blog post 3.
For your blog post, write up a brief discussion of how you would plan to determine variables to use in a regression model.  
What variable selection techniques do you prefer and why?. 

I would take a closer look at the data and study. Do we want to make predictions? What is the type of the data? Are the 
variables highly correlated? Is the sample size large enough or do we need to do bootstrap?

I would prefer to use the randomForest by caret package for the supervised study. It could avoid the influence of a strong 
predictor in the data set. It also performs better than the common linear model selection. We do not need to use all predictors.

