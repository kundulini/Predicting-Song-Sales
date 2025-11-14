Music plays a significant role in our digital age, with streaming and social media platforms driving
song sales. Various factors, such as musical features, social trends, and marketing strategies, impact
song sales. Machine learning offers a powerful tool for predicting song sales by analyzing these
features, which can benefit music streaming services. The objective of this assignment is to utilize
machine learning techniques to predict song sales based on musical features.
Implementation Steps
1. Load the dataset and identify categorical and numerical features by counting unique values in
each feature.
2. Analyze the distribution of the target variable and numeric features using suitable charts.
3. Outlier Detection: Discuss the differences between descriptive and prescriptive outlier
detection methods. Identify the suitable method for this problem and explain your choice. Use
box plots to identify columns with outliers and remove them from the dataset.
4. Feature Relationships: Investigate relationships between all features using appropriate charts
and provide detailed explanations.
5. Multicollinearity Analysis: Explain the concept of multicollinearity and discuss suitable
techniques for handling it. Determine if multicollinearity exists in this dataset (without using
charts from Step 4). If present, apply necessary preprocessing steps.
6. Implement Linear Regression: Implement linear regression from scratch and compare the
results and runtime with scikit-learn’s linear regression.
7. Lasso vs. Ridge Regression: Discuss the differences between Lasso and Ridge regression.
Implement both models and compare their performance with the previous linear regression
results.
8. Overfitting Analysis: Explore the possibility of overfitting on the test or validation set.
Discuss methods for detecting and preventing overfitting in this project.
9. Target Intervals for Sales: Consider using intervals for the target value, with each interval
representing a specific category. Divide the target data into intervals of 10,000, where the range
from 0 to 10,000 is labeled as "worst_seller" and 40,000 to 50,000 as "best_seller." Discuss if
using these intervals allows for linear regression or if the problem is better suited for
classification. Analyze potential challenges with this approach.
10. Model Evaluation: Ensure model generalization by evaluating its performance using
appropriate metrics. Analyze errors and provide a detailed report.
11. Suggestions for Improvement: Propose a new idea to improve the performance of the
discussed models (extra poi
