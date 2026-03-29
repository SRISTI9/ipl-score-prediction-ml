# ipl-score-prediction-ml
Machine Learning model to predict IPL match scores using regression techniques

# 🏏 IPL Score Prediction using Deep Learning

## 📌 Overview

This project predicts the final score of an IPL match using machine learning and deep learning techniques based on real-time match features such as runs, wickets, overs, and player information.

---

## 🚀 Key Highlights

* Performed exploratory data analysis (EDA) on IPL dataset
* Encoded categorical features like teams, players, and venues
* Built a deep learning model using TensorFlow/Keras
* Evaluated performance using MAE and MSE metrics
* Visualized match trends and feature correlations

---

## 🧠 Tech Stack

* Python
* Pandas, NumPy
* Matplotlib, Seaborn
* Scikit-learn
* TensorFlow / Keras

---

## 📊 Dataset

* IPL historical match dataset
* Features used:

  * Batting Team
  * Bowling Team
  * Venue
  * Runs
  * Wickets
  * Overs
  * Batsman & Bowler

---

## ⚙️ Model Architecture

* Input Layer
* Dense Layer (512 neurons, ReLU)
* Dense Layer (216 neurons, ReLU)
* Output Layer (Linear)

Loss Function: Huber Loss
Optimizer: Adam

---

## 📈 Results

* Evaluated using:

  * Mean Absolute Error (MAE)
  * Mean Squared Error (MSE)
* Model learns match progression patterns and predicts final score based on live match conditions

---

## 📊 Exploratory Data Analysis

* Matches per venue
* Top batsmen by runs
* Top bowlers by wickets
* Feature correlation heatmap

---


## 📌 Future Improvements

* Compare with traditional ML models (Linear Regression, Random Forest)
* Add RMSE and R² evaluation metrics
* Hyperparameter tuning
* Deploy using Streamlit for real-time predictions

---

## 🙌 Author

R Sristi
