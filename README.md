# Student Scores Analysis

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10-blue?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Jupyter-Notebook-orange?style=flat-square&logo=jupyter&logoColor=white" />
  <img src="https://img.shields.io/badge/Pandas-Data%20Analysis-green?style=flat-square&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/Seaborn-Visualization-blueviolet?style=flat-square" />
  <img src="https://img.shields.io/badge/Scikit--Learn-Regression-yellow?style=flat-square&logo=scikitlearn&logoColor=black" />
  <img src="https://img.shields.io/badge/Dataset-Kaggle-red?style=flat-square&logo=kaggle&logoColor=white" />
</p>

Exploratory Data Analysis (EDA) on a dataset of student exam scores.

## Dataset
Students Performance in Exams (Kaggle)

## Goal
This project aims to explore and analyze student exam scores using exploratory data analysis techniques.
The analysis focuses on score distributions, group comparisons, and relationships between subjects,
with potential future extensions toward predictive modeling.

## Key Analysis Steps
- Data loading and initial exploration
- Feature engineering (average score calculation)
- Group-based analysis by gender, parental education level, and test preparation course
- Data visualization using histograms, box plots, and scatter plots
- Correlation analysis between exam scores
- Simple linear regression to predict writing scores based on math scores

## Tools Used
- Python
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## Conclusion
This analysis shows that reading score is one of the strongest indicators of writing performance,
and test preparation is associated with better results.

## Detailed Summary
This analysis explored student performance across math, reading, and writing using a structured exploratory data analysis workflow. After inspecting the dataset, an overall performance metric (average_score) was created to better compare students across subjects. Several group-based analyses revealed meaningful patterns in the data.

The comparison of average scores by gender showed slight differences in central tendency and distribution, although no formal significance testing was performed. A stronger pattern appeared when examining the impact of the test preparation course: students who completed the course consistently achieved higher scores, suggesting that the program may positively influence academic performance.

The correlation study revealed strong relationships between all three exam scores, with reading and writing showing the strongest association—consistent with the linguistic nature of these subjects. Math also showed a positive correlation, though less pronounced. Additionally, parental education level demonstrated a clear upward trend: students with more highly educated parents generally performed better on average.

A more detailed explanation of each step is available directly in the notebook’s code cells.
