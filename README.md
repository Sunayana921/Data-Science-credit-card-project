# Data-Science-credit-card-project
This project builds an intelligent classification model to detect fraudulent credit card transactions with high accuracy and minimal false positives. It simulates real-world conditions using engineered user and merchant behaviors, location data, and spending patterns.



 Task Objectives

Detect fraudulent credit card transactions** using classification techniques.
Address class imbalance** using resampling strategies (undersampling in this case).
Engineer meaningful features**, including:
Transaction frequency per user
Location mismatch between user and transaction
Merchant-based spending pattern anomalies
Simulate real-world data** such as:
UserID, MerchantID`
TransactionLocation, UserHomeLocation
**Train a machine learning model** (Random Forest) for fraud classification.
**Evaluate model performance** using:
  - Confusion matrix
  - Precision, recall, F1-score
  - ROC-AUC score
  - Feature importance visualization

---

How to Run the Project

 1. Prerequisites
Make sure you have Python 3.7+ and the following libraries installed:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

2. Files

| File | Description |
|------|-------------|
| `creditcard.csv` | Original dataset |
| `fraud_detection_enhanced.py` | Main Python script |
| `creditcard_enhanced.csv` (optional) | Enhanced dataset after feature simulation |

3. Running the Project

Run the Python script from your terminal or IDE:


python fraud_detection_enhanced.py


This will:
- Load and simulate extra columns in the dataset
- Engineer additional fraud-detection features
- Train a classification model
- Output model performance metrics
- Generate plots:
  - Feature Importance
  - ROC Curve

---

Project Structure

```
.
├── creditcard.csv                  # Original dataset
├── fraud_detection_enhanced.py    # Core script with simulation, modeling, and evaluation
├── creditcard_enhanced.csv        # Exported dataset with engineered features
└── README.md                      # Project overview and guide
```
