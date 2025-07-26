💻 Laptop Price Predictor

A machine learning web app that predicts the price of a laptop based on its specifications. Built with Python, Pandas, Scikit-learn, and deployed using Streamlit.

Live demo link: https://laptop-price-predictor-bysatyam.streamlit.app/

📌 Project Overview

This project aims to predict the price of laptops using key hardware specifications like processor, RAM, storage type, GPU, screen resolution, and more. The dataset is cleaned, features are engineered, and models are trained and evaluated. The final model is wrapped in an interactive Streamlit web app.

🚀 Features

Predict laptop prices in real-time

Cleaned and preprocessed dataset with complex columns (like Memory) handled

Feature engineering: SSD, HDD, Flash Storage, Hybrid extracted

Machine Learning model training using:

Random Forest Regressor

Pipeline for full transformation + model prediction

Interactive Streamlit web interface

🛠️ Tech Stack

Python

Pandas, NumPy

Scikit-learn

XGBoost

RandomForestRegressor

Streamlit

🧠 Machine Learning

Preprocessing: Handled complex columns like Memory, extracted numerical values from strings, dropped multicollinear features


Encoding: One-hot encoded categorical columns using ColumnTransformer

Model: Trained Linear Regression pipeline with evaluation metrics:

R² Score

Mean Absolute Error (MAE)

📈 Sample Results

Metric	Value

R² Score	0.88



🖥️ Web App Preview



🗂️ Project Structure

├── app.py                 # Streamlit application

├──laptop-predictor-model.ipynb  # Data preprocessing , EDA and Modelbuilding

├── df                     # Dataset

├── pipe.pkl              # Trained model (optional)

├── requirements.txt       # Dependencies

└── README.md              # Project overview


📦 Installation
bash

git clone https://github.com/Satyam-Singh-x/laptop-price-predictor.git

cd laptop-price-predictor

pip install -r requirements.txt

streamlit run app.py

📑 Requirements

Install all dependencies:

bash

pip freeze > requirements.txt

Or manually include:

txt

streamlit

scikit-learn

pandas

numpy

xgboost

🙋‍♂️ Author

Satyam Singh

B.Tech, Chemical Engineering – Jadavpur University

🔗 LinkedIn:https://www.linkedin.com/in/satyam-singh-61152a334 | singhsatyam.0912@gmail.com
