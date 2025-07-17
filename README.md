# churn-prediction-api
End-to-end machine learning project for customer churn prediction using AWS services like SageMaker, Lambda, and API Gateway.

# 🔄 Customer Churn Prediction API – AWS Serverless Deployment

## 📌 Overview

This project demonstrates how to build and deploy a machine learning model that predicts customer churn based on historical data. The goal is to provide a scalable, serverless prediction API using AWS services such as SageMaker, Lambda, and API Gateway.

It is designed as an end-to-end MLOps portfolio project, highlighting the full ML lifecycle: from data preprocessing and model training to deployment, CI/CD integration, and API delivery.

---

## 🎯 Use Case

Customer churn is a major concern for subscription-based businesses. Early identification of at-risk customers enables companies to take proactive steps and reduce revenue loss.

This project simulates how a company could:
- Train a predictive churn model using past customer behavior
- Serve that model through a low-latency, scalable API
- Automate the infrastructure and deployment process using DevOps practices

---

## 🧠 Tech Stack

| Category             | Tools / Services                          |
|----------------------|-------------------------------------------|
| Data Processing      | Pandas, NumPy                             |
| ML Modeling          | Scikit-learn                              |
| Model Hosting        | AWS SageMaker (or Lambda with .pkl file)  |
| API Endpoint         | AWS Lambda + API Gateway                  |
| Infrastructure       | AWS S3, IAM Roles                         |
| CI/CD Pipeline       | GitHub Actions                            |
| Monitoring / Logs    | AWS CloudWatch                            |
| Documentation        | Markdown, GitHub, Jupyter Notebooks       |

---

## 📂 Project Structure

churn-prediction-api/
├── data/ # Sample Telco churn dataset (CSV)
├── notebooks/ # Exploratory data analysis and modeling
├── src/
│ ├── train_model.py # Training script
│ ├── predict.py # Prediction logic for Lambda
│ └── lambda_handler.py # Lambda entry point
├── model/ # Saved model artifact (.pkl)
├── requirements.txt # Python dependencies
├── README.md
└── .github/workflows/ # GitHub Actions for CI/CD


---

## 🚀 Features

- End-to-end churn prediction system
- AWS-native deployment (serverless infrastructure)
- Modular, extensible codebase
- CI/CD pipeline for model deployment
- Suitable for small teams or startups without DevOps engineers

---

## 🛠️ Future Improvements

- Streamlit dashboard to explore churn predictions
- Batch processing pipeline with AWS Batch or Step Functions
- Integration with a database (e.g. DynamoDB) for logging predictions
- Model registry integration (e.g. MLflow)

---

## 🙋‍♂️ About Me

Built by **Furkan Yildiz** – M.Sc. Engineering & Management student, with industry experience in AI evaluation, requirements engineering, and AWS-based ML solutions.

> Connect on [LinkedIn](https://www.linkedin.com/in/furkan-yildiz-3a7321266/) or check out my other projects [here](https://github.com/your-github).

