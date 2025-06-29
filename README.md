# 🏠 Bangalore Home Price Prediction

This project is a complete end-to-end Machine Learning web application that predicts housing prices in Bangalore, India. It includes data preprocessing, model training, and a simple web interface to interact with the model.

---

## 🚀 Features

- Predicts the price of a house in Bangalore based on:
  - Location
  - Total square footage
  - Number of bedrooms (BHK)
  - Number of bathrooms
- Trained using real-world housing data
- Web interface built with HTML, CSS, and JavaScript
- Flask backend serving a serialized ML model

---

## 📁 Project Structure

BHP/
- ├── client/ # Frontend files
- │ ├── app.html
- │ ├── app.css
- │ └── app.js
- │
- ├── server/ # Flask server
- │ ├── server.py
- │ ├── util.py
- │ └── artifacts/ # Model & metadata
- │ ├── column.json
- │ └── bangalore_home_prices_model.pickle
- │
- ├── model/ # Model training
- │ ├── ml-projects-real-estate-price-prediction.ipynb
- │ ├── column.json
- │ └── bangalore_home_prices_model.pickle

---

## 🛠️ Setup Instructions

### 1. Clone the Repository
- git clone https://github.com/your-username/bangalore-home-price-prediction.git
- cd bangalore-home-price-prediction/BHP

### 2. Create a Virtual Environment
- python -m venv venv
- source venv/bin/activate  # On Windows: venv\Scripts\activate

### 3. Install Dependencies
- pip install -r requirements.txt

### 4. Run the Flask Server
- cd server
- python server.py

### 5. Open the Web App
- Open client/app.html in a browser and start predicting!

### 📊 Model Training
- The model was trained in the Jupyter notebook located at:
- model/ml-projects-real-estate-price-prediction.ipynb
- It uses a simple Linear Regression model trained on a cleaned housing dataset for Bangalore.
