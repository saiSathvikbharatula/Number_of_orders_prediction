
# Credit Score Classification

This project builds a Random Forest Classifier to predict credit scores (Good, Standard, Poor) based on a person's financial attributes.

## Dataset

The dataset (`credit_data.csv`) includes:
- `income`
- `debt`
- `num_loans`
- `credit_utilization`
- `credit_score` (target: Good, Standard, Poor)

## Model

- **Algorithm**: Random Forest Classifier
- **Libraries**: pandas, scikit-learn
- **Metric**: Accuracy Score

## How to Run

```bash
python credit_classification.py
```

This script will load the dataset, encode the target variable, train a classification model, and evaluate accuracy.
