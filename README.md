# Customer Churn Prediction using Artificial Neural Networks

## 📌 Project Overview
This project focuses on predicting customer churn using an Artificial Neural Network (ANN) built with TensorFlow/Keras.  
The model was trained on customer data to identify whether a customer is likely to leave a company based on various features such as demographics, account information, and banking activity.

To improve model performance, Grid Search Hyperparameter Tuning was used to find the optimal neural network configuration.

The project also includes a Streamlit web application for interactive predictions and deployment.

---

## 🚀 Features
- Data preprocessing and feature engineering
- Artificial Neural Network (ANN) implementation
- Hyperparameter tuning using Grid Search
- Model evaluation and performance analysis
- Streamlit web app for real-time predictions
- Easy deployment with `app.py`

---

## 🛠️ Technologies Used
- Python
- TensorFlow / Keras
- Scikit-learn
- Pandas
- NumPy
- Matplotlib / Seaborn
- Streamlit

---

## 📂 Project Structure

```bash
Customer-Churn-Prediction/
│
├── app.py                     # Streamlit application
├── model/model.h5                   # Trained ANN model
├── requirements.txt           # Project dependencies
├── hyperparametertuningann.ipynb     # Model training notebook
├── encoder_scaler_pickle_files/scaler.pkl                 # Saved scaler object
├── encoder_scaler_pickle_files/label_encoder_gender.pkl         # Encoders for gender variable
├── encoder_scaler_pickle_files/onehot_encoder_geo.pkl         # Encoders for geography variable
└── README.md
```

---

## ⚙️ Model Training
The ANN model was trained using TensorFlow/Keras with the following workflow:

1. Data preprocessing
2. Feature scaling
3. Label encoding
4. ANN model creation
5. Hyperparameter tuning using Grid Search
6. Model evaluation

### Hyperparameters Tuned
- Number of hidden layers
- Number of neurons
- Batch size
- Epochs
- Optimizer
- Activation functions

---

## 📈 Model Performance
The trained ANN achieved strong predictive performance on the test dataset.

Evaluation metrics used:
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

## ▶️ Run the Project Locally

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/customer-churn-prediction.git
cd customer-churn-prediction
```

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Run the Streamlit App

```bash
streamlit run app.py
```
