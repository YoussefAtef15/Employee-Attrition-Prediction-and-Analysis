# 🏢 Employee Attrition Prediction and Analysis

## 📌 Project Overview
An end-to-end Machine Learning pipeline to predict employee turnover. By identifying employees who are likely to leave, this project aims to help organizations take proactive measures to improve retention. The final model is deployed as an API and an interactive dashboard.

## 📂 Project Structure
```text
employee_attrition_project/
├── app/
│   ├── api.py
│   └── dashboard.py
├── data/
│   ├── processed/
│   │   └── employee_attrition_processed.csv
│   └── raw/
│       └── employee_attrition_raw.csv
├── docs/
├── models/
│   └── best_attrition_model.pkl
├── notebooks/
│   ├── 01_data_collection_eda.ipynb
│   ├── 02_feature_engineering.ipynb
│   └── 03_model_training.ipynb
├── src/
│   ├── __init__.py
│   ├── data_processing.py
│   └── model_utils.py
├── README.md
└── requirements.txt
```

## 🚀 Milestones Completed So Far

- [x] **Milestone 1:** Data Collection & Exploratory Data Analysis (EDA).
- [x] **Milestone 2:** Feature Engineering & Data Cleaning.
- [x] **Milestone 3:** Model Training & Optimization (Handled imbalanced data using SMOTE, trained Random Forest and XGBoost).
- [ ] **Milestone 4:** Deployment (FastAPI & Streamlit) & MLOps.
- [ ] **Milestone 5:** Final Documentation & Presentation.

## ⚙️ Setup Instructions

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/YoussefAtef15/Employee-Attrition-Prediction-and-Analysis.git](https://github.com/YoussefAtef15/Employee-Attrition-Prediction-and-Analysis.git)
   ```

2. **Create a virtual environment and activate it:**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use: venv\Scripts\activate
   ```

3. **Install requirements:**
   ```bash
   pip install -r requirements.txt
   ```