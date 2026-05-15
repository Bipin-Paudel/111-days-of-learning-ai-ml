# Day 30: Log Transformations with FunctionTransformer

**🚀 Day 30 of the 111 Days of Learning challenge is complete!**

Today I explored how log transforms can improve skewed features in a Titanic survival workflow:

- 📊 **Titanic Feature Setup:** I worked with `Age`, `Fare`, and `Survived` from `train.csv`.
- 📈 **Distribution Check:** I visualized the feature distributions with histograms and QQ plots.
- 🔁 **FunctionTransformer:** I used `np.log1p` to apply a log transform cleanly.
- 🧩 **ColumnTransformer:** I applied the transform to `Fare` while keeping the other feature unchanged.
- 🎯 **Model Comparison:** I compared Logistic Regression and Decision Tree performance before and after transformation.
- ⚠️ **Experimentation:** I also tried `np.sin` as a custom transform to see how a poor transformation affects performance.

The main lesson was that the right transformation can make a real difference, especially for skewed numeric features. 💡

## Key Results

- **Without transform:** Logistic Regression = `0.6480`, Decision Tree = `0.6872`
- **With log transform:** Logistic Regression = `0.6816`, Decision Tree = `0.6704`
- **With `ColumnTransformer` log on Fare:** Logistic Regression = `0.6704`, Decision Tree = `0.6592`
- **With `np.sin` experiment:** Logistic Regression accuracy = `0.6195`

## Files

- [`day30.ipynb`](day30.ipynb)
- [`train.csv`](train.csv)

@CodeForChangeNp #CodeForChange #DataScience #MachineLearning #111DaysOfLearning #Day30LearningForChange
