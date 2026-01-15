# Student Performance Prediction — End-to-End ML System

This project builds, trains, and deploys a machine learning model to predict **student math scores** based on demographic and academic features.  
It includes a complete **ML pipeline**, saved artifacts, and a **Flask web application** for real-time inference, designed for production deployment.

## Features
- Data ingestion, preprocessing, training, and evaluation pipeline  
- Saved artifacts: `model.pkl`, `preprocessor.pkl`  
- Flask web interface for predictions  
- Modular project structure (production-style)  
- AWS Elastic Beanstalk ready

## Tech Stack
Python, Pandas, NumPy, scikit-learn, CatBoost, Flask, AWS Elastic Beanstalk

## Run Locally

```bash
pip install -r requirements.txt
python src/components/data_ingestion.py   # train & generate artifacts
python application.py                     # start web app


##Open: http://localhost:5000
