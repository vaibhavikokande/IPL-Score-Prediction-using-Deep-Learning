

# 🏏 IPL Score Prediction using Deep Learning
# 📌 Project Overview

The IPL Score Prediction using Deep Learning project aims to predict the final score of a team in an IPL (Indian Premier League) cricket match using historical match data and deep learning models.

Cricket score prediction is a real-world regression problem where multiple factors like batting team, bowling team, overs, runs, wickets, and recent performance affect the final outcome. This project applies Deep Learning techniques to analyze these factors and generate accurate score predictions.

# 🎯 Objective

* Predict the final IPL match score using Deep Learning

* Analyze how match features impact the score

* Build a regression model for sports analytics

* Demonstrate the use of AI in cricket analytics

# ❓ Problem Statement

In T20 cricket like IPL, predicting the final score during the match is challenging because:

* Game pace changes rapidly

* Wickets impact scoring rate

* Recent overs influence momentum

* Team combinations matter

The goal is to build a Deep Learning model that predicts the final total score based on current match conditions.

# 📂 Dataset Description

The dataset contains historical IPL match records with features such as:

* 🏟 Venue

* 🏏 Batting Team

* 🎯 Bowling Team

* 👤 Batsman

* 🎳 Bowler

* 📊 Current Runs

* ❌ Wickets Fallen

* ⏱ Overs Completed

* 🔥 Runs in Last 5 Overs

* ❌ Wickets in Last 5 Overs

* 👤 Striker Score

* 👤 Non-Striker Score

* 🎯 Target Variable: Final Total Score

# 🛠 Technologies Used

* Python

* Jupyter Notebook

* Pandas – Data handling

* NumPy – Numerical operations

* Matplotlib & Seaborn – Visualization

* Scikit-learn – Preprocessing

* TensorFlow / Keras – Deep Learning

# 🔄 Project Workflow
1️⃣ Data Collection

Historical IPL dataset loaded into the notebook.

2️⃣ Data Preprocessing

Removed unnecessary columns

Handled missing values

Encoded categorical variables

Converted data into model-friendly format

3️⃣ Exploratory Data Analysis (EDA)

Performed:

Correlation analysis

Heatmaps

Feature importance understanding

Trend visualization

Purpose: Understand which features influence the score.

4️⃣ Feature Engineering

Created meaningful features:

Runs in last 5 overs

Wickets in last 5 overs

Current run rate

Player contributions

5️⃣ Model Building (Deep Learning)

A neural network model was built using:

Input Layer

Hidden Dense Layers

Activation Functions (ReLU)

Output Layer for regression

6️⃣ Model Training

Data split into training & testing

Model trained using backpropagation

Loss function: Mean Squared Error (MSE)

Optimizer: Adam

7️⃣ Model Evaluation

Metrics used:

MAE (Mean Absolute Error)

MSE (Mean Squared Error)

R² Score

Lower error = Better prediction.

# 📊 Results

* Model successfully predicts final scores

* Captures match momentum patterns

* Shows good accuracy for real-time prediction


* 💡 Key Insights

* ✅ Overs and runs strongly impact prediction
* ✅ Recent 5-over performance matters a lot
* ✅ Wickets significantly reduce final score potential
* ✅ Player contribution affects score trends


# 📈 Applications

* Live match score prediction

* Cricket analytics platforms

* Sports betting analysis

* Broadcasting insights

* Team strategy planning

# 🔮 Future Improvements

* Use LSTM for time-series prediction

* Add real-time match API data

* Deploy as a web app

* Improve feature engineering

* Hyperparameter tuning
