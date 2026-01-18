# california-housing-ML-model
Machine learning project for predicting California housing prices using tabular data. Includes preprocessing, feature encoding, RandomForest model training, and performance evaluation.
# 🏡 Housing Price Prediction — Machine Learning 

This project focuses on predicting housing prices in California using machine learning techniques on tabular data. The dataset includes features such as median income, number of rooms, house age, population, and geographic location, combined to estimate median house values.

---

## 📌 Project Objectives

✔ Analyze California housing data  
✔ Clean and preprocess the dataset  
✔ Encode categorical attributes (e.g., ocean proximity)  
✔ Train a regression model for price prediction  
✔ Evaluate model performance on unseen data  

---

## 📂 Dataset

- Dataset: California Housing Data (CSV format)
- Target Variable: `median_house_value`
- Input Features:
  - Median Income
  - Total Rooms
  - Total Bedrooms
  - Population
  - Households
  - Latitude / Longitude
  - Ocean Proximity (Categorical)

---

## 🔧 Methods & Techniques Used

- Data Cleaning & EDA
- Feature Engineering
- One-Hot Encoding (for categorical variables)
- Train/Test Split (80/20)
- Regression Modeling using:
  - RandomForestRegressor

---

## 📊 Model Performance

| Metric | Result |
|--------|--------|
| RMSE | ~48,000 |
| MAE | ~31,600 |
| R² Score | ~0.82 |

The model demonstrates strong predictive performance, capturing ~82% of the variance in housing prices.

---

## 🛠 Tech Stack

- Python
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib / Seaborn (optional, for visualization)
- Jupyter / Google Colab

---

## 🚀 Key Insights

- Median income is the most influential feature for predicting house prices
- Geographical attributes significantly impact housing value
- Tree-based models perform well on tabular regression tasks

---

## 🎯 Project Outcome

This project builds a complete end-to-end ML pipeline suitable for:

✔ Academic work  
✔ Machine learning portfolio  
✔ GitHub showcase  
✔ Data science practice  

---


