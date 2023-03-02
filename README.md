# UTSA 20: Unsupervised Machine Learning Challenge

## Background
### You are on the data science team of a medical research company that’s interested in finding better ways to predict myopia, or nearsightedness. Your team has tried—and failed—to improve their classification model when training on the whole dataset. However, they believe that there might be distinct groups of patients that would be better to analyze separately. So, your supervisor has asked you to explore this possibility by using unsupervised learning.

### You have been provided with raw data, so you’ll first need to process it to fit the machine learning models. You will use several clustering algorithms to explore whether the patients can be placed into distinct groups. Then, you’ll create a visualization to share your findings with your team and other key stakeholders.

## Results and Recommendation
### Results: Neither the t-SNE nor K-means models are able to provide distinct clusters to predict whether a child will develop myopia.

### Analysis: As the dataset contains 12-14 variables (depending on the algorithm being tested), the algorithms must attempt to make complex predictions.  However, the dataset itself contains only 617 samples, which most likely contributes to the inability to find sufficient patterns to make predictions.  This failure is ultimately likely the result of a woefully inadequate sample size.

### Recommendation: The patients cannot be distinctly clustered, likely because the sample size is too small to provide enough data to train the models for prediction.  Either a larger dataset should be used or more data must be gathered.  The models can then be reapplied to look for patterns to make prediction possible.
