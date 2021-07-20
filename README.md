# ACRA BUSINESS REGISTRATION

The number of business entities registered with the Accounting and Corporate Regulatory Authority (ACRA). Business entities refer to companies, sole proprietorships & partnerships, limited liability partnerships, limited partnerships and public accounting firms.The dataset was obtained from the website of [Data.gov]. 

## INSIGHTS
To shows that entity_status_description 'live' has the most data findings in order to get more deep findings. Using the importants and high dataset which needed the most

## Problem Statement
Overall Singapore was a well-known as a business hub for southeast Asia, but were the business in Singapore really Serviving??
![image](https://user-images.githubusercontent.com/74976732/126266711-4c01b85c-3e55-44a0-9bb8-e50d1b35b4df.png)

## Problem Description 
* Before starting actual analysis, a lot of cleaning needs to be done on the data. 
* There are also some missing values which needs to be replaced. 
* import all the files, combine all the csv files into a dataframe
* slice the postal code to 2 digit, mapping created csv files and merge to find to find region location

## Summary of Dataset
#### 1. Evaluation
* There are 2 types of calendar from the dataset and we have drop the "Calendar" due to the financial forecasting will be using "Fiscal" for further insights. 
* The most important attributes were Organization Group, Department, Job, Salaries and Benefits. Total Compensation is the target of our prediction model. 


[Data.gov]:https://data.gov.sg/dataset/entities-with-unique-entity-number?resource_id=39201285-b73e-487a-a971-3a12d34ab8d9
