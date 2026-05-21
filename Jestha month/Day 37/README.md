# Day 37 of #111DaysOfLearningForChange

Today's notebooks focus on **categorical missing value imputation** using the `train.csv` dataset.

## What I learned

- Explored missing values in `GarageQual` and `FireplaceQu`
- Filled missing categories with a new label like `Missing`
- Used **most frequent imputation** to replace nulls with the mode
- Compared how different filling strategies change category counts and model-ready data
- Used `SimpleImputer` for a clean sklearn-based workflow

## Key takeaway

For categorical features, missing values can be handled either by creating a new category or by filling with the most frequent value. The best choice depends on whether "missing" itself carries useful information.

## Ready-to-post caption

🚀 Day 37 of #111DaysOfLearningForChange!

Learning categorical missing value imputation in Pandas and Scikit-learn. Explored filling nulls with a new category and using the most frequent value to make data model-ready.

@CodeForChangeNp

#CodeForChange #37DaysOfLearning

