# Customer-Churn-Prediction


Overview

The Customer Churn Prediction & CX Simulation Platform is an AI-driven web application that models and visualizes customer experience (CX) to predict churn probability based on UI/UX interactions and behavioral metrics. The system empowers businesses to simulate various design, pricing, and support scenarios and forecast how users might react emotionally or behaviorally.

🚀 Features

Machine Learning–Powered Predictions: Forecast churn risk using behavioral, engagement, and emotional state data.

CX Scenario Simulation: Experiment with UI changes, support delays, or pricing shifts and visualize real-time customer outcomes.

Interactive Dashboard: Responsive and intuitive design for analyzing customer journey metrics and satisfaction trends.

Secure Flask Backend: Provides API endpoints for data ingestion, model inference, and simulation control.

Scalable Architecture: Designed for modular integration with customer analytics pipelines or CRM systems.

🏗️ Tech Stack

Frontend: HTML5, Tailwind CSS, Chart.js
Backend: Flask (Python), RESTful APIs
Machine Learning: Scikit-learn, TensorFlow/PyTorch
Database: SQLite / PostgreSQL (configurable)
Version Control: Git & GitHub
Authentication: JWT-based (optional for enterprise setup)

⚙️ Installation
1. Clone the Repository
git clone https://github.com/Vaibhavmohanty25/Customer-Churn-Prediction.git
cd cx-churn-simulator

2. Set Up Virtual Environment
python -m venv venv
source venv/bin/activate   # or venv\Scripts\activate on Windows

3. Install Dependencies
pip install -r requirements.txt

4. Run the Flask App
python app.py


Visit: http://127.0.0.1:5000

🧩 Project Structure

cx-churn-simulator/
│
├── app.py                     # Main Flask application
│
├── src/
│   ├── data_preparation/      # Data cleaning and preprocessing scripts
│   ├── modeling/              # ML model training and prediction logic
│   ├── simulator/             # Q-learning / CX environment simulation
│   └── utils/                 # Helper utilities
│
├── templates/                 # HTML templates and page layouts
├── static/                    # CSS, JavaScript, images, animations
│
├── models/                    # Trained ML and RL models (.pkl / .pth)
├── data/
│   ├── raw/                   # Unprocessed datasets
│   └── processed/             # Cleaned and feature-engineered datasets
│
└── README.md                  # Documentation


📊 Model Overview

Approach: Q-learning and supervised ML models for churn prediction.

Metrics Tracked: Accuracy, Precision, Recall, F1-score, and ROC-AUC.

Objective: Improve customer retention by modeling the relationship between UX decisions and churn probability.

🧠 Key Use Cases

Test CX design hypotheses before production rollouts.

Predict customer churn across different user groups.

Visualize emotional and behavioral impact of business decisions.
