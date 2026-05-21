# Day 36 of #111DaysOfLearningForChange

Today's work focuses on **missing data imputation** using the `titanic_toy.csv` dataset.

## What I learned

- Split data into train and test sets before fitting imputers
- Compared **mean** and **median** imputation for `Age` and `Fare`
- Tried **arbitrary value imputation** using values like `99`, `999`, and `-1`
- Measured how different imputation strategies change variance, distribution, covariance, and correlation
- Used `SimpleImputer` and `ColumnTransformer` for a cleaner sklearn workflow

## Key takeaway

Imputation is not just about filling missing values. The strategy we choose can change the shape of the data, so it is worth comparing methods before using them in a model.

## Ready-to-post caption

🚀 Day 36 of #111DaysOfLearningForChange!

Exploring missing data imputation in Pandas and Scikit-learn. Learned how mean, median, and arbitrary value imputation affect variance, distribution, and model insights.

@CodeForChangeNp

#CodeForChange #36DaysOfLearning

