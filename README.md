# Customer Churn Prediction App

This is a Streamlit web application that predicts the likelihood of a customer churning (leaving) a bank based on their profile and account information. The app uses a pre-trained TensorFlow deep learning model along with preprocessing tools like label encoders and scalers.

---

## Features

- Input customer details such as Geography, Gender, Age, Balance, Credit Score, Estimated Salary, Tenure, Number of Products, Credit Card possession, and Active Membership status.
- Preprocesses inputs using saved encoders and scalers.
- Uses a TensorFlow model (`model.h5`) to predict churn probability.
- Displays the probability and indicates whether the customer is likely to churn or not.

---

## Installation

1. Clone the repository or copy the files locally.
2. Make sure you have Python installed.
3. Install the required packages:

```bash
pip install -r reqirements.txt

```

## File Needed

- model.h5 — Pre-trained TensorFlow model file.

- onehot_encoder_geo.pkl — Saved OneHotEncoder for Geography feature.

- label_encoder_gender.pkl — Saved LabelEncoder for Gender feature.

- scaler.pkl — Saved scaler for feature normalization.

- Make sure these files are in the same directory as the Streamlit app script.
