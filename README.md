# Churn-Analysis

This is a repository containing all the technical contents for a typical churn analysis, which is common in data science. In this case the data and a set of instructions was provided by Boston Consulting Group, to simulate the experience of working as a data scientist within a consulting firm.

There are two csv files that are given, client and price data, and one created later, labeled 'churn_dataset'.
There are three Jupyter notebooks I created, which go step by step over the data science process, beginning with Exploratory Data Analysis, then moving on to Feature Engineering, and then Model Building.

For the Feature Engineering section, some of the code may not have the best readability because it is highly optimized for large datasets, computing all grouped operations for individual consumers across 1.3M rows of data within 0.1 seconds.

For the model building section, I used Yggdrasil Decision Forests, a successor and similar package to tensorflow_decision_forests.
