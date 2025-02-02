# Disaster Response Pipeline Project

## Table of Contents
1. [Description](#description)
2. [Installation and requirements](#installation_and_requirements)
3. [Instructions](#instructions)
4. [Additional files](#additional_files)
5. [Example](#example)
6. [Acknowledgements](#acknowledgements)

<a name="descripton"></a>
## Description:
A stock price prediction algorithm that improves on the accuracy of the standerd moving average used for calculating stock price movements.

Different metrics such as price competitor price movements, volumes and price variation where taken into account along side loss aversion to understand of these play a impact market movements up to a week in the future (5 days as the market is open 5 days a week). 

This is measured over a month long period with a 5 days rolling window, measuring the average mae and mse over this time period to find the most accurate model/metrics over several iterations and variations.

The investigation process is below.

1. Import required packages
2. Extract stock prices
3. Missing data
4. Exploratory analysis
5. Auto regression
6. Excluded standard deviation
7. STD vs later trading price
8. Percentage changes
9. Loss aversion
10. Moving averages and time series analysis
11. Moving average
12. Exponential moving average
13. Variations of model and adjustments to the data
14. Variance inflation factor
15. Optimal model and metrics
16. Final notes

<a name="installation_and_requirements"></a>
## Installation and requirements:
Python version : 3.12.4

To gain the access the required packages, run the command below whilst in the same location as the requierments.txt folder:

```
pip install -r requirements.txt
```

Run the below command to clone the repository:

```
git clone https://github.com/Benedictgr97/Disaster-response-pipline.git
```

<a name="additional_files"></a>
## Additional files:

**Folder** - _app_
- **run.py** - Described above
- **Folder** -  _templates_ - HTML templates for the web application. 

**Folder** - _data_
- **ETL Pipeline Preparation.ipynb** - Experimentation to build out the process_data.py pipline with methodology included 
- **Response_db.db** - SQLlite Database created from process_data.py containing transformed data
- **disaster_categories.csv** - Categories for each disaster message 
- **disaster_messages.csv** - Real disater messages using for training the classification model
- **process_data.py** - Described above

**Folder** - _models_
- **ML Pipeline Preparation.ipynb** - Experimentation to build out the train_classifier.py model with methodology included 
- **XGB_pipeline.pkl** - Pickle file of XGB boost trained model
- **train_classifier.py** -  Described above

<a name="example"></a>
## **Example**: _Running each part_
1. Run the ETL pipline, if you have new data to train on, update the data/disaster_messages.csv data/disaster_categories.csv

![image](https://github.com/user-attachments/assets/2f92fce7-1c7a-4c8b-b975-18d0c05482a1)

2. Run the ML pilone that trains the classifier
   
![image](https://github.com/user-attachments/assets/04ac348e-5c45-49cc-87ac-25745e74ae63)
![image](https://github.com/user-attachments/assets/2aa41294-5595-4cce-b1a2-8fc95d841580)

3. Running run.py whilst in the app folder will give the below in browser

![image](https://github.com/user-attachments/assets/b80f1f40-7e78-4b18-a820-acbca38146a9)

4.Finally, entering a disaster response message to clarify will give the below

![image](https://github.com/user-attachments/assets/6d0ebe61-2015-4fa5-8d2f-a81dfd88613a)

<a name="acknowledgements"></a>
## Acknowledgements
- [Udacity](https://www.udacity.com/) : Providing the templates, outline and training for this course.
- [Figure Eight](https://www.appen.com/): Providing the disaster response data.




