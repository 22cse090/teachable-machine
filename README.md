# 🤖 AutoML Buddy - Teachable Machine

This is a **Streamlit-based AutoML application** that allows users to upload a dataset (CSV), automatically detect the task type (classification or regression), train a Random Forest model, and evaluate its performance. The trained model can also be saved for future use.

---

## Project Overview
- **AutoML Buddy** is designed for quick experimentation with datasets.
- Automatically detects whether your problem is a **classification** or **regression** task.
- Uses **Random Forest** models for training.
- Provides **real-time performance metrics**:
  - Classification → Accuracy
  - Regression → Mean Squared Error (MSE)
- Saves the trained model as `trained_model.pkl` for reuse.

---
## Features

Automatic Task Detection: Determines if the problem is classification or regression.

Random Forest Models: Trains RandomForestClassifier or RandomForestRegressor.

Model Evaluation: Displays Accuracy (for classification) or MSE (for regression).

Model Persistence: Saves trained models for future predictions.

Interactive Web Interface: Powered by Streamlit for easy use without coding.


## Tech Stack

Python 3.9+

Streamlit

Pandas

Scikit-learn

Joblib
## Usage/Examples
Upload a dataset in CSV format.

Select the target column.

Click Train Model.

View evaluation metrics.

The trained model is saved automatically as trained_model.pkl.



## Author

Prerna Sharma

22cse090@gweca.ac.in

B.Tech CSE



