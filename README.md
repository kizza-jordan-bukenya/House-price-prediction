# 🏠 House Price Prediction

A machine-learning web application that predicts the median value of a house based on its location, house characteristics, household information, and ocean proximity.

## 📌 Project Overview

This project demonstrates the complete machine-learning workflow:

* Data preparation and exploration
* Handling missing values
* Feature preprocessing
* Model training
* Model evaluation
* Model comparison
* Saving the trained model
* Building a web application with Streamlit
* Deploying a machine-learning model as an interactive application

## 📊 Dataset

The project uses the **California Housing dataset**, containing information about housing districts in California.

The dataset contains **20,640 observations** and includes features such as:

* Longitude
* Latitude
* Housing median age
* Total rooms
* Total bedrooms
* Population
* Households
* Median income
* Ocean proximity

The target variable is:

**Median house value**

## 🤖 Machine Learning Model

Several approaches were considered during the project, including a regression model and a Random Forest regression model.

The final model is a **Random Forest Regressor** using a preprocessing pipeline.

### Final Model Performance

| Metric   |    Result |
| -------- | --------: |
| MAE      | 31,628.59 |
| RMSE     | 48,941.95 |
| R² Score |    0.8172 |

The R² score indicates that the model explains approximately **81.7% of the variation** in the target variable on the test data.

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Joblib
* Streamlit
* Jupyter Notebook
* Git
* GitHub

## 📁 Project Structure

```text
House price predicrion/
│
├── app.py
├── requirements.txt
├── .gitignore
├── README.md
│
├── models/
│   └── house_price_model.pkl
│
└── notebooks/
    └── house_price_prediction.ipynb
```

## 🚀 Run the Application Locally

### 1. Clone the repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### 2. Open the project folder

```bash
cd "House price predicrion"
```

### 3. Install the required packages

```bash
pip install -r requirements.txt
```

### 4. Run the Streamlit application

```bash
python -m streamlit run app.py
```

The application will open in your web browser.

## 💡 How the Application Works

The user enters information about a house, including:

* Geographic location
* Housing median age
* Number of rooms
* Number of bedrooms
* Population
* Number of households
* Median income
* Ocean proximity

The trained machine-learning model processes these inputs and produces an estimated house value.

## ⚠️ Limitations

This application is intended for **educational and demonstration purposes**.

The prediction should not be considered an official property valuation because the model is trained on historical California housing data and does not account for all factors that influence real-world property prices.

## 🔮 Future Improvements

Possible improvements include:

* Hyperparameter tuning
* More advanced feature engineering
* Additional machine-learning models
* Improved user interface
* Interactive data visualizations
* Deployment to the cloud
* Integration with real-time property data
* Development of a construction-cost prediction model

## 👨‍💻 Author

**Kizza Jordan Bukenya**

Bachelor of Science in Quantity Surveying
Makerere University

Interested in Data Science, Machine Learning, Business Intelligence, and the application of technology in the construction industry.
