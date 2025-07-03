# IPL-Score-Predictions
IML project using Linear Regression to predict IPL match scores

This project focuses on predicting the **total runs scored by a batting team** in an Indian Premier League (IPL) cricket match using **Linear Regression**. The aim is to build a machine learning model that uses historical match data and relevant features to forecast match scores accurately.

Developed as part of the **Intelligent Machine Learning (IML)** course.

---

## 🔍 Problem Statement

> **Design and implement a predictive model** that takes match features such as team, venue, pitch and weather conditions, and player statistics to estimate the total runs scored in a given IPL match.

---

## 🎯 Objectives

- To apply linear regression to a real-world sports analytics problem
- To preprocess and engineer features from complex categorical and numerical data
- To evaluate and interpret the performance of a regression model
- To derive insights that can help in real-time decision-making in cricket

---

## 📊 Use Cases & Applications

- **Fantasy Cricket & Betting**: Enhance strategies based on predicted scores
- **Live Broadcasting**: Add analytical depth to commentary
- **Team Strategy**: Help franchises set realistic targets or chase strategies
- **Fan Engagement**: Power score prediction games on digital platforms
- **Analytics and Insights**: Aid researchers in cricket match trend analysis

---

## 📥 Input Features

| Feature                  | Description                                             |
|--------------------------|---------------------------------------------------------|
| `Venue`                 | Stadium/location of the match                          |
| `Batting Team`          | Team currently batting                                 |
| `Bowling Team`          | Team currently bowling                                 |
| `Batting Order`         | 1st innings or 2nd innings                             |
| `Previous Match Performance` | Team form and trends                          |
| `Pitch Conditions`      | Dry, grassy, flat, etc.                                |
| `Weather Conditions`    | Temperature, humidity, etc.                            |
| `Player Statistics`     | Averages, strike rates, recent form, etc.              |

---

## 🎯 Output

- **Total Runs Scored**: A numerical prediction of the total runs made by the batting team.

---

## 🔧 Technologies Used

- Python
- pandas, numpy
- matplotlib, seaborn
- scikit-learn
- Jupyter Notebook

---

## 🧠 Machine Learning Model

- **Algorithm Used**: Linear Regression
- **Why Linear Regression?**  
  It's effective for continuous numeric prediction and provides interpretable coefficients for feature impact.

---

## ⚙️ Process Workflow

1. **Data Collection**  
   Historical IPL match data from sources like Kaggle or Cricinfo

2. **Data Preprocessing**
   - Handling missing values
   - One-hot encoding for categorical variables
   - Scaling of numerical features

3. **Feature Engineering**
   - Extracting relevant player & team stats
   - Encoding contextual match details

4. **Model Training**
   - Using scikit-learn's `LinearRegression`
   - Splitting data into training/testing sets

5. **Model Evaluation**
   - Metrics used:
     - Mean Absolute Error (MAE)
     - Mean Squared Error (MSE)
     - Root Mean Squared Error (RMSE)
     - R-squared (R²)

6. **Prediction & Analysis**
   - Predict future match scores
   - Interpret model coefficients to find key features

---

## 📈 Results & Insights

- Key predictors included **venue**, **batting order**, and **recent player form**
- The model showed promising performance with an MAE of _X_ and RMSE of _Y_ (replace with your actual values)
- Linear regression provided interpretable relationships between features and scores

---

## ✅ Success Criteria

- Low prediction error compared to baselines
- Clear interpretability of model output
- A simple, reproducible notebook pipeline
- Potential for integration into real-world platforms or dashboards

---
