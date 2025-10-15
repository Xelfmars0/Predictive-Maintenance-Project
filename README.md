# Predictive-Maintenance-Project
Team project for predictive maintenance case study - Data Science Capstone (Team Cre8tive Outliers)
# 🏭 Predictive Maintenance System

> Predicting machine failures to enable proactive maintenance and reduce downtime costs

## 📋 Project Overview

This project develops a machine learning system to predict equipment failures in industrial settings using sensor data. By identifying at-risk machines before they fail, we enable proactive maintenance strategies that can save significant downtime costs.

**Business Impact:** Potential savings in annual downtime costs through early failure detection.

## 🎯 Key Features

- **Failure Prediction**: Binary classification to predict machine failures
- **Multi-class Analysis**: Identification of failure types (Tool wear, Heat dissipation, Power, etc.)
- **Model Interpretation**: SHAP analysis to explain prediction drivers
- **Business Recommendations**: Actionable maintenance strategies based on model insights
- **Cost-Benefit Analysis**: ROI calculation for predictive maintenance implementation

## 📊 Dataset

**Source**: [AI4I 2020 Predictive Maintenance Dataset](https://archive.ics.uci.edu/dataset/601/ai4i+2020+predictive+maintenance+dataset)

**Features**:
- `Air temperature [K]`, `Process temperature [K]`, `Rotational speed [rpm]`
- `Torque [Nm]`, `Tool wear [min]`, `Machine Type`
- `Target`: Failure prediction (Binary)
- `Failure Type`: Specific failure modes

**Dataset Size**: 10,000 data points with 8 features

