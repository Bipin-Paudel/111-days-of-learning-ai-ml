# Day 42 of #111DaysOfLearningForChange

Today's notebook focused on **IQR-based outlier detection** using the placement dataset.

## What I learned

- Plotted the distribution and boxplot of `placement_exam_marks`
- Calculated the first quartile, third quartile, and IQR
- Found upper and lower outlier limits using the 1.5 * IQR rule
- Removed outliers with **trimming**
- Applied **capping** to keep the data while limiting extreme values

## Key takeaway

IQR is a simple and powerful way to detect outliers, especially when the data is skewed. Trimming and capping give two different ways to handle those extremes.

