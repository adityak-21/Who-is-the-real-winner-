# State Election Winner Education Level Prediction

## Overview
Classification refers to the task of categorizing data into different classes or categories. In this assignment, we are tasked with predicting the education level of winners of state elections in India based on various features. This task falls under multi-class classification, where the winners' education levels are classified into different categories.

## Problem Statement
The dataset provided contains information about the winners of state and union territory (UT) elections across India. Our goal is to build a machine learning model using the provided training dataset to predict the education level of the winners based on different features.

## Approach
1. **Data Preprocessing:**
    - Load the dataset using Pandas.
    - Perform basic data analysis and visualization using Pandas and Matplotlib/Seaborn.
    - Preprocess the data by handling missing values, encoding categorical variables, and scaling numerical features if required.

2. **Model Selection:**
    - Choose a suitable machine learning model for multi-class classification. Options include SVM, KNN, DecisionTree, RandomForest, etc.
    - Train the selected model on the preprocessed training dataset.

3. **Model Evaluation:**
    - Evaluate the trained model using the F1-score metric on the test dataset.
    - Make predictions on the test dataset and calculate the F1-score to assess the model's performance.

4. **Data Visualization:**
    - Plot the percentage distribution of parties with candidates having the most criminal records.
    - Plot the percentage distribution of parties with the most wealthy candidates.
    - Include any other informative plot for data analysis (bonus points).

5. **Report Generation:**
    - Generate a LaTeX report containing details about the models used, hyperparameters, data analysis plots, final leaderboard score, and rank.
    - Submit the LaTeX report in PDF format with the roll number and name as the filename.