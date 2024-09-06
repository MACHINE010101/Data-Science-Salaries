# Data Science Salaries
### Author: Eduard Pascale

## DA Practice 1: Data Science Salaries

Research question: we want to predict the salary

There are a few columns related to salary (salary, salary in USD, salary currency)

Question on data cleaning: how should you deal with this? 

Question on data cleaning: how to deal with the job titles? Tip: make this simpler by introducing fewer hand-made categories. You need to craft these by hand in general, but I am giving you a function that offers a solution (and yes, building functions like this are a part of data cleaning. You need to build one for converting countries to continents). def segment_job_title(job_title).txt

Download def segment_job_title(job_title).txt


Question on data cleaning: how to deal with the many countries?   Tip: make this simpler by introducing fewer categories (continents for example).

Question on modeling: I would like you to fit a decision tree to this data.  To find the best hyper-parameters (such as max depth, etc... ) do a grid search with cross-validation (use SK-Learn documentation to find out how). 

The decision tree has a feature importance, use the sk learn documentation to understand its definition and plot it and explain what it means. 

Use a random forest regressor and follow the same steps.

No bias-variance trade-off
