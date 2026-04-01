# Student Performance Predictor

This project uses machine learning to predict whether a student will pass or fail based on personal, social, and academic factors.

## Project Overview

The dataset was taken from the UCI Student Performance dataset.  
A Random Forest classifier was trained to predict student performance using processed student-related features.

## Tools and Libraries

- Python
- Google Colab
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## Project Steps

1. Loaded and explored the dataset
2. Checked data types and missing values
3. Created a classification target column called pass
4. Removed grade columns that could leak the answer
5. Encoded categorical variables
6. Split the data into training and testing sets
7. Trained a Random Forest classifier
8. Evaluated the model using accuracy, classification report, and confusion matrix

## Result

The model achieved an accuracy of about *72%*.

The model performed better at identifying students who passed than students who failed. This shows that the dataset is slightly imbalanced and that future improvement could involve model tuning or handling class imbalance more carefully.

## Files in This Repository

- requirements.txt - project dependencies
- student_performance_predictor.ipynb - complete notebook with code, results, and visualizations

## Dataset Source

UCI Machine Learning Repository - Student Performance Dataset
