# mlops-automl-pipeline
mlops course project - an automatic ml pipeline for a regression model improvement (tabular datasets)

IDEAS for the automatic step:

1. Data drift detector (calculate stats on columns and their distribution, save as metric and define a threshold for alert)
2. auto feature selection by importance / Shapely
3. Normalization techniques
4. Missing Values ratio 
5. Auto bias detector (e.g. gender bias)
6. 

Pipeline:
1. Have a configuration file as input to the python script: one for each model and dataset, that will define the categorical and numerical features
2. the metrics
