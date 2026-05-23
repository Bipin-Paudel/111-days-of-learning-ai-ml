# Day 39 of #111DaysOfLearningForChange

Today's notebook focuses on **KNN Imputation** for handling missing values using the Titanic dataset.

## What I learned

- Used `KNNImputer` with `n_neighbors=3` and `weights='distance'` to fill missing Age values
- Compared KNN imputation against `SimpleImputer` (mean strategy)
- Trained a Logistic Regression model on both imputed datasets and measured accuracy
- KNN imputer outperformed mean imputation: **71.5% vs 69.3% accuracy**

## Key takeaway

KNN imputation leverages the similarity between data points to fill missing values more intelligently than simple mean/median imputation, and this can translate to measurable gains in model accuracy.

