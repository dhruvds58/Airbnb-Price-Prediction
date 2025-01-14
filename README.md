# 🏠 **Airbnb Price Prediction Project**  

### *Analyzing and Predicting Airbnb Listing Prices*  

---

## 📖 **Project Overview**  
This project focuses on exploring and predicting the prices of Airbnb listings using factors like location, property type, availability, and reviews. Through **Exploratory Data Analysis (EDA)** and machine learning techniques, the goal was to uncover insights about price determinants and create a predictive model to estimate listing prices.

---

## 🚀 **Key Highlights**  

### 1. **Data Cleaning and Preprocessing**  
- Handled missing values in key features like `reviews_per_month` and `availability_365`.  
- Addressed outliers in `price` and other numerical columns to improve data quality.  
- Converted categorical features, such as `neighborhood` and `room_type`, into numerical representations for model compatibility.  

---

## 📊 **Key Insights from EDA**  

### 1. **Neighborhood Influences Price**  
Listings in popular neighborhoods tend to have higher average prices. Proximity to central locations and tourist spots significantly impacts pricing.  

### 2. **Seasonality in Pricing**  
Prices exhibit seasonal trends, with peaks during holidays and vacation periods.  

### 3. **Impact of Reviews**  
Properties with more reviews and higher ratings tend to be priced higher, indicating a correlation between customer trust and price.

---

## 🧠 **Modeling Process**  

### 1. **Data Preparation**  
- Standardized numerical features, such as `price` and `minimum_nights`.  
- Encoded categorical variables for use in machine learning models.

### 2. **Model Training and Evaluation**  
- Models tested:  
  - **Linear Regression:** A baseline model for interpretability.  
  - **Random Forest Regressor:** Captured non-linear relationships effectively.  

- **Best Model:**  
  The **Random Forest Regressor** achieved the best performance with the following metrics:  
  - **R² Score:** 0.78  
  - **Mean Absolute Error (MAE):** $30.20  

---

## 🔑 **Results and Insights**  
- **Neighborhood and property type** emerged as key predictors of listing price.  
- The machine learning model provides a foundation for Airbnb hosts to estimate competitive prices.  

---

## 🛠️ **Technologies Used**  
- **Programming Language:** Python  
- **Libraries:** Pandas, NumPy, Seaborn, Matplotlib, Scikit-learn  

---

## 🎯 **Challenges Encountered**  
1. **Data Quality Issues:** Missing values and outliers required extensive cleaning.  
2. **Feature Selection:** Balancing model complexity with the interpretability of features.  

---

## 📈 **Next Steps**  
- Expand the dataset to include listings from additional cities for broader insights.  
- Explore advanced modeling techniques to improve prediction accuracy.  
- Develop visual dashboards for better user interaction with the model results.  
