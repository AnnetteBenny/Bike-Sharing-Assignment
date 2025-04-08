# Bike-Sharing-Assignment

---

## Bike Sharing Demand Prediction using Multiple Linear Regression

This project aims to develop a **multiple linear regression model** to predict the daily demand for shared bikes, helping BoomBikes—a U.S.-based bike-sharing company—better prepare for post-pandemic recovery and growth.

### 🚲 Problem Overview  
BoomBikes has experienced a major revenue decline due to the COVID-19 lockdown. To recover and plan ahead, the company seeks to understand the factors influencing bike rental demand. With a rich dataset of daily bike usage along with weather and seasonal information, the goal is to:
- Identify the most significant factors influencing demand.
- Accurately model how these factors impact daily rentals.
- Use the insights to optimize strategy and meet customer needs.

### 📊 Data & Features  
The dataset contains variables related to:
- **Weather conditions** (e.g. temperature, humidity, windspeed)
- **Temporal features** (e.g. season, holiday, working day)
- **User types** (casual, registered)
- **Target variable**: `cnt` (total daily rentals)

Special attention is paid to:
- Converting ordinal-looking categorical variables (like `season` and `weathersit`) into actual categorical types.
- Retaining important binary indicators such as `yr` (year), which may reflect increasing popularity over time.

### 🔧 Approach  
1. **Data Cleaning & Preparation**: Handling categorical variables, interpreting time-based features, ensuring proper data types.
2. **Feature Engineering**: Identifying and selecting meaningful predictors.
3. **Model Building**: Constructing a multiple linear regression model to predict `cnt`.
4. **Model Evaluation**: Performing residual analysis and calculating **R-squared score** on the test set using `r2_score()` from `sklearn.metrics`.

### 📈 Business Impact  
Understanding demand drivers will allow BoomBikes to make data-driven decisions, optimize resource allocation, and position themselves competitively as demand rebounds. The model also serves as a blueprint for forecasting bike demand in new markets.

---
