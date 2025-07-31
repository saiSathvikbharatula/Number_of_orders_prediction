
# Number of Orders Prediction

This project uses a Gradient Boosting Regression model to predict the number of orders for a retail environment based on various features such as store type, location, holiday, and discount.

## Dataset

The dataset (`orders_data.csv`) includes the following features:
- `store_type`
- `location_type`
- `holiday`
- `discount`
- `num_orders` (target)

## Model

- **Algorithm**: Gradient Boosting Regressor
- **Libraries**: pandas, scikit-learn
- **Metrics**: MAE, RMSE, R² Score

## How to Run

```bash
python orders_prediction.py
```

This script will load the dataset, split it into training and testing sets, train the model, and print evaluation metrics.
