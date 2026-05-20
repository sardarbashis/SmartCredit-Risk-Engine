# SmartCredit Risk Engine

ML-powered credit risk prediction API and dashboard built using FastAPI, Scikit-learn, and MLOps principles.

---

## Features

- Credit score prediction API
- FastAPI backend
- Swagger API documentation
- ML inference pipeline
- Docker-ready structure
- Modular MLOps project architecture
- Scorecard generation

---

## Tech Stack

- Python
- FastAPI
- Scikit-learn
- Pandas
- NumPy
- Uvicorn
- Docker

---

## Project Structure

```bash
SmartCredit-Risk-Engine/
│
├── api/
├── app/
├── credit_score_mlops/
├── data/
├── models/
├── notebooks/
├── reports/
├── Dockerfile
├── params.yaml
├── pyproject.toml
└── README.md
```

---

## API Preview

### Swagger Documentation

Visit:

```bash
http://127.0.0.1:8000/docs
```

---

## Sample API Request

```json
{
  "person_age": 28,
  "person_income": 65000,
  "person_home_ownership": "RENT",
  "person_emp_length": 5,
  "loan_intent": "EDUCATION",
  "loan_grade": "B",
  "loan_amnt": 12000,
  "loan_int_rate": 11.5,
  "loan_percent_income": 0.18,
  "cb_person_default_on_file": "N",
  "cb_person_cred_hist_length": 6
}
```

---

## Sample API Response

```json
{
  "credit_score": 567
}
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/sardarbashis/SmartCredit-Risk-Engine.git
```

Move into the project directory:

```bash
cd SmartCredit-Risk-Engine
```

Create virtual environment:

```bash
python -m venv venv
```

Activate virtual environment:

```bash
venv\Scripts\activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run FastAPI server:

```bash
uvicorn api.api:app --reload
```

---

## Future Improvements

- SHAP explainability integration
- Deployment on Render/Railway
- Streamlit dashboard redesign
- Batch CSV predictions
- Authentication system
- Monitoring & logging dashboard

---

## Author

Ashis Kumar Sardar

GitHub:
https://github.com/sardarbashis
