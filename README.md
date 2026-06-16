# Real Estate Price Predictor — UAE

> Predicting property prices in the UAE using machine learning regression models trained on real market data.

---

## Overview

This project builds and evaluates machine learning models to predict real estate prices across the UAE. It covers the full ML pipeline: data exploration, preprocessing, feature engineering, model training, and evaluation.

**Current status:** Work in progress — trained on initial dataset, expanding to full real-world data.

---

## Dataset

| Field  | Details               |
| ------ | --------------------- |
| Source | UAE property listings |
| Format | CSV                   |
| Size   | ~14 KB (initial)      |
| Target | Property price        |

> The full dataset will be updated as more real-world data is collected and cleaned.

---

## Project Structure

```
Real_Estate_Predictor/
├── 1.ipynb              # Main notebook: EDA, preprocessing, modeling
├── uae_properties.csv   # Dataset
├── .gitignore
└── README.md
```

---

## ML Pipeline

- [ ] Exploratory Data Analysis (EDA)
- [ ] Data Cleaning & Preprocessing
- [ ] Feature Engineering
- [ ] Model Training (Linear Regression, Random Forest, XGBoost)
- [ ] Hyperparameter Tuning
- [ ] Model Evaluation & Comparison
- [ ] Deployment (planned)

---

## Tech Stack

![Python](https://img.shields.io/badge/Python-3.14-blue?logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data_Analysis-150458?logo=pandas&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-ML-F7931E?logo=scikit-learn&logoColor=white)

---

## Getting Started

```bash
# Clone the repo
git clone https://github.com/HatemAhmed1/Real_Estate_Predictor.git
cd Real_Estate_Predictor

# Create and activate a virtual environment
python -m venv ml-env
ml-env\Scripts\activate      # Windows
# source ml-env/bin/activate  # macOS/Linux

# Install dependencies
pip install jupyter pandas numpy matplotlib seaborn scikit-learn

# Launch the notebook
jupyter notebook 1.ipynb
```

---

## Results

> To be updated after full training on real data.

---

## Author

**Hatem Ahmed** — (https://github.com/HatemAhmed1)

---

_This project is part of a hands-on machine learning learning journey._
