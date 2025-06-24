# Price Prediction for Airbnb Listings

This project is part of an assessment to build a predictive model using a custom Artificial Neural Network (ANN) for estimating Airbnb listing prices. The project follows a structured pipeline including data exploration, cleaning, modeling, and evaluation.

## Task Objective

Predict the price per night of an Airbnb listing based on features like reviews, ratings, location, and amenities.

## Dataset Description

The dataset includes the following key fields:

* `id`, `host_id`, `host_name`
* Listing details: `name`, `address`, `features`, `amenities`, `checkin`, `checkout`
* Numerical fields: `rating`, `reviews`, `price`, `bathrooms`, `beds`, `bedrooms`, `toilets`, `studios`, `guests`
* Categorical fields: `country`

## Workflow

### 🔍 Step 1: Exploratory Data Analysis (EDA)

* Structure and missing values inspection
* Distribution analysis of price and other numerical features
* Correlation matrix and categorical feature exploration

### 🧹 Step 2: Data Cleaning

* Handle missing values and outliers
* Encode categorical features
* Normalize/standardize numerical features

### 🧠 Step 3: Model Creation

* Build a custom ANN model using Keras
* Evaluate initial accuracy and performance

### 📈 Step 4: Accuracy Improvement

* Use classification metrics, AUC-ROC, and confusion matrix
* Hyperparameter tuning and cross-validation
* Optional: Apply ensemble methods for better accuracy

## Tools & Libraries

* Python (Pandas, NumPy, Matplotlib, Seaborn)
* Scikit-learn
* TensorFlow/Keras
