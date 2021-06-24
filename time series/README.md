Missing Data Generation
-----------------------

This folder includes a collection of 4 time series from [UEA and UCR repository](http://www.timeseriesclassification.com/) and each is represented in a separate subfolder. Each subfolder contains 12 scenarios of increasing missing data for one dataset.

We remove sequences of consecutive values on the training set to create artificial datasets with missing data. We generate five scenarios of increasing missing value removal for each of the training datasets, assuming data are not recorded for a period of time. For each scenario and in each case in the training set, we simulate $5$ sequences of missing values (consecutive observations) of different lengths with no overlap, assuming missing data occurs completely at random (MCAR). 
Since the original datasets are sampled at different rates, we perform different simulations of increasing missing data for each individual dataset as follows.
