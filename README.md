# Student Performance Analysis

## Overview
This project analyzes how student habits relate to exam performance using EDA and regression modeling. The  goal is to identify which factors have independent effects on exam score after accounting for confounding variables.

## Dataset
- Source: Student Habits vs Academic Performance (public dataset on Kaggle) 
- Observations: 1,000 students
- Target variable: Exam score

## Methods
- Data cleaning and preprocessing
- Exploratory analysis (correlation heatmaps and scatter plots)
- Linear regression for interpretable coefficient estimates
- Random forest regression for comparison
- Train/test split with fixed random seed for reproducibility

## Key Findings
- Study hours per day shows the strongest independent association with exam score when other variables are held constant
- Mental health rating, Netflix hours, and social media hours exhibit weaker but non-zero effects. Mental health rating being the strongest of the three
- Linear regression provides clearer interpretability and outperformed random forest on this dataset

## Results
- 📊 Full analysis: [student_performance.ipynb](student_performance.ipynb)
- 📄 Final report: [Student Performance Report](report/Student_Performance_Report.pdf)


## Tools
Python, pandas, numpy, matplotlib, seaborn, scikit-learn
