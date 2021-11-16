# DSTS_FinalProject
This repository dedicated to the Final Project of the Data Science Technology and Systems unit, Semester 2, 2021.

The problem: Predicting Airplane Delays

The goals of this project are:
- Process and create a dataset from downloaded ZIP files
- Exploratory data analysis (EDA)
- Establish a baseline model and improve it
- Using Tableau to build a dashboard
- Using Amazon Sagemakers to train, validate and deploy the models

- Introduction to business scenario
A travel booking website that is working to improve the customer experience for flights that were delayed. The company wants to create a feature to let customers know if the flight will be delayed due to weather when the customers are booking the flight to or from the busiest airports for domestic travel in the US. The aim of this project is to solve a part of this problem by leveraging machine learning to identify whether the flight will be delayed due to weather. The dataset is of on-time performance of domestic flights operated by large air carriers, is to be used train a machine learning model to predict if the flight is going to be delayed for the busiest airports.

- Dataset
The provided dataset contains scheduled and actual departure and arrival times reported by certified US air carriers that account for at least 1 percent of domestic scheduled passenger revenues. The data was collected by the Office of Airline Information, Bureau of Transportation Statistics (BTS). The dataset contains date, time, origin, destination, airline, distance, and delay status of flights for flights between 2014 and 2018.
The data are in 60 compressed files, where each file contains a CSV for the flight details in a month for the five years (from 2014 - 2018). The data can be downloaded from this link: [https://ucstaff-my.sharepoint.com/:f:/g/personal/ibrahim_radwan_canberra_edu_au/Er0nVreXmihEmtMz5qC5kVIB81-ugSusExPYdcyQTglfLg?e=bNO312]. Please download the data files and place them on a relative path. Dataset(s) used in this assignment were compiled by the Office of Airline Information, Bureau of Transportation Statistics (BTS), Airline On-Time Performance Data, available with the following link: [https://www.transtats.bts.gov/Fields.asp?gnoyr_VQ=FGJ].

- Project contents:
- "onpremises" file contains code to read, pre-process, EDA, and modelling the data, along with the commands to bush the files to the repository and the link to the Tableau dashboard.
- "oncloud" file contains code to train, validate, and deploy two classifiers on the pre-processed data.
- "raw_data" a folder contains the raw dataset.
- "All_data_files" a folder contains the dataset after unzipping.
