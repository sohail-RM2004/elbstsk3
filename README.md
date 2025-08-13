# House Price Prediction — Linear Regression

A machine learning pipeline that predicts house prices based on property features such as area, bedrooms, bathrooms, location preferences, and amenities.

---

##  Steps Performed

### 1. **Data Loading & Cleaning**
- Loaded the dataset from a CSV file.
- Dropped the non-informative `index` column.

### 2. **Preprocessing**
- Encoded categorical features (`mainroad`, `guestroom`, `furnishingstatus`, etc.) into numerical format using **One-Hot Encoding**.

### 3. **Splitting Data**
- Split dataset into **80% training** and **20% testing** sets.

### 4. **Model Training**
- Used **`LinearRegression`** from `sklearn.linear_model` to train the model.

### 5. **Model Evaluation**
Evaluated model performance using:
- **Mean Absolute Error (MAE)**  
- **Mean Squared Error (MSE)**  
- **R² Score**
  
### 6. **Visualization**
![Actual vs Predicted Prices](https://github.com/user-attachments/assets/bdf02cd7-32fe-4c91-ba5f-84f6484e08c6)  
*Scatter plot comparing actual and predicted house prices.*

### 7. **Feature Importance**
- Printed model coefficients to understand the influence of each feature on house prices.

---

##  **Results**
- **MAE**: `970,043.40`  
- **MSE**: `1,754,318,687,330.66`  
- **R² Score**: `0.6529`

---

##  **Key Insights**
- Larger **area**, more **bathrooms**, and **preferred location** significantly increase house prices.  
- Features like **mainroad access**, **air conditioning**, and **furnishing status** also contribute positively.  
- The model serves as a **baseline**; performance can be improved with **feature engineering** or **advanced regression models**.



