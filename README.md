# ✈ Flight Price Prediction – EDA & Feature Engineering

## 📌 Overview
This project aims to analyze and predict flight ticket prices based on various factors such as airline, source, destination, date of journey, and more.  
We perform *Exploratory Data Analysis (EDA), **Feature Engineering, and **Preprocessing* to prepare the dataset for machine learning models.

The analysis helps in:
- Understanding the factors affecting flight prices
- Building a clean dataset ready for modeling
- Identifying trends and patterns in ticket pricing

---

## 📂 Dataset
- *Source:* Publicly available dataset from Kaggle / other sources
- *Key Columns:*
  - Airline – Name of the airline
  - Date_of_Journey – Date of flight
  - Source & Destination – Airports
  - Route – Flight path
  - Dep_Time & Arrival_Time – Departure and arrival times
  - Duration – Total travel time
  - Total_Stops – Number of stops
  - Price – Ticket price (Target variable)

---

## 🔍 Steps Performed

### 1. *Exploratory Data Analysis (EDA)*
- Checked data types, null values, and duplicates
- Visualized categorical and numerical features
- Studied correlation between features and ticket prices
- Identified outliers

### 2. *Data Cleaning*
- Handled missing values
- Removed irrelevant features
- Converted date/time columns into separate day, month, hour, and minute features

### 3. *Feature Engineering*
- Extracted *Journey Day* & *Month*
- Converted *Duration* into minutes
- Encoded categorical variables (OneHotEncoder, Label Encoding)
- Handled ordinal features like Total_Stops

### 4. *Data Preprocessing*
- Normalized numerical features
- Created final dataset ready for machine learning

---

## 📊 Tools & Libraries Used
- *Python*
- *Pandas* – Data manipulation
- *NumPy* – Numerical computation
- *Matplotlib* & *Seaborn* – Data visualization
- *Scikit-learn* – Encoding & preprocessing

---

## 📈 Results
- Clean, preprocessed dataset ready for modeling
- Insights into flight price trends based on:
  - Airlines
  - Travel month
  - Duration & Stops
- Found strong influence of airline type and total stops on ticket price

---

## 🚀 Future Scope
- Implement multiple ML algorithms (Random Forest, XGBoost, etc.)
- Hyperparameter tuning for better accuracy
- Build a web app for live flight price prediction

---

## 🛠 How to Run
1. Clone this repository:
   ```bash
   git clone [https://github.com/username/Flight-Price-Prediction.git](https://github.com/subhiksha-kodi/EDA-and-FEATURE-ENGINEERING---FLIGHT-PRICE-PREDICTION)
   cd Flight-Price-Prediction
