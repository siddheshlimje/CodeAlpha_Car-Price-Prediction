# CodeAlpha_Car-Price-Prediction

🚗 Car Price Prediction using Machine Learning
📌 Project Overview

This project focuses on building a Machine Learning model to predict the selling price of used cars based on various features such as:

Present Price

Kilometers Driven

Fuel Type

Transmission Type

Number of Owners

Age of Car

The goal is to build a regression model that can accurately estimate the selling price of a car.

📊 Dataset Information

The dataset contains 301 rows and the following features:

Feature	Description
Car_Name	Name of the car
Manufacturing_year	Year the car was manufactured
Selling_Price	Selling price of the car (Target Variable)
Present_Price	Current ex-showroom price
Driven_kms	Total kilometers driven
Fuel_Type	Petrol / Diesel / CNG
Selling_type	Dealer / Individual
Transmission	Manual / Automatic
Owner	Number of previous owners
Age_of_car	Age calculated from manufacturing year
🧹 Data Preprocessing Steps

Checked for missing values

Removed duplicates

Created new feature: Age_of_car

Dropped Manufacturing_year (redundant feature)

Dropped Car_Name (high cardinality feature)

Applied One-Hot Encoding to categorical variables

Checked skewness and outliers

Applied log transformation (if required)

🔍 Exploratory Data Analysis (EDA)

Distribution of Selling Price

Correlation Heatmap

Outlier Detection using IQR

Relationship between Age_of_car and Selling Price

Feature importance analysis

Key Observations:

Selling price decreases as age increases

Present price strongly affects selling price

Diesel cars tend to have slightly higher resale value

🤖 Machine Learning Models Used

Linear Regression

Random Forest Regressor

📈 Model Evaluation Metrics

R² Score

Mean Absolute Error (MAE)

Random Forest performed better compared to Linear Regression.

🏆 Final Model

The best performing model was:

👉 Random Forest Regressor

It provided higher accuracy and handled non-linearity and outliers effectively.

🛠️ Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

📂 Project Structure
Car-Price-Prediction/
│
├── car_data.csv
├── car_price_prediction.ipynb
├── README.md
🚀 How to Run This Project

Clone the repository

Install required libraries:

pip install -r requirements.txt

Run the Jupyter Notebook

📌 Future Improvements

Hyperparameter tuning using GridSearchCV

Cross-validation

Try XGBoost

Deploy model using Flask / Streamlit

🎯 Learning Outcome

This project helped in understanding:

Feature engineering

Handling categorical variables

Outlier detection

Model comparison

Regression evaluation metrics

👨‍💻 Author

Siddhesh Limje
Aspiring Data Scientist | Machine Learning Enthusiast
Open to Data Analyst & ML Internships
