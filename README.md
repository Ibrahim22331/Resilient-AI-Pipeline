# Resilient AI Pipelines in Adversarial Big-Data Ecosystems

## CS4074 – Big Data Analytics Final Project

### Project Overview

This project presents a resilient AI-driven big data pipeline built using PySpark and Databricks. The pipeline is designed to detect, clean, and process adversarial or corrupted data records in large-scale analytical environments.

The system demonstrates how machine learning pipelines can maintain reliability and performance under noisy, incomplete, or manipulated datasets.

---

# Objectives

- Build a scalable PySpark-based analytics pipeline
- Detect adversarial and corrupted data
- Implement resilient ETL processing
- Apply machine learning using Spark MLlib
- Benchmark pipeline performance
- Analyze resilience under noisy data conditions

---

# Technologies Used

- PySpark
- Spark MLlib
- Databricks
- Python
- CSV Data Processing

---

# Project Structure

```bash
Resilient-AI-Pipeline/
│
├── data/
├── notebooks/
├── scripts/
├── screenshots/
├── docker/
├── README.md
├── requirements.txt
└── .gitignore
```

---

# Dataset Description

The dataset contains:

- Numerical features
- Missing values
- Corrupted records
- Adversarial anomalies

Examples of adversarial conditions:

- NULL values
- Negative values
- Extremely large manipulated values

---

# Pipeline Workflow

1. Load Dataset
2. Detect Missing Values
3. Remove Corrupted Data
4. Perform Feature Engineering
5. Train Machine Learning Model
6. Generate Predictions
7. Evaluate Performance
8. Measure Pipeline Resilience

---

# Installation Instructions

## Clone Repository

```bash
git clone https://github.com/yourusername/Resilient-AI-Pipeline.git
```

---

## Install Dependencies

```bash
pip install -r requirements.txt
```

---

# Running the Project

## Databricks

1. Upload `sample_data.csv`
2. Open notebook
3. Run all notebook cells

---

## Local Execution

```bash
python scripts/resilient_ai_pipeline.py
```

---

# Sample Results

## Resilience Metrics

- Original Records: 100
- Clean Records: 96
- Removed Adversarial Records: 4
- Detection Rate: 4%

---

# Machine Learning Results

The Logistic Regression model was trained using Spark MLlib to classify records after adversarial data cleaning.

---

# Performance Benchmarking

Pipeline execution time and processing performance were measured using PySpark transformations and aggregation operations.

---

# Screenshots

Screenshots of:

- Original dataset
- Cleaned dataset
- Model predictions
- Performance metrics

are available in the `screenshots/` directory.

---

# Dependencies

- pyspark
- pandas
- numpy
- scikit-learn

---

# Future Improvements

- Kafka Streaming Integration
- Real-Time Adversarial Detection
- Dockerized Deployment
- Cloud Scalability Testing
- Auto-Healing Data Pipelines

---

# Author

CS4074 Big Data Analytics Project  
Effat University – Spring 2026
