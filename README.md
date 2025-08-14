✈️ **FLIGHT PRICE PREDICTION**

📌 **OVERVIEW**  
This project focuses on forecasting flight ticket prices by analyzing historical flight data. It uses information such as travel dates, airlines, routes, flight durations, and stopovers to uncover pricing trends and deliver accurate predictions. The goal is to help travelers and businesses better understand price fluctuations and optimize purchasing decisions.

📂 **DATASETS**  
Two Excel files are included:

- **data_train.xlsx** – Contains historical flight details along with actual ticket prices; used to train and validate prediction models.  
- **test_set.xlsx** – Contains flight details without prices; the trained model will predict ticket prices for these entries.

**KEY FEATURES INCLUDE:**  
Travel Date | Departure & Arrival Times | Origin & Destination | Flight Duration | Airline | Number of Stops | Ticket Price (training data only)

🔍 **WORKFLOW SUMMARY**

📥 **DATA LOADING**  
Imported datasets and performed initial inspection for missing values, inconsistencies, and data types.

🧹 **DATA PREPARATION**  
Cleaned and preprocessed data by handling missing values, converting categorical variables, and engineering date/time features.

⚙️ **FEATURE ENGINEERING**  
Created additional variables such as journey length in hours, day of the week, and whether the flight is on a weekend or holiday to improve model performance.

🤖 **MODEL DEVELOPMENT**  
Experimented with regression algorithms including Linear Regression, Random Forest, and Gradient Boosting to predict flight prices accurately.

🎯 **PRICE PREDICTION**  
Applied the best-performing model to the test dataset and generated price predictions to support decision-making.

