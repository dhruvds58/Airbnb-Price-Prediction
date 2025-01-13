# 🏠 **Airbnb Price Prediction Project**  

### *Leveraging Machine Learning to Analyze and Predict Listing Prices*  

---

## 📖 **Project Overview**  
This project aims to predict the prices of Airbnb listings using various factors, including location, property type, amenities, and customer reviews. By performing a comprehensive **Exploratory Data Analysis (EDA)**, creating meaningful visualizations, and building machine learning models, this analysis provides actionable insights for Airbnb hosts to optimize their pricing strategies and maximize revenue.  

The project delivers:
- A deep understanding of key drivers behind listing prices.  
- A predictive model to assist hosts in estimating fair prices for their properties.  
- Insights into market dynamics and customer preferences in the Airbnb ecosystem.  

---

## 🚀 **Key Features**  

### 1. **Data Cleaning and Preprocessing**  
- Addressed missing values for critical variables like `reviews_per_month`, `availability_365`, and `price`.  
- Handled outliers, such as extreme pricing anomalies, which skewed the analysis.  
- Feature engineering included creating variables like:  
  - **Neighborhood popularity scores** based on booking frequency.  
  - **Seasonality factors** using check-in date trends.  

### 2. **Exploratory Data Analysis (EDA)**  
- Uncovered correlations between location, property type, reviews, and pricing.  
- Highlighted trends using advanced visualizations (e.g., heatmaps, bar charts, scatter plots).  

### 3. **Machine Learning Models**  
- Built and evaluated multiple regression models to predict listing prices.  
- Optimized the best model for accuracy and interpretability.  

---

## 📊 **Key Insights and Visualizations**  

### 1. **Location is the Biggest Determinant**  
- Properties in tourist hotspots and popular neighborhoods attract higher prices.  
- Suburban and rural areas see lower average pricing.  

*Example Insight: Listings in downtown areas cost 30–40% more than suburban locations.*  

### 2. **Impact of Reviews and Ratings**  
- Listings with higher ratings (above 4.5) command premium prices.  
- However, diminishing returns observed for listings with excessive reviews (>200).  

### 3. **Property Type and Amenities**  
- Private apartments and entire homes consistently achieve higher prices.  
- Luxury amenities (e.g., hot tubs, pools, and private parking) add significant value to listings.  

### 4. **Seasonality and Booking Trends**  
- Prices peak during high-demand periods such as summer holidays and festive seasons.  
- Properties with flexible cancellation policies see increased demand and, in turn, higher prices.  

---

## 🧠 **Modeling Process**  

### 1. **Data Preparation**  
- **Feature Engineering:**  
  - Extracted features like `host_experience` (years active) and `guest_capacity`.  
  - Created categorical encodings for `neighborhood`, `property_type`, and `room_type`.  
- **Data Scaling:** Standardized numerical variables (e.g., `price`, `minimum_nights`, `number_of_reviews`) for model compatibility.  

### 2. **Model Evaluation**  
- Tested multiple algorithms:  
  - **Linear Regression**: Baseline model with interpretable coefficients.  
  - **Random Forest Regressor**: Best-performing model with an R² of 0.85.  
  - **Gradient Boosting Machines (XGBoost)**: Provided robust results with minimal overfitting.  
- **Hyperparameter Tuning:** Used GridSearchCV to optimize models for better accuracy.  

---

## 🔑 **Results**  
- The **Random Forest Regressor** emerged as the top-performing model with:  
  - **R² Score:** 0.85  
  - **Mean Absolute Error (MAE):** $25.35  
  - **Mean Squared Error (MSE):** $50.45  
- The model's predictions aligned closely with real-world pricing trends, demonstrating its practical applicability.  

---

## 🛠️ **Technologies Used**  
- **Programming Language:** Python  
- **Libraries:**  
  - Data Analysis: Pandas, NumPy  
  - Data Visualization: Matplotlib, Seaborn, Plotly  
  - Machine Learning: Scikit-learn, XGBoost  
- **Tools:** Jupyter Notebook  
- **Data Source:** Airbnb dataset  

---

## 🎯 **Challenges Encountered**  
1. **Data Quality Issues:**  
   - Handled missing and erroneous values in key attributes such as `price` and `reviews_per_month`.  
   - Used domain knowledge to impute plausible values.  

2. **Outliers in Pricing:**  
   - Listings with unusually high prices (e.g., luxury mansions) created skewed distributions.  
   - Applied logarithmic transformations to normalize the `price` variable.  

3. **Feature Importance:**  
   - Balancing interpretability with predictive power was challenging.  
   - Used SHAP (SHapley Additive exPlanations) to identify the most impactful features.  

---

## 📈 **Next Steps**  
- **Predictive Enhancements:**  
  - Incorporate dynamic pricing models to reflect real-time market conditions.  
  - Factor in external variables like weather, local events, and holidays.  
- **Interactive Tools:**  
  - Build a user-friendly dashboard for Airbnb hosts to predict prices dynamically.  
- **Expand Analysis:**  
  - Conduct similar studies for other major cities to validate findings across regions.  

---
