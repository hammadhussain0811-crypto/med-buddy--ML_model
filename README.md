# 🩺 MedBuddy.ML – Heart Disease Prediction

A Machine Learning web application that predicts the probability of heart disease based on patient health parameters.

## 🌐 Live Demo

🔗 https://medbuddy-heart-prediction.streamlit.app

## 📌 Overview

MedBuddy.ML is an end-to-end Machine Learning project that predicts whether a patient is at risk of heart disease using clinical health data.

The project includes:

- Data preprocessing
- Model training
- Model serialization using Joblib
- Prediction pipeline
- Interactive Streamlit web application
- Cloud deployment using Streamlit Community Cloud

---

## 🚀 Features

- Predicts heart disease risk
- Displays prediction probability
- Interactive and user-friendly interface
- Real-time predictions
- Deployed online for public access

---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Streamlit
- Joblib
- Git & GitHub
  

---

## 📂 Project Structure

```
med-buddy--ML_model/
│
├── backend/
│   ├── training.py
│   ├── predictor.py
│   └── main.py
│
├── dataset/
│
├── model_dir/
│   └── heart_disease_prediction_model.joblib
│
├── notebooks/
│
├── logs/
│
├── app.py
├── requirements.txt
├── README.md
└── LICENSE
```

---

## 📊 Input Features

- Age
- Sex
- Chest Pain Type
- Resting Blood Pressure
- Cholesterol
- Fasting Blood Sugar
- Resting ECG
- Maximum Heart Rate
- Exercise Induced Angina
- Oldpeak
- Slope
- Number of Major Vessels
- Thal

---

## ⚙️ Installation

Clone the repository

```bash
git clone https://github.com/hammadhussain0811-crypto/med-buddy--ML_model.git
```

Move into the project

```bash
cd med-buddy--ML_model
```

Create virtual environment

```bash
python -m venv venv
```

Activate virtual environment

Windows

```bash
venv\Scripts\activate
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the application

```bash
streamlit run app.py
```

---

## 📷 Application Preview
### Home Page

![Home Page](images/Screenshot%202026-07-01%20205720.png)

### Prediction Result

![Prediction Result](images/Screenshot%202026-07-01%20205733.png)

---

## 🌍 Deployment

The application is deployed using **Streamlit Community Cloud**.

Live Application:

https://medbuddy-heart-prediction.streamlit.app

---

## 📈 Future Improvements

- Better UI/UX
- Model explainability (SHAP)
- Multiple ML model comparison
- Docker deployment
- REST API integration
- User authentication

---

## 👨‍💻 Author

**Hammad Hussain**

GitHub:
https://github.com/hammadhussain0811-crypto

LinkedIn:
https://www.linkedin.com/in/hammad-hussain-629b59243

