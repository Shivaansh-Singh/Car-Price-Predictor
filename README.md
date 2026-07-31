# 🚗 Car Price Prediction System

**Author:** Shivaansh Singh

**Registration Number:** 23MIM10071

**Application Number:** IN26011206

**Batch Number:** 1A

**Email ID:** shivaansh.23mim10071@vitbhopal.ac.in 

An end-to-end Machine Learning web application that predicts the resale price of a car based on its specifications, features, and history. The system trains a Random Forest Regressor model on historical automotive data and serves real-time predictions via a production-ready Flask interface deployed in the cloud.


## 🔗 Project Links

- **Live Web Application:** https://car-price-predictor-lm0r.onrender.com
- **GitHub Repository:** https://github.com/Shivaansh-Singh/Car-Price-Predictor

## 🛠️ Tech Stack & Ecosystem

- **Core Language:** Python 3.10
- **Machine Learning & Data Processing:** Scikit-learn, Pandas, NumPy
- **Backend Web Framework:** Flask
- **Production Web Server:** Gunicorn (WSGI)
- **Model Serialization:** Pickle
- **Cloud Platform:** Render 

## 📂 Production Directory Architecture

The repository is engineered according to institutional production guidelines, strictly separating static client UI assets from data matrix operations:

```text
📁 Car-Price-Predictor/
│
├── 📁 static/
│   └── 📄 style.css            # Custom user interface theme
│
├── 📁 templates/
│   └── 📄 index.html           # Core frontend interactive web form
│
├── 📄 app.py                   # Production Flask application engine
├── 📄 car_price_model.pkl      # Serialized Random Forest Regressor binary
├── 📄 requirements.txt         # Plaintext manifest mapping core dependencies
└── 📄 Procfile                 # Production WSGI process container config
