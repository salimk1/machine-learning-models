<h1 align="center"><b>Machine Learning Models</b></h1>

## Table of Contents
+ Project Abstract
+ Repository Description
+ Acknowledgments 

## Project Abstract
The expected commute time is important for both commercial and individual drivers as it allows them to plan their day and avoid unforeseen delays. Our group analyzed previous Deerfoot Trail commute time and weather data to create Linear Regression (LR) and Decision Tree (DT) commute time prediction models. The models focus on the weekday rush hour. The big data framework was Apache Spark and the coding language was Python.

We compared the Root Mean Squared Error (RMSE) and accuracy of these models along with an existing Random Forest (RF) and baseline model based on the validation/test dataset. The results were close to each other, with the baseline model having the lowest accuracy and the DT having the highest accuracy. Similarly, the DT had the lowest RMSE and LR had the highest RMSE. The RMSE for RF fluctuated, sometimes it was higher, sometimes lower. Since the DT model had the best and most consistent results we continued to analyze this model. We created a scatter plot of the predicted and actual commute times as well as a sample prediction graph given a sample weather and time input.

## Repository Description
There are four files in this repository: 
+ `deerfoot_commute_times.csv` contains the Deerfoot Trail commute times from 6 am to 9 pm between September 21, 2013, and April 10, 2014 
+ `weather_data_01012013_12312013.csv` contains the weather data for Calgary for 2013
+ `weather_data_01012014_12312014.csv` contains the weather data for Calgary for 2014
+ `models.ipynb` is a Python notebook created in Spark and it contains the complete process of creating the LR and DT models 

## Acknowledgments 
We collaborated on this project with a team of five fellow university students. Portions of this project were adapted from external material provided to us by our professor at the University of Calgary.
