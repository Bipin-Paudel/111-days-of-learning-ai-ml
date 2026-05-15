# Day 31: PowerTransformer on Concrete Strength Data

**🚀 Day 31 of the 111 Days of Learning challenge is complete!**

Today I worked on a regression problem using concrete mix data and explored how power transforms can improve model performance:

- 🏗️ **Concrete Dataset:** I used `concrete_data.csv` to predict `Strength` from the mix ingredients and age.
- 📊 **Baseline Regression:** I trained a Linear Regression model on the raw features first.
- 🔄 **Box-Cox Transformation:** I used `PowerTransformer(method='box-cox')` to normalize positive-valued features.
- 🌊 **Yeo-Johnson Transformation:** I also tried the default `PowerTransformer()` version that works with zero and negative values too.
- 📉 **Distribution Check:** I compared feature distributions before and after transformation with plots.
- 🎯 **Model Comparison:** I compared test performance and cross-validation scores across the raw and transformed datasets.

This day made it much clearer that transforming skewed numeric data can unlock a big jump in linear model performance. 💡

## Key Results

- **Raw features:** test `R2 = 0.6276`, cross-val `R2 = 0.4610`
- **Box-Cox:** test `R2 = 0.8048`, cross-val `R2 = 0.6659`
- **Yeo-Johnson:** test `R2 = 0.8162`, cross-val `R2 = 0.6835`

## Files

- [`day31.ipynb`](day31.ipynb)
- [`concrete_data.csv`](concrete_data.csv)

@CodeForChangeNp #CodeForChange #DataScience #MachineLearning #111DaysOfLearning #Day31LearningForChange
