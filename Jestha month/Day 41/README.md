# Day 41 of #111DaysOfLearningForChange

Today's notebook focused on **outlier detection and treatment** using the placement dataset.

## What I learned

- Visualized the distribution of `cgpa` and `placement_exam_marks` to understand skewness and spread
- Found boundary values using the mean and standard deviation
- Removed outliers using **trimming**
- Used **Z-score based filtering** to detect extreme values
- Applied **capping** with `np.where()` to limit values outside the acceptable range

## Key takeaway

Outlier handling is not just about deleting bad values. Sometimes trimming is useful, but capping can preserve data while reducing the influence of extreme points.
