Housing Price Prediction Model

A Machine Learning model that predicts housing prices based on key features such as Location, BHK, Number of Bathrooms, Property Size, and more.
This project demonstrates a complete end-to-end workflow — including data cleaning, feature engineering, model training, evaluation, and prediction — using real-world housing data.

🚀 Project Overview

The goal of this project is to build a model that can accurately estimate the selling price of a house based on user-provided inputs.
All the work is implemented inside the Jupyter Notebook:

📌 notebooks/DATA SCIENCE REGRESSION ON HOUSE SALE DATA.ipynb

The dataset used for analysis and training is located at:

📌 data/Bengaluru_House_Data.csv

🧠 Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn (Regression Models)

Jupyter Notebook

📊 Workflow / Steps Performed
1️⃣ Data Loading

Import dataset from CSV

Handle missing values

Treat incorrect datatypes

2️⃣ Exploratory Data Analysis (EDA)

Visualize data distributions

Calculate correlations

Detect outliers

Understand feature relationships

3️⃣ Feature Engineering

Encode categorical variables

Drop unnecessary columns

Create derived features

Normalize/scale features if needed

4️⃣ Model Building

Train-test split

Regression model training

Linear Regression / Random Forest Regression

Hyperparameter tuning

Avoiding overfitting & underfitting

5️⃣ Evaluation

Model performance comparison

6️⃣ Prediction

Final model predicts house prices based on factors such as:

Location / Area

BHK (Bedrooms)

Bathrooms


🖥️ How to Run Locally
1. Clone this repository
git clone https://github.com/udiits/Housing-Price-Model.git

2. Install dependencies
pip install -r requirements.txt

3. Open the notebook
jupyter notebook


Then open:

notebooks/DATA SCIENCE REGRESSION ON HOUSE SALE DATA.ipynb

📁 Project Structure
Housing-Price-Model/
├── data/
│   └── <your_dataset>.csv
├── notebooks/
│   └── DATA SCIENCE REGRESSION ON HOUSE SALE DATA.ipynb
├── LICENSE
├── .gitignore
└── README.md

📈 Results

Model successfully predicts housing prices based on user inputs

Visual insights are provided inside the notebook

🔧 Future Improvements

Deploy model using Streamlit

Add API using FastAPI

Train advanced models like XGBoost, CatBoost

Add more geographic features

👤 Contact

Udit Sharma
GitHub: https://github.com/udiits
