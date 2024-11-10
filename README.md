# Restaurant Tip Prediction Analysis

This project analyzes a dataset of restaurant bills to predict tip amounts. It involves:

- **Rainbow Test** for linearity
- **Residuals Plot** to check model assumptions
- **Trend Analysis** with line plots
- **Modeling** using linear and polynomial regression
- **Evaluation** based on RMSE and R-squared metrics

## Project Structure
- `data/`: Contains the dataset (e.g., `tips.csv`).
- `notebooks/`: Jupyter notebooks for data exploration, modeling, and visualization.
- `scripts/`: Python scripts for statistical tests, model training, and evaluation.

## Requirements
- Python 3.x
- pandas
- seaborn
- statsmodels
- scikit-learn
- matplotlib

## Instructions
1. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
2. Run the analysis notebook or scripts in the `scripts/` folder.

## Results
The best regression model is selected based on the lowest RMSE and highest R-squared, providing insights into factors affecting tip amounts.

## License
This project is open-source and available under the MIT License.
