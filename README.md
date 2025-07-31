# Multiple_Linear_Regression
📘 Multiple Linear Regression – Economic Index Prediction
🧠 Project Overview
This project uses Multiple Linear Regression to predict an Economic Index Price based on two key macroeconomic indicators:

📉 Interest Rate

📊 Unemployment Rate

The model is built using Python and the scikit-learn library. It includes data preprocessing, visualization, model training, performance evaluation, and interpretation of results.

📁 Dataset
File: economic_index.csv

Features used:

interest_rate – Annual interest rate

unemployment_rate – Percentage of unemployed individuals in the economy

index_price – Target variable (economic index to be predicted)

Columns like Unnamed: 0, year, and month were removed during preprocessing.

⚙️ Technologies Used
Python 3

pandas

matplotlib & seaborn

scikit-learn

📊 Workflow Summary
Data Cleaning & Exploration

Removed unnecessary columns

Checked for null values

Visualized relationships using scatter plots and pairplot

Correlation matrix analysis

Feature Engineering

Selected interest_rate and unemployment_rate as features (X)

Target: index_price (y)

Preprocessing

Data split into training and testing sets (75%-25%)

Feature scaling using StandardScaler

Model Training

Trained a LinearRegression model on the scaled training data

Model Evaluation

Metrics used:

Mean Absolute Error (MAE)

Mean Squared Error (MSE)

Root Mean Squared Error (RMSE)

R² Score

Adjusted R² Score

Cross-validation using cross_val_score with 3 folds

Visualization

Regression lines

Actual vs Predicted comparison

📈 Sample Results (replace with your actuals)
Metric	Value
R² Score	0.89
Adjusted R²	0.88
MAE	9.25
MSE	125.7
RMSE	11.21

📂 File Structure
Copy
Edit
├── economic_index.csv
├── Multiple_Linear_reg.ipynb
├── README.md
🚀 Future Enhancements
Add more features (e.g., inflation, GDP growth)

Apply Ridge/Lasso/ElasticNet for regularization

Turn into a Streamlit web app

Perform residual analysis and improve interpretability

🔗 Author
Aryan Kashyap
This project showcases practical implementation of multiple linear regression on a real-world financial dataset. Ideal for beginners exploring supervised learning techniques.
