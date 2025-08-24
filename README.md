Car Price Prediction:
This project predicts the selling price of used cars based on features like year, fuel type, kilometers driven, transmission type, and more.
The analysis uses both Linear Regression and Random Forest Regressor to compare performance.

Features:
1. Downloaded and cleaned used car dataset
2. Performed feature engineering and encoding of categorical variables
3. Standardized numerical features for better model performance

Trained two models:
1. Linear Regression
2. Random Forest Regressor
3. Compared models using MAE, RMSE, and R² Score
4. Visualized actual vs predicted car prices

Project Structure:
1. Notebook/Script – Main code with data preparation, training, and evaluation
2. Dataset – Used car price dataset from Kaggle
3. Visualizations – Scatter plot of actual vs predicted prices

Results:
1. Linear Regression gave baseline performance.
2. Random Forest performed better with higher accuracy and lower error values.
3. Scatter plot shows Random Forest predictions closely match actual selling prices.

Tech Stack:
1. Python
2. Pandas, NumPy
3. Scikit-learn
4. Matplotlib, Seaborn

Future Work:
1. Tune Random Forest with hyperparameter optimization
2. Try advanced models like Gradient Boosting or XGBoost
3. Build a Streamlit web app for live car price prediction

Author:
Developed by AMNA KHAN
