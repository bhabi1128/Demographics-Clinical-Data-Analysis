# Demographics-Clinical-Data-Analysis
## ABSTRACT

Obsessive-Compulsive Disorder (OCD) is a complex mental health condition characterized by recurring obsessions and compulsions. Understanding the relationship between demographic factors, clinical symptoms, and comorbid conditions is essential for early diagnosis and treatment planning.

This project analyzes a dataset of 1500 OCD patients containing demographic attributes, clinical scores (Y-BOCS), symptom duration, comorbid diagnoses, and medication history. Exploratory Data Analysis (EDA) was performed to discover trends, identify severity patterns, and understand correlations between obsession and compulsion scores.

A machine learning model was also developed to predict OCD severity (High vs Low) using demographic and clinical variables. The project highlights key insights about patient behavior, major risk contributors, and potential clinical indicators that can support mental health professionals.

## PROJECT OVERVIEW

This project focuses on understanding OCD patients through data-driven insights. The dataset includes details such as age, gender, marital status, education level, symptom duration, obsession types, compulsion types, Y-BOCS scores, and comorbidities like depression and anxiety.

The workflow includes

Data cleaning and preprocessing

Statistical and visual Exploratory Data Analysis

Correlation study between obsession and compulsion scores

Predictive modeling for OCD severity

Interpretation of results and final insights

The project helps identify how demographic factors and clinical symptoms influence OCD severity and how comorbid conditions impact patient outcomes.
<br>
<br>

## PROJECT GOALS
<b>Primary Goals</b>

To analyze demographic and clinical patterns of OCD patients.
<br>
To understand the relationship between Y-BOCS Obsession and Compulsion scores.
<br>
To study comorbidities such as Depression and Anxiety.
<br>
To identify key factors contributing to OCD severity.
<br>
To build a machine learning model that predicts OCD Severity (High vs Low).
<br>
<b>Secondary Goals</b>

To visualize important correlations using heatmaps and scatter plots.
<br>
To understand how gender, age, and symptom duration affect OCD symptoms.
<br>
To evaluate feature importance to understand which variables strongly impact severity.
<br>
To convert findings into meaningful clinical interpretations.
<br>
<br>

## ALGORITHM USED
Machine Learning Algorithms Used:

⭐ Random Forest Classifier (Recommended)

Used for predicting OCD severity (High vs Low).
Random Forest works using multiple decision trees and provides high accuracy, handles categorical data well, and identifies the most important features.

Why Random Forest?

Works well with mixed data (categorical + numerical)

Handles missing values

Reduces overfitting

Provides feature importance ranking
<br>
<br>

## CONCLUSION

This project provides meaningful insights into the demographics and clinical characteristics of OCD patients. Analyzing Y-BOCS scores revealed a strong correlation between obsessions and compulsions, showing that increased obsession severity typically leads to increased compulsive behaviors. Symptom duration and comorbid conditions (depression and anxiety) also played an important role in determining overall OCD severity.

The machine learning model successfully predicted OCD severity based on patient demographic and clinical features. Random Forest delivered strong performance and helped identify key factors influencing the condition.

Overall, the project demonstrates how data science and machine learning can support mental health assessment, assist clinicians, and provide early indicators of severity.

## FUTURE WORK

Build advanced prediction models (XGBoost, Deep Learning) to improve accuracy.

Develop a clinical dashboard for real-time prediction and monitoring.

Incorporate more physiological and behavioral data for better predictions.

Analyze treatment effectiveness over time using longitudinal data.

Build a symptom progression model to predict future severity.

Integrate NLP to analyze patient therapy notes or clinical text.
