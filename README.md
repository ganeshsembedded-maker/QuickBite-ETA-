🍔 QuickBite ETA Prediction
📌 Project Overview

QuickBite ETA Prediction is an end-to-end Machine Learning project that predicts food delivery Estimated Time of Arrival (ETA) based on order, restaurant, and delivery-related parameters.

The project simulates a real-world food delivery system (similar to Swiggy / Zomato) and demonstrates the complete ML lifecycle — from data preprocessing to model deployment using Flask.
🎯 Problem Statement

Accurate food delivery time estimation is critical for:

Improving customer satisfaction

Reducing order cancellations

Optimizing delivery operations

Manual or rule-based ETA estimation often leads to inaccuracies.
This project addresses the problem using a Machine Learning-based ETA prediction model.
🧠 Solution Approach

Perform Exploratory Data Analysis (EDA)

Clean and preprocess the dataset

Train regression-based ML models

Evaluate model performance using appropriate metrics

Deploy the trained model using a Flask web application

🛠️ Technologies Used

Python

Pandas

NumPy

Scikit-learn

Flask

📊 Machine Learning Model

Problem Type: Regression

Target Variable: Delivery Time (ETA)

Evaluation Metrics:

Mean Absolute Error (MAE)

Root Mean Squared Error (RMSE)

R² Score

📂 Project Structure

QuickBite-ETA-Prediction/
│
├── app/
│   └── app.py            # Flask application
│
├── train.py              # Model training script
├── train.csv             # Training dataset
├── requirements.txt      # Project dependencies
├── README.md             # Project documentation
📈 Future Improvements

Add real-time traffic and weather data

Use advanced models (XGBoost, Random Forest)

Deploy on cloud platforms (AWS / Render / Heroku)

Improve UI with frontend frameworks

👨‍💻 Author

Ganesh S
Aspiring Data Scientist | Machine Learning Enthusiast
