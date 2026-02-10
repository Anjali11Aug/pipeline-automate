
## 📌 Automated ML Pipeline for Screentime Usage Prediction

### Overview

This project demonstrates a basic batch machine learning pipeline for predicting app usage time using historical screentime data. The focus is on building a clear preprocessing workflow, training an ML model, and illustrating how the pipeline can be automated using Apache Airflow.

### Approach

* Performed data cleaning, feature engineering, and scaling on app usage data
* Trained and evaluated a Random Forest regression model using Mean Absolute Error (MAE)
* Defined an Apache Airflow DAG to conceptually automate the preprocessing step in a scheduled pipeline

### Technologies

Python, Pandas, Scikit-learn, Apache Airflow

### Notes

The Airflow DAG is included to demonstrate task orchestration logic. Due to environment constraints, the DAG is not executed in this setup. In a production environment, the DAG would be scheduled and run using the Airflow scheduler.

### Key Learnings

* End-to-end ML workflow from data preprocessing to evaluation
* Importance of automation and reproducibility in ML pipelines
* Practical understanding of batch-oriented ML systems


