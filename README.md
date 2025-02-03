# Disaster Response Pipeline Project

## Table of Contents
1. [Description](#description)
2. [Installation and requirements](#installation_and_requirements)
3. [Model_output](#model_output)

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
git clone https://github.com/Benedictgr97/stock_prediction_v2.git
```

<a name="model_output"></a>
## Model output 
An example output is shown below, and the methodology will work the same for other stocks and competitors, although features and models may be adjusted to achieve more accurate results.

![image](https://github.com/user-attachments/assets/1295a218-d734-4312-a093-d46451f53e15)




## Acknowledgements
- [Udacity](https://www.udacity.com/) : Providing training for this course.
- [polygon.io](https://polygon.io/): used to pull in stock prices.
- [Market beat](https://www.marketbeat.com/stocks/NYSE/GLW/competitors-and-alternatives/#:~:text=The%20main%20competitors%20of%20Corning,%2C%20and%20ARM%20(ARM)): Used to find the top 5 competitors.




