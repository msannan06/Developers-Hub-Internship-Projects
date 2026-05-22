# DevelopersHub AI/ML Engineering Internship Tasks

This repository contains the projects and tasks completed during my AI/ML Engineering Internship at DevelopersHub Corporation.

## Task 1: Exploring and Visualizing a Simple Dataset

### 📌 Objective
To load, inspect, and analyze the classic Iris dataset using exploratory data analysis (EDA) techniques to understand data trends, distributions, and feature relationships.

### 📊 Dataset Used
* **Name:** Iris Dataset (loaded via Seaborn)
* **Features:** Sepal Length, Sepal Width, Petal Length, Petal Width, and Species (Setosa, Versicolor, Virginica).

### 🛠️ Libraries Used
* `pandas` for data manipulation and inspection.
* `matplotlib.pyplot` and `seaborn` for data visualization.

### 🔑 Key Results & Findings
* **Data Integrity:** The dataset contains 150 entries across 5 columns with zero missing (null) values, making it highly reliable for analysis.
* **Species Distinctness:** Visual plots confirm that the *Setosa* species forms a completely distinct cluster with significantly smaller petal lengths and widths compared to *Versicolor* and *Virginica*.
* **Feature Corellation:** A clear positive linear relationship is visible between petal length and petal width across all species.

## Task 2: Predict Future Stock Prices (Short-Term)

### 📌 Objective
To build a machine learning regression framework capable of estimating the next day's closing financial asset value using historical market markers.

### 📊 Dataset Used
* **Source:** Yahoo Finance (via `yfinance` API)
* **Ticker Analyzed:** AAPL (Apple Inc.)
* **Features Used:** Open, High, Low, Volume

### 🛠️ Models & Libraries Applied
* `scikit-learn` for Linear Regression training and splitting metrics.
* `yfinance` for automated historical data acquisition.

### 🔑 Key Results & Findings
* The Linear Regression model accurately mirrors directional trends with a strong baseline R2 metric.
* Feature checking indicates that the immediate day's high/low boundary thresholds act as the most significant weights for predicting immediate next-day variations.

## Task 3: Heart Disease Prediction (Classification)

### 📌 Objective
To configure a binary health analytics classifier capable of accurately segmenting high-risk cardiac vectors from standard metrics using machine learning diagnostic protocols.

### 📊 Dataset Used
* **Source:** UCI Processed Cleveland Heart Dataset
* **Target Mapping:** 0 (Healthy Control Baseline Value), 1 (Risk Group Present)

### 🛠️ Models Applied
* Logistic Regression classification framework utilizing dynamic threshold assignment evaluation profiles.

### 🔑 Key Results & Findings
* **Diagnostic Precision:** The confusion matrix metrics demonstrate robust true-negative classification rates, vital for mitigating medical misclassification.
* **Feature Weights:** Parameters including 'ca' (number of major vessels) and 'thal' display highly significant prediction weights during classification tasks.

## Task 6: House Price Prediction (Regression)

### 📌 Objective
To implement an advanced regression framework capable of analyzing real estate features (such as demographic data and geographic metrics) to accurately estimate property valuation.

### 📊 Dataset Used
* **Source:** California Housing Dataset (via Scikit-Learn)
* **Features:** Median Income, House Age, Average Rooms, Average Bedrooms, Population, Average Occupancy, Latitude, and Longitude.

### 🛠️ Models Applied
* Gradient Boosting Regressor (an ensemble learning method for optimizing regression accuracy).

### 🔑 Key Results & Findings
* **Model Accuracy:** The Gradient Boosting model successfully captured data non-linearities, resulting in low MAE and RMSE scores.
* **Economic Drivers:** Exploratory analysis confirmed that the median income of an area is the single strongest statistical predictor of overall property value.
