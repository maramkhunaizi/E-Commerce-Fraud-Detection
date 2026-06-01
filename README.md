# E-Commerce Fraud Detection — IT9201 Project

**Author:** Maram Alkhenaizi
**Student ID:** 202509031
**Course:** Machine Learning and Data Mining (IT9201)
**Programme:** MSc in Artificial Intelligence
**Institution:** Bahrain Polytechnic
**Lecturer:** Dr. Shomona Gracia Jacob

## Project Overview

This project implements a binary classification model to detect fraudulent e-commerce transactions using three machine learning algorithms across two tools (Python and Orange).

## Models Implemented

- **Logistic Regression** — Linear baseline model
- **Naïve Bayes** — Probabilistic baseline model
- **Random Forest** — Ensemble tree-based model

## Dataset

E-Commerce Fraud Detection Dataset from Kaggle
- ~300,000 transactions
- 17 features (numerical + categorical)
- Binary fraud label (severe class imbalance: 1:44)

## Pipeline

1. Data acquisition (Kaggle)
2. Exploratory data analysis
3. Pre-processing (encoding, datetime extraction)
4. Stratified train-test split (80/20)
5. SMOTE + StandardScaler (training set only)
6. Model training (3 algorithms in 2 tools)
7. Hyper-parameter tuning (GridSearchCV, 5-fold stratified CV)
8. Evaluation (Accuracy, Precision, Recall, F1, ROC-AUC, Confusion Matrix)

## Tools Used

- **Python:** Jupyter Notebook, scikit-learn, imbalanced-learn, pandas, matplotlib, seaborn
- **Orange:** No-code workflow for cross-tool model implementation

## Files

- `ecommerce_fraud_detection.ipynb` — Main Python notebook
- `orange/fraud_detection.ows` — Orange workflow file
- `report/IT9201_Project_Report.pdf` — Final project report
- `data/` — Dataset folder

## How to Run

1. Clone this repository
2. Install dependencies: `pip install -r requirements.txt`
3. Open `ecommerce_fraud_detection.ipynb` in Jupyter
4. Run all cells in order

## License

Academic project submission for Bahrain Polytechnic.
