# churn-prediction-model

# 📞 Customer Churn Prediction

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1.0%2B-orange)
![License](https://img.shields.io/badge/License-MIT-green)

A machine learning project to predict customer churn for telecommunications companies, helping businesses identify at-risk customers and improve retention strategies.

## 📌 Table of Contents
- [Project Overview](#-project-overview)
- [Dataset](#-dataset)
- [Features](#-features)
- [Installation](#-installation)
- [Usage](#-usage)
- [Results](#-results)
- [Project Structure](#-project-structure)
- [Contributing](#-contributing)
- [License](#-license)

## 🌟 Project Overview

This project develops a predictive model to identify customers likely to churn (cancel services) from a telecom company. Key components include:

- Exploratory Data Analysis (EDA)
- Feature engineering
- Machine learning model training
- Model evaluation
- (Optional) Flask web app deployment

## 📊 Dataset

The dataset contains information about:
- Customer demographics (gender, senior citizen status, partner/dependents)
- Account information (tenure, contract type, payment method)
- Services subscribed (phone, internet, add-ons)
- Charges (monthly and total)
- Churn status (target variable)

**Dataset Source**: [IBM Telco Customer Churn Data](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

## 🔍 Features

### Key Predictive Features
1. **Tenure**: Months with the company
2. **Contract Type**: Month-to-month, yearly contracts
3. **Monthly Charges**: Recurring costs
4. **Internet Service**: DSL, Fiber optic, None
5. **Online Security**: Yes/No

### Target Variable
- **Churn**: Whether the customer left (Yes/No)

## 🛠 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/customer-churn-prediction.git
   cd customer-churn-prediction
