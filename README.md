# gAIety
# 🌍 World Happiness Report (2020-2024) - Streamlit Web App  

This project explores the **World Happiness Report (2020-2024)** and predicts **Healthy Life Expectancy** using machine learning. It also includes a **Streamlit web app** that displays happiness insights, predictions, and jokes for entertainment.

---

## 📊 Dataset Information  
The dataset is sourced from **Kaggle**:  
[World Happiness Report 2020-2024](https://www.kaggle.com/datasets/samithsachidanandan/world-happiness-report-2020-2024?select=2020.csv)  

It consists of data from **2020 to 2024**, covering multiple countries, with features representing different happiness indicators.

### **Dataset Columns & Description**  
| Column Name                     | Description |
|---------------------------------|-------------|
| `Country name`                  | Name of the country |
| `Happiness Rank`                | Rank of the country based on happiness score |
| `Happiness Score`               | Overall happiness score (0-10) |
| `Upperwhisker`                  | Upper confidence interval for happiness score |
| `Lowerwhisker`                  | Lower confidence interval for happiness score |
| `Economy (GDP per Capita)`       | GDP per capita (economic indicator) |
| `Social Support`                 | Extent of social support in the country |
| `Healthy Life Expectancy`        | Average healthy life expectancy (Target Variable) |
| `Freedom to make life choices`   | Perception of freedom in making life decisions |
| `Generosity`                     | Measure of generosity in society |
| `Perceptions of Corruption`      | Perception of government corruption |
| `Year`                           | Year of the data |

---

## 📂 Data Preparation & Exploration  

1. **Load all five CSV files (2020-2024)** into Pandas.
2. **Explore the datasets** to check for missing values, column names, and data consistency.
3. **Standardize column names** if they differ across years.
   
## 🛠 Data Cleaning & Preprocessing

1. Handle missing values (drop, impute, or interpolate as needed).
2. Convert categorical data into numerical (e.g., encoding Country name).
3. Normalize numerical values for better model performance.

## 📊 Exploratory Data Analysis (EDA)

Visualize trends over the years 
1. box plots
2. histograms
3. pair plot
4. skewness graph to see if the distribution is balanced

## 🎯 Machine Learning Model
1️⃣ Model Used: Random Forest Regressor, Linear Regression
A Random Forest Regression model was trained to predict Healthy Life Expectancy using all other features.

## 2️⃣ Model Performance
1. Mean Squared Error (MSE): 0.0109 for Random Forest Regressor and 0.0178 for Linear Regression
2. The low error indicates the model performs well in predicting Healthy Life Expectancy based on the given features.
3. r2 error is alos found

## Feature Importance Ranking is caluclated

## 🎨 Streamlit Web App
## Features of the App
1. **Home Page** - Displays famous happiness quotes from philanthropists.
2. **Predictions Page** - Allows users to select a country and predict Healthy Life Expectancy.
3. **Jokes Page** - Displays a random joke to entertain users.

## 📌 Future Improvements
1. More interactive visualizations (e.g., box plots, scatter plots).
2. Experiment with different ML models for comparison.
3. Cluster analysis to group countries based on happiness scores.

----
