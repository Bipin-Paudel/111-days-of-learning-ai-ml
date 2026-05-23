# Day 40 of #111DaysOfLearningForChange

Today's notebook covers a **step-by-step manual implementation of Iterative Imputation (MICE)** using the 50 Startups dataset.

## What I learned

- Initialized missing values with column means (0th iteration)
- For each missing value: removed the initial fill, trained a Linear Regression on other columns, and predicted the missing value
- Repeated this across multiple iterations and tracked how imputed values converge
- Understood the core logic behind `IterativeImputer` in sklearn before using it as a black box

## Key takeaway

Iterative imputation treats each feature with missing values as a regression target — using all other features to predict it. Running this loop until values stabilize gives a smarter, relationship-aware imputation.




