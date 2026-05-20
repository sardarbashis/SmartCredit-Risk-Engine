# SmartCredit Risk Engine

A machine learning project for predicting customer credit risk using Logistic Regression, FastAPI, and Streamlit.

This project focuses on understanding how ML models can be deployed as APIs and used in finance-related applications.

---

## Project Overview

The goal of this project is to build a simple end-to-end machine learning workflow for credit risk prediction.

The project covers:

- Data preprocessing
- Model training
- Risk prediction
- API deployment using FastAPI
- Simple frontend interface using Streamlit
- Basic Docker containerization

The application predicts whether a customer belongs to a low-risk or high-risk credit category based on financial input data.

---

## Tech Stack

### Machine Learning
- Python
- Pandas
- NumPy
- Scikit-learn

### Backend & Deployment
- FastAPI
- Uvicorn
- Docker

### Frontend
- Streamlit

### Development Tools
- Git
- GitHub Actions

---

## Project Structure

```txt
SmartCredit-Risk-Engine/
│
├── api/                  # FastAPI backend
├── app/                  # Streamlit frontend
├── risk_engine/          # ML pipeline and utilities
├── data/                 # Dataset folders
├── models/               # Saved trained models
├── notebooks/            # Experiments and analysis
├── reports/              # Metrics and outputs
│
├── Dockerfile
├── requirements.txt
└── README.md