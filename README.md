# 🏠 House Price Prediction — Machine Learning Web Application

A machine learning web application that predicts the estimated median value of a house based on its location, characteristics, and household information.

##  Live Demo

Try the application here:

https://house-price-prediction-mdhphcrv3cbeb2pnprcts9.streamlit.app/

##  Project Overview

This project demonstrates the development of an end-to-end machine learning application, starting from housing data preparation and model training to deployment as an interactive web application.

A **Random Forest Regression** model was trained to predict median house values using housing characteristics such as location, number of rooms, number of bedrooms, population, household size, and median income.

The trained model is hosted on **Hugging Face**, while the application is deployed using **Streamlit Community Cloud**.

##  Objectives

* Build a machine learning model for house price prediction.
* Perform data preparation and feature selection.
* Train a Random Forest regression model.
* Create an interactive user interface using Streamlit.
* Host the trained machine learning model online.
* Deploy the complete application so users can make predictions through a web browser.

##  Technologies Used

* **Python**
* **Pandas**
* **NumPy**
* **Scikit-learn**
* **Joblib**
* **Streamlit**
* **Hugging Face**
* **GitHub**

##  Machine Learning Model

The project uses a **Random Forest Regression** model.

### Input Features

The model uses the following features:

* Longitude
* Latitude
* Housing median age
* Total rooms
* Total bedrooms
* Population
* Households
* Median income
* Ocean proximity

### Target

The target variable is:

**Median House Value**

** Project Workflow

Housing Dataset
       ↓
Data Cleaning & Preparation
       ↓
Feature Selection
       ↓
Model Training
       ↓
Random Forest Regression
       ↓
Model Saved with Joblib
       ↓
Model Hosted on Hugging Face
       ↓
Streamlit Web Application
       ↓
Deployment on Streamlit Community Cloud


How the Application Works

1. The user enters information about a house.
2. The application collects the input values.
3. The inputs are converted into a Pandas DataFrame.
4. The trained Random Forest model processes the data.
5. The model generates an estimated house value.
6. The predicted value is displayed to the user.

Project Structure

text
House-price-prediction/
│
├── app.py
├── README.md
├── requirements.txt
├── .gitignore
│
├── models/
│
└── notebooks/


Deployment

The project uses several technologies together:

* **GitHub** — source code and project version control
* **Hugging Face** — hosting the trained machine learning model
* **Streamlit Community Cloud** — hosting the web application

This allows the machine learning model and application to be accessed online without requiring users to run the project locally.

Skills Demonstrated

This project demonstrates practical experience with:

* Python programming
* Data preprocessing
* Exploratory data analysis
* Feature engineering
* Machine learning
* Regression
* Random Forest
* Model serialization
* Streamlit application development
* GitHub
* Model hosting
* Cloud deployment

⚠️ Disclaimer

This application is intended for **educational and demonstration purposes only**. The predictions should not be considered official property valuations or professional appraisals.

Author

Kizza Jordan Bukenya

Aspiring Data Scientist | Data Analyst | Machine Learning Enthusiast



If you find this project useful, feel free to explore the repository and try the live application.
