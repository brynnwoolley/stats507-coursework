# stats507-coursework
GitHub repository for the U-M Stats 507 course

## Term Project: NYC Taxi Demand Forecasting

This project compares LSTM and Transformer models for short-term zone-level taxi demand prediction in New York City.

### File Structure
- `Data Preparation.ipynb`: Preprocessing pipeline for raw trip data.
- `Model.ipynb`: Defines and trains LSTM and Transformer models.
- `CleanedDemand.csv`: Processed time series features for modeling.

### How to Run
1. Open `Data Preparation.ipynb` and run all cells to prepare the dataset.
2. Open `Model.ipynb` to train and evaluate the models.

### Dependencies
- Python ≥ 3.8
- PyTorch
- Pandas, NumPy, scikit-learn
- Jupyter Notebook

Run `pip install -r requirements.txt` (if using virtual environments).

### Results Summary
| Model       | RMSE  | MAE   | Train Time (s) | Eval Time (s) |
|-------------|-------|-------|----------------|----------------|
| LSTM        | 0.2502 | 0.1061 | 38.81         | 0.26           |
| Transformer | 0.2450 | 0.1034 | 157.19        | 0.47           |

