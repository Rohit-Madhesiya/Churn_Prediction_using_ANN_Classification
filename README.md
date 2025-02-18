# Customer Churn Prediction
A Streamlit-based web application that predicts customer churn using a deep learning model. This project utilizes TensorFlow, Scikit-Learn, and Pandas to process user input, perform feature encoding, and make real-time predictions.

## 🚀 Live Demo
🔗 [Try the App on Streamlit](https://churnpredictionusingannclassification-5dxljksxj9ubtezfdx7hmc.streamlit.app/)
## Features

- Interactive UI built with **Streamlit**
- Uses a **trained TensorFlow model** for churn prediction
- **One-hot encoding & scaling** of categorical features
- **Real-time prediction probability** for customer churn

## Dependencies
Ensure you have the following installed before running the project:
```
tensorflow==2.16.1
pandas
numpy
scikit-learn==1.5.2
tensorboard
matplotlib
streamlit
keras
scikeras
```

## Installation

Clone the repository

```bash
git clone https://github.com/Rohit-Madhesiya/Churn_Prediction_using_ANN_Classification

cd Churn_Prediction_using_ANN_Classification
```
Install dependencies
```
pip install -r requirements.txt
```

Run the application
```
streamlit run app.py
```
## Usage

- Enter customer details (Geography(Country like: France, Germany), Gender, Age, Credit Score, etc.).
- The model processes the input, encodes categorical data, and predicts the churn probability.
- If the churn probability is above 0.5, the customer is likely to churn; otherwise, they are not.
## Technology Stack
- **Frontend:** Streamlit
- **Backend:** TensorFlow, Scikit-Learn
- **Model:** Deep Learning (TensorFlow)
- **Libraries:** Pandas, NumPy, Matplotlib
