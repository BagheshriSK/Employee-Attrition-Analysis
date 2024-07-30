# Employee-Attrition-Analysis

# Introduction

In the business context, employee attrition refers to the phenomenon where employees leave a company for various reasons such as finding new employment or retirement, without immediate replacement. A company's success heavily depends on its ability to not only attract but also retain top talent. The objective of this project is to analyze a dataset containing information about a company's employees to uncover patterns that can help understand the reasons behind employee attrition.

# Data Treatment

The initial steps involved treating the data by addressing missing values and assigning meaningful names to categorical variables that were initially labeled numerically.

# Data Visualization

Following data treatment, Plotly was used for data visualization to identify patterns related to employee attrition.

# Model Building

The dataset was then split into training and testing sets to build a classification model, with necessary treatments like variable encoding, feature rescaling, and handling imbalanced classes. A search for optimal hyperparameters was conducted to improve model performance.

# Results

The Gradient Boosting Classifier achieved the highest accuracy score of 88.44% after hyperparameter tuning, while the Ada Boost Classifier initially had the best recall score of 62.69%.

# Conclusion

Further tuning of the Ada Boost Classifier increased the recall score to 83.58%, though this resulted in a decrease in accuracy and an increase in false positives, indicating potential bias in the model.
