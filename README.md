
# MSDS: Case Study 2 - Predicting and Forecasting Bike Sharing Data 
Swee K Chew, Mallory Hightower

## Introduction
This project contains source code supporting analyses of predicting and forecasting counts of rental bikes by metro DC's bikeshare system named Capital Bikeshare. The goal of the project is to use a random forest model to predict the bike demand and apply different time series methods to forecast the 2017 data and determine which model performs the best. 

## Data Description

The 'bike_day_data.csv' data file is obtained from the UCI Machine Learning Repository, which has daily rental counts of bike sharing data and it is used to fit a random forest model. The remaining 25 files are the raw individual bike trip data files that are downloaded from the Capital Bikeshare company website to perform forecasting analyses. Those 25 files are not uploaded onto GitHub due to the maximum file size limitation. Instead, the monthly rental bike counts over time dataset that is extracted and aggregated from the source files is available as 'bike_cnt_overtime.csv' file. 

## Data Source Links

UCI Machine Learning Repository - https://archive.ics.uci.edu/ml/datasets/Bike+Sharing+Dataset
Raw data source - https://s3.amazonaws.com/capitalbikeshare-data/index.html

## Code structure

The analysis and conclusion are summarized in the *MSDS_6306_Case_Study_2_Report.pdf* file. Data sets can be found in the *data* folder. To compile the report to _HTML_ format please reference to the *MSDS_6306_Case_Study_2_Report.Rmd* file. 