# Airbnb NYC Sales Data Analysis & Price Prediction

## 📌 Internship Project – Data Analytics
---

## 📖 Project Overview
This project focuses on analyzing **Airbnb New York City listings data** to understand key factors affecting listing prices and to build a **machine learning model** that predicts prices based on various features such as location, room type, availability, and reviews.

The project also includes an **interactive Streamlit web dashboard** to visualize insights and allow real-time price prediction.

---

## 🎯 Objectives
- Perform data cleaning and preprocessing
- Conduct exploratory data analysis (EDA)
- Identify key pricing factors
- Build a machine learning model for price prediction
- Create an interactive dashboard for insights and forecasting

---

## 📊 Dataset Description
- **Dataset Name:** Airbnb NYC Open Data (2019)
- **Source:** Kaggle
- **Records:** 48,895 listings
- **Format:** CSV

### Key Features Used:
- `neighbourhood_group`
- `room_type`
- `price`
- `minimum_nights`
- `number_of_reviews`
- `reviews_per_month`
- `availability_365`

**Target Variable:** `price`

---

## 🛠️ Tools & Technologies Used
- **Python**
- **Pandas & NumPy** – Data handling
- **Matplotlib & Seaborn** – Data visualization
- **Scikit-learn** – Machine learning
- **Streamlit** – Interactive web application
- **GitHub** – Version control

---

## 🔍 Data Cleaning & Preprocessing
- Removed irrelevant columns (`name`, `host_name`, `last_review`)
- Handled missing values in `reviews_per_month`
- Removed listings with zero price
- Prepared categorical and numerical features for modeling

---

## 📈 Exploratory Data Analysis (EDA)
Key insights discovered:
- Manhattan has the highest average listing prices
- Entire homes/apartments are priced higher than private rooms
- Listings with higher availability tend to have lower prices
- Reviews indicate popularity but do not always increase price

---

## 🤖 Machine Learning Model
- **Model Used:** Random Forest Regressor
- **Reason:** Handles non-linear relationships and performs well on structured data
- **Features:** Location, room type, reviews, availability, minimum nights

### Evaluation Metrics:
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

