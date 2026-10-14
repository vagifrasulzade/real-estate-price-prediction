# Real Estate Price Prediction — Practical Questions

## Part 1 — Data Loading and Inspection

**Objective:** Understand the dataset structure and identify potential data quality issues.

1. Load the Excel dataset using Pandas and display the first 10 rows.
2. Find the total number of rows and columns.
3. Inspect column names, data types, and non-null values.
4. Calculate descriptive statistics for numerical columns.
5. Count duplicate records.
6. Calculate the number and percentage of missing values in each column.
7. Identify numerical and categorical columns.
8. Check the number of unique values in each column.
9. Identify the target variable and potential input features.
10. Summarize the main observations about the dataset.

## Part 2 — Data Cleaning and Preprocessing

**Objective:** Identify and handle data quality issues.

1. Investigate missing values in each column.
2. Decide how to handle missing numerical values.
3. Decide how to handle missing categorical values.
4. Identify and remove confirmed duplicate records.
5. Check for invalid property prices, areas, and bedroom counts.
6. Identify inconsistent categorical values.
7. Standardize categorical values, including capitalization and whitespace.
8. Investigate potential outliers in numerical columns.
9. Verify that the cleaned dataset has the expected data types.
10. Validate the cleaned dataset and summarize the changes.

## Part 3 — Exploratory Data Analysis (EDA)

**Objective:** Understand property price distributions and relationships between features.

1. What is the distribution of property prices?
2. What are the mean, median, and standard deviation of property prices?
3. Which property types have the highest average prices?
4. How does property area relate to price?
5. How do the numbers of bedrooms and bathrooms relate to price?
6. Which locations have the highest average property prices?
7. Are there significant differences in price between property types?
8. Which numerical features are most strongly correlated with price?
9. Are there potential outliers in property prices or areas?
10. What conclusions can be drawn from the visualizations?

## Part 4 — Feature Engineering

**Objective:** Prepare features for Machine Learning models.

1. Separate the target variable from the input features.
2. Identify numerical and categorical input features.
3. Check whether any columns should be excluded from training.
4. Encode categorical features using One-Hot Encoding.
5. Determine whether numerical feature scaling is necessary.
6. Split the dataset into training and testing sets.
7. Build a preprocessing pipeline for numerical and categorical features.
8. Ensure that preprocessing does not introduce data leakage.
9. Verify that the transformed features are suitable for model training.

## Part 5 — Model Training

**Objective:** Train regression models to predict property prices.

1. Create a baseline model using `DummyRegressor`.
2. Train a `LinearRegression` model.
3. Train a `RandomForestRegressor` model.
4. Train a `HistGradientBoostingRegressor` model.
5. Apply consistent preprocessing to all models.
6. Generate predictions using the test dataset.
7. Compare the models using the same training and testing split.
8. Investigate whether any model produces unrealistic predictions.

## Part 6 — Model Evaluation and Comparison

**Objective:** Evaluate prediction accuracy and select an appropriate model.

1. Calculate Mean Absolute Error (MAE) for each model.
2. Calculate Root Mean Squared Error (RMSE) for each model.
3. Calculate the R² score for each model.
4. Create a comparison table of all model metrics.
5. Identify the model with the lowest MAE.
6. Identify the model with the lowest RMSE.
7. Compare model performance against the baseline.
8. Plot actual prices against predicted prices.
9. Analyze residuals and prediction errors.
10. Select the most suitable model and justify the choice.

## Part 7 — Practical Price Predictions

**Objective:** Apply the trained model to property price estimation.

1. Display actual and predicted prices for test records.
2. Calculate the absolute prediction error for each record.
3. Identify records with the largest prediction errors.
4. Create an input record for a new property.
5. Predict the price of the new property.
6. Validate the new property's input features before prediction.
7. Explain the limitations of the generated prediction.

## Part 8 — Save Results and Project Outputs

**Objective:** Export analysis results and prepare the project for presentation.

1. Save model comparison metrics to `outputs/model_comparison.csv`.
2. Save actual and predicted prices to `outputs/test_predictions.csv`.
3. Save the price distribution plot.
4. Save the correlation heatmap.
5. Save the actual-versus-predicted plot.
6. Save the residuals plot.
7. Verify that the expected output files exist.
8. Update `README.md` with the actual dataset details and model results.
9. Document the best-performing model and its evaluation metrics.

## Final Review

1. Can the complete notebook run from beginning to end without errors?
2. Are missing values and duplicates handled appropriately?
3. Is the target variable excluded from the input features?
4. Is the test dataset kept separate from model training?
5. Are all model comparisons based on consistent evaluation data?
6. Are the results reproducible using a fixed random seed?
7. Are the project structure and installation instructions documented correctly?
