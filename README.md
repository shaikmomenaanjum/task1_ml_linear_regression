# task1_ml_linear_regression
Machine Learning project that predicts California house prices using Linear Regression, pandas, scikit-learn, and data visualization techniques.
Build & Evaluate a Linear Regression Model (House Price Predictor)
Submitted by: Momena Anjum
Introduction
The goal of this project is to predict California house prices using a Linear Regression model. The California Housing dataset was used because it contains useful information about houses and neighborhoods. This project helped demonstrate the basic machine learning process from loading data to evaluating model performance.
Exploratory Data Analysis (EDA)
The dataset was examined using summary statistics and visualizations. No missing values were found. A histogram showed that most house prices are concentrated in the lower and middle ranges, while a heatmap revealed relationships between variables. Median Income (MedInc) had the strongest positive correlation with house prices (0.69). Population and Average Occupancy showed very weak relationships with the target variable.
Model Training and Evaluation
The dataset was split into 80% training data and 20% testing data. A Linear Regression model from scikit-learn was trained and evaluated using standard regression metrics.
Metric	Value	Meaning
MAE	0.5332	Average prediction error
MSE	0.5559	Mean squared error
RMSE	0.7456	Typical prediction error
R²	0.5758	Explains 57.58% of variance
The results indicate that the model provides a reasonable baseline for house price prediction. The Actual vs Predicted graph shows that predictions become less accurate for expensive houses, partly because the dataset caps values around $500,000.
Possible Improvements
Future improvements may include feature engineering, adding more housing-related variables, and testing advanced algorithms such as Random Forest Regression or Gradient Boosting. These approaches may capture non-linear relationships and improve prediction accuracy.
Conclusion
This project successfully demonstrated the complete machine learning workflow using the California Housing dataset. Linear Regression produced a solid baseline model and provided valuable experience in data analysis, visualization, model training, and evaluation.
