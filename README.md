# Heart Disease Prediction System

A machine learning-powered web application for predicting the risk of heart disease based on user health parameters. This project leverages data science and AI to assist users and healthcare professionals in early detection and risk assessment of cardiovascular diseases.

---

## Features

- **Heart Disease Risk Prediction:** Input health metrics to receive a prediction of heart disease risk.
- **Interactive Web Interface:** User-friendly frontend for data input and results display.
- **AI Explainability:** Model explanations provided for predictions.
- **Health Advice:** Actionable health recommendations based on prediction results.
- **PDF Report Generation:** Downloadable summary of your results and advice.
- **Voice Input Support:** Enter data using voice commands for accessibility.
- **Data Visualization:** Visual representation of input data and prediction outcomes.

---

## Project Structure

| Folder/File         | Description                                  |
|---------------------|----------------------------------------------|
| `data/`             | Datasets used for training and testing       |
| `models/`           | Saved machine learning models                |
| `notebook/`         | Jupyter notebooks for exploration/training   |
| `static/plots/`     | Static images and plots for the web app      |
| `templates/`        | HTML templates for the web interface         |
| `utils/`            | Utility scripts and helper functions         |
| `app.py`            | Main Flask application                       |
| `ai_explainer.py`   | Model explanation logic                      |
| `generate_pdf.py`   | PDF report generation module                 |
| `health_advice.py`  | Health advice logic                          |
| `voice_input.py`    | Voice input processing                       |
| `tester.py`         | Testing and validation script                |
| `requirements.txt`  | Python dependencies                          |
| `Procfile`          | Deployment configuration (e.g., Heroku)      |
| `run.sh`            | Shell script to run the application          |

---

## Getting Started

### Prerequisites

- Python 3.7+
- pip (Python package manager)

### Installation

1. **Clone the repository:**
