# Project 3

This analysis will look at Buffalo 311 data. The beginning date is January 1, 2020 and runs all the way through today (May 10th). 

Calls are usually in the hundreds or couple of hundreds each day during the week but drop down at the weekend.

There will also be a forecast created using Prophet that cuts the end date of the dataframe at December 31st, and forecasts 311 calls for the next 24 months.

As we see in the modeling, calls for the next 24 months will typically remain in the hundreds but you can see a slight upward trend in the number of calls in the prediction. 

A regressor (United States holidays) was also added, and as seen, there does not to be any strong difference other than the amount of calls on a specific holiday is very minimal, but dates around them and in the year do not change much.
