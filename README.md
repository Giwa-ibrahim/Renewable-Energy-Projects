# Welcome to Giwa Ibrahim's Portfolio

## About Me
I am a recent graduate of Ladoke Akintola University of Technology (LAUTECH), where I studied Electronic and Electrical Engineering. Within one year of experience in the Data Science field, I have undertaken several professional courses covering the basics of Data Analytics and Machine Learning. To date, I have successfully completed two projects related to Renewable Energy, which align with my field of study.

## [Project 1: Wind Speed Prediction using LSTM Model](https://github.com/Giwa-ibrahim/Giwa_Portfolio/blob/main/Wind_Speed_Prediction_Model.ipynb)

This was a project I did for my Undergraduate Final year project.

Duration: 6 months (between Jan 2023 and July 2023).

**Project Overview**
* Data was collected from the Nigerian Meteorological Agency (NIMET) and contained 10 years (2007-2018) of wind speed dataset from Kano state, Nigeria.
* Preprocessing steps such as Data cleaning and feature engineering were done.
* LSTM, ANN, GRU, and SimpleRNN models were used to train the models where LSTM outperformed other models based on the error metrics.
*  The LSTM hyperparameters such as the number of neurons, layers, timesteps, number of engineered features, optimizers, etc,  were iterated to optimize the accuracy of the model and were finally compared with other neural network variants.

![](/Performance%20of%20LSTM.PNG)

![](/Comaprison%20of%20LSTM%20with%20other%20models%20plot.png)

## [Project 2: Energy Consumption Price Model](https://github.com/Giwa-ibrahim/Giwa_Portfolio/blob/main/Energy_Consumption_Price_Model.ipynb)

This was a virtual Hackathon project organized by Optimus AI Labs.

Duration: 5 days (between April 8th and April 12th, 2024).

**Project Scope**

Develop a User interface model for forecasting energy consumption for buildings, areas, or utilities, as well as predicting renewable energy output from sources such as wind turbines or solar panels, considering weather conditions and environmental factors.

**Project Overview**
* The dataset was sourced from Kaggle, which comprises two extensive sets spanning four years (2015-2018). It includes Consumption and Generation data, and Weather Features data from the five largest cities in Spain.
* Preprocessing techniques, such as removal of unnecessary columns and missing values, renaming of columns, merging of the both datasets via the date-time columns, checking for outliers, and feature engineering by transforming the date-time into hour, day, month and year columns.
*  Trained the dataset with the Random Forest (RF) Regression model which involves experimenting with various Machine Learning (ML) models including  LSTM, Random Forest, XGBoost, Gradient Boost, and AdaBoost, but RF model produced the least error metric with a Root Mean Square Error (RMSE) of 3.301.
*  The model was deployed using Streamlit library to ensure an easy access user interface as shown below.

![](/Performance%20of%20Energy%20Consuption%20Predicted%20and%20actual%20price.png)

### The User Interface Model Testing
![](/Model%20Deploy%20(1).png)
![](/Model%20Deploy%20(2).png)


