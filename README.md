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

The web app will be available at `http://localhost:5000/`.

---

## Usage

1. **Open the web application** in your browser.
2. **Enter your health parameters** (such as age, blood pressure, cholesterol, etc.).
3. **Submit the form** to receive your heart disease risk prediction.
4. **Download the PDF report** for your records.
5. **Explore health advice** and model explanations for better understanding.

---

## Technologies Used

- **Backend:** Python, Flask
- **Frontend:** HTML, CSS (in `templates/` and `static/`)
- **Machine Learning:** scikit-learn, pandas, numpy
- **Visualization:** matplotlib, seaborn
- **Voice Input:** speech recognition libraries
- **PDF Generation:** ReportLab or similar

---

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for improvements or bug fixes.

---

## License

This project is for educational and research purposes. Please review the repository for licensing details.

---

## Acknowledgments

Inspired by open-source heart disease prediction projects and the need for accessible healthcare technology.


