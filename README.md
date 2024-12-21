# Loan Status Prediction API

![License](https://img.shields.io/badge/license-MIT-blue.svg)  
![Python](https://img.shields.io/badge/python-3.x-blue.svg)  
![Flask](https://img.shields.io/badge/Flask-3.x-green.svg)

A machine learning-powered API for predicting loan approval status. This API is designed to simplify loan eligibility evaluations by providing quick and accurate predictions based on applicant and loan data.  

## 🚀 Quick Links

- **API Base URL**: [Loan Status API](https://loan-status-api.onrender.com/)  
- **API Endpoint (POST)**: [Predict Loan Status](https://loan-status-api.onrender.com/predict)  
- **Web Application**: [Loan Status Prediction App](https://loan-status-prediction-5fk2.onrender.com/)  
- **Project Repository**: [GitHub Repo](https://github.com/krish1440/loan_status_API)

## 📌 Features

- Predict loan approval status using a RESTful API.
- Categorical and numerical input handling.
- Scalable, production-ready deployment.

## 🔧 How to Use

### 1. **API Endpoints**

- **GET**: API's Documentation
  URL: [Loan Status API](https://loan-status-api.onrender.com/)  

- **POST**: Predict loan approval status  
  URL: [Predict Loan Status](https://loan-status-api.onrender.com/predict)

## 💬 Contact

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Krish%20Chaudhary-blue?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/krish-chaudhary-krc8252/)  
[![GitHub](https://img.shields.io/badge/GitHub-krish1440-black?style=flat-square&logo=github)](https://github.com/krish1440)

#### Request Example (POST)
Send a JSON payload with the required fields:
  ```json
  {
    "Gender": "Male",
    "Married": "Yes",
    "Dependents": "1",
    "ApplicantIncome": 5000,
    "CoapplicantIncome": 2000,
    "LoanAmount": 150,
    "LoanAmountTerm": 360,
    "CreditHistory": 1,
    "PropertyArea": "Urban"
   }



