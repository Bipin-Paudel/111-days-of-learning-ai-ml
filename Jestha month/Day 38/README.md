# Day 38 of #111DaysOfLearningForChange

Today's notebooks focus on **advanced missing value handling** using Titanic and house price datasets.

## What I learned

- Used **random sample imputation** for numerical and categorical features
- Added **missing indicators** to preserve information about null values
- Compared imputed vs original distributions to see how sampling affects the data
- Used `SimpleImputer(add_indicator=True)` for a clean sklearn workflow
- Built a pipeline and used `GridSearchCV` to tune imputer strategies automatically

## Key takeaway

Missing value handling is not one-size-fits-all. Sometimes the best approach is to impute, sometimes to add an indicator, and sometimes to let the pipeline choose the best strategy.

## Ready-to-post caption

🚀 Day 38 of #111DaysOfLearningForChange!

Exploring advanced missing value handling in Pandas and Scikit-learn. Learned random sample imputation, missing indicators, and how to tune imputer settings inside a pipeline.

@CodeForChangeNp

#CodeForChange #38DaysOfLearning
