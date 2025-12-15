# 🔥 Forest Fire Prediction System

A Machine Learning Web Application built with **Flask** that predicts the **Fire Weather Index (FWI)** based on various environmental factors. This project uses **Ridge Regression** for prediction and is deployed using a Flask web server.

## 📂 Project Overview
Forest fires are a major environmental concern. This application allows users to input weather conditions (like temperature, humidity, wind speed) and predicts the fire danger level using a trained Machine Learning model.

### Key Features:
* **User-Friendly Interface:** Built with HTML/CSS.
* **ML Model:** Ridge Regression model trained on the Algerian Forest Fires dataset.
* **Preprocessing:** Standard Scaler used for feature scaling.
* **Backend:** Flask API to handle requests and render templates.

## 🛠️ Tech Stack
* **Python** (3.x)
* **Flask** (Web Framework)
* **Scikit-Learn** (Machine Learning)
* **Pandas & NumPy** (Data Manipulation)
* **Pickle** (Model Serialization)
* **HTML/CSS** (Frontend)

## 📊 Dataset
The model was trained on the **Algerian Forest Fires Dataset**, which includes features like:
* **Temperature** (noon temperature in °C)
* **RH** (Relative Humidity in %)
* **Ws** (Wind Speed in km/h)
* **Rain** (Daily rainfall in mm)
* **FFMC** (Fine Fuel Moisture Code)
* **DMC** (Duff Moisture Code)
* **ISI** (Initial Spread Index)
* **Classes** (Fire/Not Fire)
* **Region** (Bejaia/Sidi Bel-Abbes)

## ⚙️ Installation & Usage

Follow these steps to run the project locally:

### 1. Clone the Repository
```bash
git clone [https://github.com/Heet-Jamariya/Forest-Fire-Prediction-Flask.git](https://github.com/Heet-Jamariya/Forest-Fire-Prediction-Flask.git)
cd Forest-Fire-Prediction-Flask