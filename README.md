# Customer Churn Prediction

A machine learning project to predict customer churn using ensemble methods, 
achieving 75.91% accuracy and 0.81 AUC on held-out test data.

## Project Structure
```
customer-churn-prediction/
├── data/
├── models/
├── notebooks/
│   └── churn_analysis.ipynb
├── output/
├── src/
├── requirements.txt
└── README.md
```

## Tech Stack
- Python, Scikit-learn, XGBoost
- Snowflake, AWS S3
- Power BI (dashboarding)
- Apache Kafka, NiFi (pipeline)

## Models Evaluated
- Logistic Regression
- Random Forest
- Gradient Boosting (Tuned) ← best performer

## Results
| Metric | Score |
|--------|-------|
| Accuracy | 75.91% |
| AUC | 0.8087 |
| No Churn F1 | 0.83 |
| Churn F1 | 0.57 |

## Setup
```bash
pip install -r requirements.txt
jupyter notebook notebooks/churn_analysis.ipynb
```