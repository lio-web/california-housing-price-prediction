
# California Housing Price Prediction

## Project Overview
This project uses Machine Learning to predict median house prices in California using the California Housing dataset.

## Technologies Used
- Python
- Pandas
- Scikit-learn
- KNN Regression
- GridSearchCV
- Streamlit
- Joblib

## Machine Learning Workflow
1. Load California Housing dataset.
2. Preprocess data using StandardScaler and ColumnTransformer.
3. Split data into training and testing sets (80/20).
4. Train a KNeighborsRegressor.
5. Tune hyperparameters using GridSearchCV.
6. Apply 5-fold cross-validation.
7. Evaluate the model using R² score.
8. Save the trained pipeline using Joblib.
9. Build a Streamlit application for predictions.

## Run Locally

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the application:

```bash
streamlit run app.py
```

## Model
The trained model is saved as:

`california_housing_model.pkl`

## Author
Leonard Muhati
