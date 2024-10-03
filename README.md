# Assignment: Predicting Power Load Using Deep Learning
<hr>

## Designed by

Prof. Jiehan Zhou

jiehan.zhou@ieee.org 

Shandong University of Science and Technology 

## Completed by

Ayub Ali Emon

202486060005@sdust.edu.cn

Phoutthavong Phonesamay

202486060004@sdust.edu.cn

# ABSTRACT
<hr>

In this study, we employed a Long Short-Term Memory (LSTM) model to predict the energy load data based on historical energy usage and meteorological data. The load data was collected from Arizona State University’s Tempe campus and meteorological data from the National Renewable Energy Laboratory. Our goal was to accurately forecast energy consumption, leveraging time-series modeling techniques. We have chosen LSTM to address the challenge of fluctuating energy loads in large-scale facilities.
After several model iterations, hyperparameter tuning, and feature selection, we achieved a final Mean Absolute Percentage Error (MAPE) of 1.99% and a Root Mean Squared Error (RMSE) of 9606.14 KW. These results demonstrate the model's strength in learning patterns from the input features and predicting future energy loads with minimal error. Despite challenges with initial flat predictions, adjustments in feature engineering, and sequence length we have significantly improved the model’s performance.
This report outlines the methodology, model development process, challenges encountered, and final results, providing insights into using LSTM models for time-series prediction in energy management. 


## Final Result

<center>

![Evaluation](/report/images/evaluation.png)

</center>