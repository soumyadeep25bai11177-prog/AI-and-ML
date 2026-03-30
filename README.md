# Weather Forecasting AI Website

A simple AI/ML-based weather prediction website using machine learning to forecast next-day temperature based on weather parameters such as temperature, humidity, pressure, and wind speed.

---

## Project Title
AI-Based Weather Forecast Prediction Website

---

## Overview of the Project
This project is a complete end-to-end weather prediction system. It includes:
- A trained Machine Learning model that predicts next-day temperature.
- A Flask backend API that accepts user inputs and returns predictions.
- A clean, responsive frontend UI where users can input weather values.
- A modular architecture allowing dataset replacement or model improvement.

The purpose of this project is to demonstrate how AI/ML can be integrated into a real-world web application.

---

## Features
- Machine Learning-based weather prediction
- Clean and modern user interface
- Real-time API predictions
- Easy-to-train ML model (dataset included)
- Fully customizable model and architecture
- Cross-platform (Windows/Mac/Linux)

---

## Technologies / Tools Used
### Frontend:
- HTML5
- CSS3
- JavaScript

### Backend:
- Python
- Flask
- Flask-CORS

### Machine Learning:
- Scikit-learn
- Pandas
- NumPy
- Joblib

### Additional Tools:
- VS Code / PyCharm
- Node.js (optional for frontend workflow)

---

## Steps to Install and Run the Project
### 1. Clone or Download the Project
```
git clone https://github.com/your-repo/weather-ai-website
cd weather-ai-website
```

### 2. Install Backend Dependencies
```
cd backend
pip install -r requirements.txt
```

### 3. Train the Machine Learning Model
```
python train_model.py
```
This generates:
```
model.joblib
```

### 4. Run the Backend Server
```
python app.py
```
The server will run at:
```
http://127.0.0.1:5000
```

### 5. Start the Frontend
If using simple HTML:
```
Open index.html in browser
```

If using Node.js (optional):
```
cd frontend
npm install
npm start
```

---

## Instructions for Testing
### Test API using Postman or cURL
```
POST http://127.0.0.1:5000/predict
Content-Type: application/json

{
  "day_of_year": 120,
  "prev_temp": 30,
  "prev_humidity": 70,
  "prev_pressure": 1010
}
```
Expected Response:
```
{
  "predicted_temp": 31.52
}
```

### Test via Frontend
1. Open index.html
2. Enter the required weather values
3. Click Predict
4. AI-generated prediction will appear

---

## Screenshots (Optional)
You may add screenshots such as:
- Homepage UI
- Prediction result page
- Flask terminal logs
- Example dataset

---

## Contact / Support
If you need help or improvements, feel free to ask.
