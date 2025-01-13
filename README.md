# 🏠 **Airbnb Price Prediction Project**  

### *Leveraging Machine Learning to Predict Listing Prices*  

---

## 📖 **Project Overview**  
This project focuses on predicting Airbnb listing prices using historical data. The analysis aims to identify factors influencing pricing, such as location, property type, amenities, and customer ratings, while building a robust machine learning model for accurate predictions.  

By combining **data cleaning**, **EDA**, and **predictive modeling**, this project provides insights to hosts and stakeholders for optimizing pricing strategies.

---

## 🚀 **Key Features**  
- **Exploratory Data Analysis (EDA):** Uncovered trends and relationships between features such as location, reviews, and pricing.  
- **Data Cleaning:** Addressed missing values, handled outliers, and engineered new features like neighborhood popularity scores.  
- **Machine Learning Model:** Trained models to predict listing prices with a focus on interpretability and accuracy.  
- **Visualization:** Developed compelling visualizations to highlight correlations and model performance.  

---

## 📊 **Key Insights**  

### 1. **Location Matters**  
- Listings in central locations or popular neighborhoods command higher prices.  
- Proximity to tourist attractions significantly impacts pricing.  

![Price by Location](path/to/location_price_map.png)  

---

### 2. **Impact of Reviews and Ratings**  
- Properties with higher ratings and more reviews generally have higher prices.  
- However, extreme pricing for highly-rated properties may reduce booking frequency.  

![Reviews vs. Price](path/to/reviews_price_chart.png)  

---

### 3. **Property Type and Amenities**  
- Luxury properties and listings with premium amenities (e.g., pools, WiFi, parking) show a price premium.  
- Shared accommodations are consistently priced lower compared to private rentals.  

![Amenities vs. Price](path/to/amenities_price_chart.png)  

---

## 🧠 **Modeling Approach**  

### 1. **Data Preparation**  
- Encoded categorical variables (e.g., property type, neighborhood).  
- Scaled numerical features (e.g., square footage, review scores).  

### 2. **Models Evaluated**  
- Linear Regression  
- Random Forest Regressor  
- Gradient Boosting Machines  

### 3. **Best Model**  
- **Random Forest Regressor** achieved the highest performance with a **R² score of 0.85** and low mean absolute error (MAE).  

---

## 🛠️ **Technologies Used**  
- **Programming Language:** Python  
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Plotly  
- **Tools:** Jupyter Notebook  
- **Data Source:** Airbnb dataset  

---

## 🎯 **Challenges Encountered**  
- **Handling Missing Data:** Some key attributes like amenities and reviews had incomplete data. Imputation techniques were applied where appropriate.  
- **Outliers:** Extreme values in pricing skewed the model and were addressed through data preprocessing.  

---

## 📈 **Next Steps**  
- Implement advanced feature engineering to capture seasonality and dynamic pricing factors.  
- Explore deep learning models to enhance prediction accuracy.  
- Develop an interactive dashboard for Airbnb hosts to estimate listing prices in real-time.  

---

## 🤝 **Acknowledgments**  
Thanks to the Airbnb dataset providers for making this analysis possible. Appreciation to the team for their collaborative efforts in delivering actionable insights through this project.  

---

## 📬 **Contact**  
**Dhruv Shah**  
M.S. in Business Analytics, Boston University  
- Email: dhruv.shah@example.com  
- [LinkedIn](https://linkedin.com/in/dhruv-shah)  
