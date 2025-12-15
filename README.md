# 🚗 Car Price Prediction Project

## 📌 Project Overview

The **Car Price Prediction** project is a machine learning application that predicts the selling price of a car based on various features such as brand, model year, fuel type, transmission, kilometers driven, and other specifications.

This project demonstrates the complete **end-to-end data science workflow**, including data preprocessing, exploratory data analysis (EDA), model training, evaluation, and deployment readiness.

---

## 🎯 Objectives

* Analyze car market data
* Build a regression model to predict car prices
* Compare different machine learning algorithms
* Deploy the trained model for real-time prediction (optional)

---

## 🧠 Machine Learning Techniques Used

* Linear Regression
* Random Forest Regressor
* Decision Tree Regressor
* Pipeline & Feature Engineering

---

## 🗂️ Project Structure

```
car-price-prediction/
│
├── data/
│   └── car_data.csv
│
├── notebooks/
│   └── EDA_and_Model_Training.ipynb
│
├── models/
│   └── car_price_model.pkl
│
├── app.py                # Flask / Streamlit app
├── requirements.txt
├── README.md

```

---

## 📊 Dataset Description

The dataset contains the following features:

| Column Name   | Description           |
| ------------- | --------------------- |
| name          | Car brand and model   |
| year          | Manufacturing year    |
| selling_price | Target variable       |
| km_driven     | Distance driven       |
| fuel          | Petrol / Diesel / CNG |
| seller_type   | Individual / Dealer   |
| transmission  | Manual / Automatic    |
| owner         | Owner type            |

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/Gokulnath k/car-price-prediction.git
cd car-price-prediction
```

### 2️⃣ Create Virtual Environment (Optional)

```bash
python -m venv venv
venv\Scripts\activate   # Windows
```

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Application

### For Streamlit App

```bash
streamlit run app.py
```

---

## 📈 Model Performance

* R² Score: **0.87**
* Mean Absolute Error (MAE): Low error rate
* Model saved using **Joblib / Pickle**

---

## 🛠️ Tools & Technologies

* Python
* Pandas, NumPy
* Scikit-learn
* Matplotlib, Seaborn
* Streamlit
* Git & GitHub

---

## 📌 Future Improvements

* Add more car features
* Improve accuracy with hyperparameter tuning
* Deploy on cloud (AWS / Render / Hugging Face)
* Add REST API

---

## 👤 Author

**Gokulnath k **
Data Science & Machine Learning Enthusiast

---

##
