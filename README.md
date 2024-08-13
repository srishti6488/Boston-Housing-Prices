

🚀 **Project: Boston Housing Price Prediction Using Linear Regression** 🏡

🔍 **Objective:**  
Build a predictive model using linear regression to estimate housing prices in Boston based on various features.

📊 **Data Columns:**
- **crim:** Per capita crime rate by town.
- **zn:** Proportion of residential land zoned for lots over 25,000 sq.ft.
- **indus:** Proportion of non-retail business acres per town.
- **chas:** Charles River dummy variable (= 1 if tract bounds river; 0 otherwise).
- **nox:** Nitrogen oxides concentration.
- **rm:** Average number of rooms per dwelling.
- **age:** Proportion of owner-occupied units built before 1940.
- **dis:** Weighted mean of distances to five Boston employment centers.
- **rad:** Accessibility index to radial highways.
- **tax:** Property tax rate per $10,000.
- **ptratio:** Pupil-teacher ratio by town.
- **black:** Proportion of the population that is Black.
- **lstat:** Percentage of lower-status population.
- **medv:** Median value of owner-occupied homes in $1000s.

💡 **Process:**
1. **Data Preparation:**  
   - Dropped irrelevant columns like 'ID'.
   - Visualized relationships using scatter plots and heatmaps.
   
2. **Correlation Analysis:**  
   - Focused on how each feature relates to the target variable 'medv' (housing price).
   - Plotted pair plots to explore positive, negative, and zero correlations.

3. **Model Training:**
   - Used `train_test_split` to divide the data.
   - Trained a Linear Regression model and evaluated its performance using metrics like MAE, MSE, and RMSE.
   - Interpreted coefficients to understand the impact of each feature on housing prices.

📉 **Results:**  
   - **RMSE:** The model's average error indicates the prediction accuracy.
   - **Coefficient Analysis:** Positive or negative impacts of features like 'rm' (number of rooms) and 'nox' (nitrogen oxides concentration) on housing prices.

This was my first analysis using a machine learning method, and I’m eager to continue improving my skills and my English in future projects. 😊


#DataScience #MachineLearning #Python #LinearRegression #BostonHousing
