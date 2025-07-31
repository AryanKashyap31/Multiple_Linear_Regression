# Multiple_Linear_Regression
📘 Multiple Linear Regression – Economic Index Prediction
🧠 Project Overview
This project demonstrates the use of Multiple Linear Regression to predict the Index Price of the economy based on two key financial indicators:

📉 Interest Rate

📊 Unemployment Rate

It includes data preprocessing, model training, performance evaluation, and visualization of the relationships among features.

📁 Dataset
The dataset used in this project is stored in economic_index.csv, which includes the following columns:

interest_rate

unemployment_rate

index_price

Note: Columns like Unnamed: 0, year, and month were dropped during preprocessing.

⚙️ Technologies Used
Python 3

pandas, numpy

matplotlib, seaborn

scikit-learn

📊 Workflow
Data Cleaning

Removed irrelevant columns (Unnamed: 0, year, month)

Checked for null values

Exploratory Data Analysis

Used scatter plots and pairplots to examine relationships

Calculated the correlation matrix

Data Preparation

Selected interest_rate and unemployment_rate as input features

Scaled features using StandardScaler

Split data into training and testing sets (75% train, 25% test)

Model Training

Trained a LinearRegression model on the training data

Evaluation Metrics

Mean Squared Error (MSE)

Mean Absolute Error (MAE)

Root Mean Squared Error (RMSE)

R² Score

Adjusted R² Score

Cross Validation

Applied 3-fold cross-validation to evaluate training performance

Visualization

Plotted regression lines and actual vs predicted values

📈 Results
R² Score: ~ [insert your score]

RMSE: ~ [insert your RMSE]

Observed an inverse relationship between interest rate and index price, indicating potential macroeconomic patterns.

📂 File Structure
plaintext
Copy
Edit
├── economic_index.csv
├── regression_model.ipynb
├── README.md
🚀 Future Enhancements
Add Ridge and Lasso regression for regularization

Introduce more features like inflation or GDP

Deploy as a Streamlit web app

🔗 Author
Aryan Kashyap
Feel free to explore and use this project for educational purposes!

