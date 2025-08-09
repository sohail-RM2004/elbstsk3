<h1> Steps Performed </h1>

Data Loading & Cleaning

Loaded the dataset from CSV file.

Dropped index column (non-informative).

Preprocessing

Encoded categorical features (mainroad, guestroom, etc.) into numerical format using One-Hot Encoding.

Splitting Data

Split the dataset into training (80%) and testing (20%) sets.

Model Training

Used LinearRegression from sklearn.linear_model to train the model on the training set.

Model Evaluation

Evaluated performance using:

Mean Absolute Error (MAE)

Mean Squared Error (MSE)

R² Score

Visualization

<img width="554" height="455" alt="image" src="https://github.com/user-attachments/assets/bdf02cd7-32fe-4c91-ba5f-84f6484e08c6" />

Created Actual vs Predicted price scatter plot to assess model fit.

Feature Importance

Printed model coefficients to understand the effect of each feature on house price.

<h3> Results </h3>
MAE: 970043.4039201636

MSE: 1754318687330.6638

R² Score: 0.6529242642153184

<h3> Key Insights </h3>
Larger area, higher number of bathrooms, and preferred location significantly increase house prices.


Features like mainroad access, air conditioning, and furnishing status also contribute positively.

The model provides a baseline predictive performance that can be improved with feature engineering or advanced models.
