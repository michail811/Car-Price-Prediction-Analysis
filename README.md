Car Price Prediction Analysis

This notebook explores the task of predicting car prices using linear regression techniques. The dataset used in this analysis is obtained from Kaggle.

Techniques Used
Linear Regression: Both ordinary least squares (OLS) regression using the statsmodels library and linear regression using scikit-learn are employed to model the relationship between input features and car prices.
Random Forest Regressor: A machine learning ensemble technique, the Random Forest Regressor, is applied to compare its performance with linear regression.

Data Preprocessing
Missing values are handled by dropping rows with null values.
Categorical features such as Fuel_Type, Seller_Type, Transmission, Owner, and Car_Name are converted to numerical representations using label encoding and dummy variable creation.
The dataset is split into training and testing sets, and features are standardized using StandardScaler.

Exploratory Data Analysis (EDA)
Visualizations are created to explore the distribution of the target variable (Selling_Price) and the histograms of numerical and categorical features.
Bar plots are generated to illustrate the distribution of fuel types, transmission systems, and ownership counts.

Feature Engineering
The 'Year' column is transformed into 'Age' by subtracting the year from 2024.
Dummy variables are created for categorical features, and the correlation matrix is visualized using a heatmap.

Model Evaluation
The analysis involves evaluating models using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), R-squared (R2), and Explained Variance Score (EVS).
The notebook explores the impact of Principal Component Analysis (PCA) on model performance by varying the number of components.

Cross-Validation
Cross-validation is performed to assess model performance using different numbers of PCA components.

Results
Results are summarized in a tabular format, showcasing the MAE for each model.
Visualizations illustrate the model performance with varying numbers of PCA components.

Conclusion
This analysis provides insights into predicting car prices using linear regression and random forest techniques. The comparison of models and exploration of PCA components contribute to understanding the trade-offs between model complexity and performance. The provided code and visualizations offer a comprehensive overview for further exploration and refinement of car price prediction models.
