# 🍔 QuickBite ETA Prediction

## 📌 Project Overview

**QuickBite ETA Prediction** is an **end-to-end Machine Learning project** that predicts **food delivery time (ETA)** based on order, restaurant, and delivery-related parameters.

The project simulates a **real-world food delivery system** like **Swiggy or Zomato** and covers the complete ML lifecycle:

* Data preprocessing
* Feature engineering
* Model training & evaluation
* Model deployment using **Flask**

---

## 🎯 Problem Statement

Accurately estimating food delivery time is critical for customer satisfaction in food delivery platforms.

Traditional/manual estimation methods are often inaccurate, leading to:

* Poor user experience
* Increased customer complaints
* Reduced trust in the platform

This project solves the problem using a **Machine Learning-based ETA prediction system**.

---

## 🧠 Technologies Used

* **Python**
* **Pandas**
* **NumPy**
* **Scikit-learn**
* **Flask**
* **Matplotlib / Seaborn**

---

## 📂 Project Structure

```
QuickBite-ETA-Prediction/
│
├── app/
│   ├── app.py              # Flask application
│   ├── templates/          # HTML templates
│   └── static/             # CSS / assets
│
├── train.py                # Model training script
├── train.csv               # Dataset used for training
├── model.pkl               # Trained ML model
├── requirements.txt        # Project dependencies
└── README.md               # Project documentation
```

---

## 📊 Dataset Description

The dataset contains various features related to food delivery such as:

* Distance between restaurant and customer
* Preparation time
* Delivery partner availability
* Traffic conditions
* Weather conditions

**Target Variable:**

* `Delivery_Time (ETA in minutes)`

---

## ⚙️ Model Building

1. Data Cleaning & Preprocessing
2. Feature Engineering
3. Train-Test Split
4. Model Training using **Scikit-learn**
5. Model Evaluation using metrics like:

   * Mean Absolute Error (MAE)
   * Mean Squared Error (MSE)

---

## 🚀 Deployment (Flask App)

The trained model is deployed using **Flask**, allowing users to input order details via a web interface and receive **predicted delivery time (ETA)**.
---

## 📈 Results

* The model provides reliable ETA predictions
* Helps improve delivery transparency
* Enhances customer satisfaction

---

## 🔮 Future Improvements

* Use advanced models (XGBoost, Random Forest)
* Real-time traffic and weather API integration
* Docker deployment
* Cloud deployment (AWS / Azure)

---

## 👨‍💻 Author

**Ganesh S**
Aspiring Data Scientist | Machine Learning Enthusiast

---

## ⭐ Acknowledgements

* Inspired by real-world food delivery platforms
* Open-source Python community

---

> If you like this project, don’t forget to ⭐ the repository!
