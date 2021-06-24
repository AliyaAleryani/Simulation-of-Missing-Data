
Missing Data Generation
-----------------------
This folder includes a collection of 20 datasets from [UCI repository](https://archive.ics.uci.edu/ml/index.php) and each is represented in a separate subfolder. Each subfolder contains 12 scenarios of increasing missing data for one dataset. 

To create scenarios for testing with increasing missing data, some values in the training sets are removed completely at random as follows:  Firstly, 10\% (then 20\%, 50\%)  of the attributes are randomly selected to remove data with the following chosen rates 5%, 15%, 30% and 50% of the records, respectively. The table below summarises the experimental scenarios artificially created.

| Scenario#  | % Features selected | % Records affected by missing data |
| -----------| ------------------- | ------------- |
| Scenario1  | 10                  |5   |
| Scenario2  | 10                  |15  |
| Scenario3  | 10                  |30  | 
| Scenario4  | 10                  |50  |
| Scenario5  | 20                  |5   | 
| Scenario6  | 20                  |15  |
| Scenario7  | 20                  |30  |
| Scenario8  | 20                  |50  |
| Scenario9  | 50                  |5   |
| Scenario10 | 50                  |15  |
| Scenario11 | 50                  |30  |
| Scenario12 | 50                  |50  |


The name of each .csv file can be read as: 
DatasetName-training-%FeatureSelected-att-%RecordsAffectedByMissingData
