# Titanic Survival Prediction (Machine Learning)

This project builds a machine learning model to predict passenger survival on the Titanic dataset.

It covers the full ML workflow, including data analysis, feature engineering, preprocessing pipelines, and model experimentation.

---

## Objective

The goal is to predict whether a passenger survived (1) or not (0) using structured data.

---

## Key Steps

- Exploratory Data Analysis (EDA)
- Feature Engineering (FamilySize, Title)
- Data Preprocessing with Pipeline & ColumnTransformer
- Model Training and Evaluation
- Model Comparison

---

## Features Used

- Pclass (ticket class)
- Sex
- Age
- Fare
- Embarked
- FamilySize (engineered)
- Title (engineered from Name)

---

## Models Evaluated

- Linear Regression (baseline)
- Logistic Regression
- Random Forest Classifier

---

## Results

| Model               | Accuracy | Recall (Survived) |
|--------------------|---------|------------------|
| Linear Regression  | 0.81    | 0.72             |
| Logistic Regression| 0.83    | 0.75             |
| Random Forest      | 0.83    | 0.75             |

---

## Key Insights

- Female passengers had a significantly higher survival rate
- Higher-class passengers were more likely to survive
- Feature engineering (Title, FamilySize) improved model performance
- Random Forest captured more complex patterns in the data

---

## Conclusion

Both Logistic Regression and Random Forest performed well, achieving similar accuracy.  
Random Forest was selected as the final model due to its ability to capture non-linear relationships.

---

## Future Improvements

- Hyperparameter tuning
- Advanced models (Gradient Boosting, XGBoost)
- Feature selection optimization

---

## Tech Stack

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib / Seaborn

---

## Author

Juan Fierro
