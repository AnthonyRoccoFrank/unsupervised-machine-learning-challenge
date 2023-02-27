# Unsupervised Machine Learning Challenge

## Background

You are on the data science team of a medical research company that’s interested in finding better ways to predict myopia, or nearsightedness. Your team has tried—and failed—to improve their classification model when training on the whole dataset. However, they believe that there might be distinct groups of patients that would be better to analyze separately. So, your supervisor has asked you to explore this possibility by using unsupervised learning.

You have been provided with raw data, so you’ll first need to process it to fit the machine learning models. You will use several clustering algorithms to explore whether the patients can be placed into distinct groups. Then, you’ll create a visualization to share your findings with your team and other key stakeholders.

## Part 1: Prepare the Data

* Read <code>myopia.csv</code> into a Pandas DataFrame.
**Note: This file can be found in your Module 20 Challenge files.
*Remove the "MYOPIC" column from the dataset.
**Note: The target column is needed for supervised machine learning, but it will make an unsupervised model biased. After all, the target column is effectively providing clusters already!
*Standardize your dataset so that columns that contain larger values do not influence the outcome more than columns with smaller values.
