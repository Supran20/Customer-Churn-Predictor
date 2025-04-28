# Customer Churn Prediction Web App

This is a simple **Flask web application** that predicts whether a customer will churn (leave) or not, based on their service details.  
It uses a **Random Forest Classifier** trained on customer data, with preprocessing steps including **encoding categorical features** and **scaling numerical features**.

---

## Features
- Predict customer churn (Churn/No Churn) with probability
- User-friendly web interface
- Preprocessing using saved encoders and scaler
- Random Forest-based prediction model

---


## Input Fields

- Gender
- Senior Citizen (0 or 1)
- Partner (Yes/No)
- Dependents (Yes/No)
- Tenure (integer, months)
- Phone Service (Yes/No)
- Multiple Lines (Yes/No/No phone service)
- Internet Service (DSL/Fiber optic/No)
- Online Security (Yes/No/No internet service)
- Online Backup (Yes/No/No internet service)
- Device Protection (Yes/No/No internet service)
- Tech Support (Yes/No/No internet service)
- Streaming TV (Yes/No/No internet service)
- Streaming Movies (Yes/No/No internet service)
- Contract (Month-to-month/One year/Two year)
- Paperless Billing (Yes/No)
- Payment Method (Electronic check/Mailed check/Bank transfer/Credit card)
- Monthly Charges (float)
- Total Charges (float)

---

## Prediction Output

- **Result**: "Churn" or "No Churn"
- **Probability**: Confidence score (0 to 1)

---

## Model Details

- **Algorithm**: Random Forest Classifier
- **Preprocessing**: 
  - Encoding categorical variables
  - Scaling numerical features

---

## License
This project is for educational purposes.

---
