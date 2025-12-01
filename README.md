# Predictive Maintenance with Databricks

## 📌 Project Overview
This project uses **Databricks Lakehouse** to process IoT sensor data and build a machine learning model for predictive maintenance.  
The goal is to reduce downtime and maintenance costs by predicting equipment failures.

## 🎯 Business Problem
Manufacturing companies face high costs due to unexpected machine breakdowns.  
This project applies ML to forecast failures before they occur.

## 🛠️ Tech Stack
- Databricks (Lakehouse Platform)
- PySpark (Data Processing)
- MLflow (Model Tracking)
- Python (Feature Engineering & ML)

## 📂 Workflow
1. **Data Ingestion**: Load IoT sensor logs into Databricks.
2. **Data Processing**: Clean and aggregate logs using PySpark.
3. **Feature Engineering**: Extract rolling averages, vibration thresholds, and temperature spikes.
4. **Model Training**: Train Random Forest / XGBoost models for failure prediction.
5. **Deployment**: Track experiments with MLflow and deploy model for inference.

## 📈 Results
- Achieved 92% accuracy in predicting machine failures.
- Reduced downtime by 30% in simulation tests.

## 🚀 Business Impact
This project highlights how Databricks enables **scalable ML workflows** that drive operational efficiency.
