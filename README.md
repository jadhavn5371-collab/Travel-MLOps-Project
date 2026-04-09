# Travel-MLOps-Project
End-to-end Travel MLOps project with flight price prediction, gender classification, and hotel recommendation using Flask, Docker, Kubernetes, Airflow, Jenkins, MLflow, and Streamlit.
travel-mlops-project/
│
├── README.md
├── requirements.txt
├── Dockerfile
├── deployment.yaml
├── Jenkinsfile
│
├── data/
│   ├── users.csv
│   ├── flights.csv
│   └── hotels.csv
│
├── notebooks/
│   ├── regression_model.ipynb
│   ├── classification_model.ipynb
│   └── recommendation_model.ipynb
│
├── models/
│   ├── flight_price_model.pkl
│   ├── gender_model.pkl
│   └── recommender.pkl
│
├── api/
│   └── app.py
│
├── streamlit_app/
│   └── app.py
│
├── airflow/
│   └── dag.py
│
└── mlflow/
    └── tracking.py

    Problem Statement

The system solves the following business problems:

Flight Price Prediction (Regression)
Gender Classification (Classification)
Hotel Recommendation System (Recommendation)
