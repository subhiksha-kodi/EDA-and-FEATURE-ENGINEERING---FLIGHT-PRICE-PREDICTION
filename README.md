#✈️ Flight Price Prediction

##📌 Overview
This project focuses on forecasting flight ticket prices by analyzing historical flight data. It uses information like travel dates, airlines, routes, and flight durations to uncover pricing trends and deliver accurate predictions.

##📂 Datasets
Two Excel files are included:

data_train.xlsx – Historical flight details with prices, used for training the model.

test_set.xlsx – Flight details without prices; the model predicts prices for these entries.

##Key features include:
🗓️ Travel Date | 🛫 Departure & Arrival Times | 🌆 Origin & Destination | ⏳ Flight Duration | ✈️ Airline | 🔄 Stops | 💲 Ticket Price (training data only)

##🔍 Workflow Summary

##📥 Data Loading
Imported datasets and inspected for missing or inconsistent data.

##🧹 Data Preparation
Cleaned and transformed data, converting dates and categorical features for modeling.

##⚙️ Feature Engineering
Created additional features such as journey length and day of week to improve predictions.

##🤖 Model Development
Built regression models to learn the relationship between flight attributes and prices.

##🎯 Price Prediction
Used trained models to predict flight prices on the test dataset.
