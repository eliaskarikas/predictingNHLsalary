# predictingNHLsalary

This project was submitted as a final for the summer portion of Fundamentals of Data Science.

NHL contract information is a somewhat subjective process, and measuring the value of players across the league is a difficult process. 
Because of this we set out to create a regression algorithm to predict a cotinuous value (salary), to understand what statistical information 
most effects salary information, whether that be point totals, shot conversion, corsi performance, etc. Through creating this model, 
we wanted to create a generalized standard for determining players salaries based on statistical performance.

We sourced our data through data scraping capfriendly.com, and converted this data to a dataframe so it could be manipulated and further analyzed. 
We extracted features from our data using a DecisionTreeRegressor, finding the most optimal balance of features to drive model performance.
To obtain this goal we focused on testing various regression models such as Support Vector Machines, Multiple Linear Regression, Ridge, and Lasso, 
to determine what model would yield the best performance on our dataset. We first trained our data, and then fit this model to testing sets.

Final Project writeup can be accessed VIA <b>DS3000_FP4_Group15_2</b>.
This file contains all analysis, code, and visualizations.
Additional files show webscraping, data formatting, data files, etc.
