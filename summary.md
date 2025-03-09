Here's a concise summary of your code:

---

### **Admission Prediction Using Machine Learning**

This project analyzes admission chances using machine learning models based on academic and profile-related features.

#### **Key Steps:**

1. **Data Loading & Exploration**

   - Loaded the dataset and examined structure, statistics, and missing values.
   - Renamed columns for better readability.

2. **Data Visualization**

   - Plotted distributions of GRE, TOEFL, CGPA, and other features.
   - Analyzed relationships using scatter plots, box plots, and a correlation heatmap.

3. **Feature Engineering & Data Cleaning**

   - Identified and handled missing values.
   - Dropped unnecessary columns (e.g., Serial No.).

4. **Model Selection & Training**

   - Used **GridSearchCV** to find the best model among **Linear Regression, Lasso, SVR, Decision Trees, Random Forest, and KNN**.
   - **Linear Regression** was selected as the best-performing model.

5. **Model Evaluation**
   - Standardized data using `StandardScaler`.
   - Evaluated model performance using **R² score (0.8215), MAE (0.0417), MSE, and RMSE (0.054)**.

#### **Conclusion:**

The model predicts admission probability with **82.15% accuracy**. CGPA, GRE, and TOEFL scores were found to be the most significant predictors. Further improvements can be made with more feature engineering or advanced models.
