# Predictive Modeling of Emergency Food Gaps in NYC

## Project Overview
Built a logistic regression model to predict neighborhoods at high risk of food insecurity during emergency situations using NYC open data.

## Goals
- Identify vulnerable areas in NYC using data science.
- Help city planners prepare for food distribution crises.

## Technologies Used
- Python, Pandas, NumPy
- scikit-learn (logistic regression)
- Seaborn, Matplotlib (visualization)

## Methodology
- Cleaned and preprocessed real-world food access data.
- Performed exploratory data analysis (EDA).
- Built and evaluated a logistic regression model using precision, recall, F1-score.

## Key Results
- Food insecurity percentage was the most significant predictor of supply gaps, highlighting strong alignment between high food insecurity and emergency food need.
- Weighted score showed strong correlation with supply gap, while unemployment rate and vulnerable population percentage had moderate impact — suggesting interaction effects may improve future models.
- Model Performance:

Precision (High Gap): 0.61

Recall (High Gap): 0.44

F1 Score (High Gap): 0.51

High false negatives (22) indicate real-world risk of underestimating food supply needs.

-Despite limitations, the model offers valuable interpretability and serves as a foundation for more advanced predictive tools to guide food distribution efforts.

## Files
- `eda.ipynb`: EDA and visualization
- `model.ipynb`: Logistic regression modeling and evaluation

## Next Steps
- Explore decision trees or random forest models
- Incorporate additional demographic features
