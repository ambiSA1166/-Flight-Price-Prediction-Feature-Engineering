# ✈️ Flight Price Prediction – Feature Engineering

## 📌 Overview

This project focuses on transforming raw flight data into a structured format suitable for machine learning.
The main goal was to perform **feature engineering and preprocessing** to improve data quality and usability for predictive modeling.

---

## 📊 Dataset

The dataset contains flight-related information such as:

* Airline, Source, Destination
* Date of journey
* Departure & arrival time
* Duration
* Total stops
* Additional information
* Price *(target variable)*

---

## ⚙️ Key Feature Engineering

* **Date Processing**
  Extracted day, month, and year from journey date

* **Time Features**
  Extracted hour and minutes from departure and arrival time

* **Duration Handling**
  Converted duration into numerical format (hours & minutes)

* **Stops Encoding**
  Converted total stops into numerical values

* **Categorical Encoding**
  Applied Label Encoding to categorical features (Airline, Source, Destination, etc.)

* **Data Cleaning**
  Removed inconsistent records and handled missing values

---

## 🧾 Final Features

The processed dataset includes:

* Airline, Source, Destination
* Total_Stops, Additional_Info
* Date, Month, Year
* Arrival_hour, Arrival_min
* Dep_hour, Dep_min
* Duration_hour, Duration_min
* Price

---

## 🚀 Tech Stack

* Python
* Pandas
* NumPy
* Scikit-learn

---

## 💡 Key Takeaways

* Learned how to handle real-world messy data
* Improved understanding of feature engineering techniques
* Prepared dataset for machine learning models

---

## 🔮 Next Steps

* Perform Exploratory Data Analysis (EDA)
* Train ML models (Linear Regression, Random Forest, etc.)
* Hyperparameter tuning and evaluation

---

## 📎 Note

This project mainly focuses on **data preprocessing and feature engineering**, which are crucial steps in building effective machine learning models.

---

