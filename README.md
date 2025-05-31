# health-lifestyle-analysis-01
Exploring the impact of sleep, stress, and activity on health outcomes using Python, EDA, and statistical testing.
Health & Lifestyle Data Analysis
Author: Basit Shah
Course: DS204 – Applied Data Science
Date: May 30, 2025

Project Overview
This project explores how lifestyle behaviors—such as sleep duration, physical activity, and stress level—affect overall health outcomes like BMI, heart rate, and sleep quality. Using a real-world dataset sourced from Kaggle, we applied statistical methods and data visualization techniques to uncover key health insights that can inform personal habits and public health strategies.

Dataset Information
Source: Sleep Health and Lifestyle Dataset

Link: https://www.kaggle.com/datasets/uom190346a/sleep-health-and-lifestyle-dataset

Variables included:
Age, Gender, Occupation, Sleep Duration, Quality of Sleep, Physical Activity Level, Stress Level, Daily Steps, Heart Rate, BMI Category, and Sleep Disorder status

Objectives
Investigate whether certain health behaviors predict poor sleep or stress

Identify correlations between numerical health indicators

Determine if health metrics differ by gender, BMI, or activity level

Provide meaningful real-world health insights from data

Methods Used
Data Cleaning and Preprocessing using Pandas

Exploratory Data Analysis (EDA)

Statistical Hypothesis Testing:

Independent t-test

One-way ANOVA

Pearson, Spearman, Kendall Tau, Phi, and Point-Biserial correlations

Data Visualization with Matplotlib and Seaborn

Key Results
Sleep Disorder vs. Sleep Duration
T-test showed that individuals with sleep disorders sleep significantly fewer hours on average.
p-value: < 0.001

Stress Level by BMI Category
ANOVA indicated that stress levels significantly differ among BMI categories.
p-value: 0.0072

Physical Activity vs. Stress Level
T-test found no significant difference in stress levels between high and low activity individuals.
p-value: 0.7181

Correlation Analysis Highlights

Age and Heart Rate: Moderate negative Pearson correlation (r = -0.226)

Physical Activity and Sleep Quality: Weak but significant Spearman correlation (ρ = 0.178)

Stress and Sleep Quality: Strong negative monotonic relationship (τ = -0.826)

Gender and Sleep Disorder: Positive Phi correlation (φ = 0.280)

Visualizations
The following visualizations were used to support findings:

Boxplot of Sleep Duration by Sleep Disorder

Boxplot of Stress Level across BMI Categories

Correlation heatmap showing relationships between numerical features

Scatterplot of Stress vs. Sleep Quality

These can be found in the /charts/ directory of this repository.

Real-World Implications
This analysis suggests that:

Managing stress can significantly improve sleep quality and heart health.

Sleep disorder awareness is critical for improving daily functioning and well-being.

BMI is not just physical—it links closely with mental stress levels.

While physical activity is important, mental wellness has a deeper impact on sleep and stress metrics.

These insights can help guide health education, workplace wellness programs, and personal habit tracking.

Project Files
Health_Lifestyle_Analysis.ipynb – Jupyter/Colab notebook with full analysis

Sleep_health_and_lifestyle_dataset.csv – CSV dataset

Explained_Styled_Health_Lifestyle_Presentation_Basit_Shah.pptx – Final presentation slides



README.md – This project summary

How to Run This Project
Clone or download the repository

Open the Health_Lifestyle_Analysis.ipynb notebook in Google Colab or Jupyter Notebook



Presentation
The final presentation slides summarizing the methodology, charts, and key findings are available in this repository as a PowerPoint file. You can use them for a classroom presentation or stakeholder meeting.
