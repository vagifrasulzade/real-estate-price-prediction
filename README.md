# Real Estate Price Prediction

## Overview

This project uses machine learning to predict real estate prices based on property characteristics such as area, number of bedrooms and bathrooms, building age, location, floor, and distance to the city center.

The project covers data analysis, preprocessing, feature engineering, model training, evaluation, and practical price prediction.

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Excel

## Dataset Features

The dataset contains property information, including:

- Location
- Area (square meters)
- Bedrooms and bathrooms
- Property type
- Building age
- Floor and total floors
- Parking and elevator availability
- Distance to the city center
- Renovation status
- Property price (target variable)

## Machine Learning Models

The project compares the following regression models:

- Dummy Regressor (baseline)
- Linear Regression
- Random Forest Regressor
- HistGradientBoostingRegressor

## Evaluation Metrics

Models are evaluated using:

- **MAE:** Mean Absolute Error
- **RMSE:** Root Mean Squared Error
- **R²:** Coefficient of Determination

The best-performing model is selected based on the lowest RMSE.

## Project Structure

```text
real-estate-price-prediction/
├── data/
│   └── real_estate_data.xlsx
├── notebooks/
│   └── real_estate_price_prediction.ipynb
├── outputs/
│   ├── model_comparison.csv
│   ├── test_predictions.csv
│   └── plots/
├── questions.md
├── README.md
├── requirements.txt
└── .gitignore
```

## How to Run

1. Clone the repository.
2. Install the required dependencies.
3. Open the Jupyter Notebook.
4. Run the notebook cells in order.

Install dependencies:

```bash
pip install -r requirements.txt
```

Start Jupyter Notebook:

```bash
jupyter notebook
```

## Outputs

The project generates:

- Model comparison metrics
- Actual versus predicted prices
- Absolute prediction errors
- Price distribution visualization
- Correlation heatmap
- Residual analysis plot
- Predictions for a new property

## Limitations

Predictions depend on dataset quality, feature coverage, and market conditions. Estimated prices are not guaranteed selling prices or professional property valuations.

## Author

Developed as a practical machine learning project to build skills in data analysis, regression modeling, and model evaluation.