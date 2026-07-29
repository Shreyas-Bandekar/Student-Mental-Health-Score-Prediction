# Student Mental Health Score Prediction

Exploratory data analysis notebook for studying how student social media habits and lifestyle factors relate to mental health score.

## Overview

The project is centered around the notebook [mental_health_score.ipynb](mental_health_score.ipynb), which loads a dataset of student social media and mental health indicators, inspects the data, and visualizes the relationship between features such as daily usage, study time, sleep, stress, and the target variable `Mental_Health_Score`.

## Dataset

The notebook expects the CSV file `Student Social Media And Mental Health Impact.csv` to be available in the same folder.

The dataset contains 5,000 rows and 13 columns, including:

- `Age`
- `Gender`
- `Country`
- `Academic_Level`
- `Most_Used_Platform`
- `Purpose_Of_Use`
- `Avg_Daily_Usage_Hours`
- `Daily_Unlocks`
- `Study_Hours`
- `Physical_Activity_Hours`
- `Sleep_Hours_Per_Night`
- `Stress_Level`
- `Mental_Health_Score`

## What The Notebook Does

- Loads the CSV into a pandas DataFrame.
- Displays basic structure and data quality checks.
- Explores the distribution of `Mental_Health_Score`.
- Compares `Mental_Health_Score` across `Stress_Level` groups.
- Visualizes the relationship between screen time and mental health score.

## Requirements

Use Python 3 with the following libraries:

- numpy
- pandas
- matplotlib
- seaborn

## How To Run

1. Open [mental_health_score.ipynb](mental_health_score.ipynb) in Jupyter Notebook, JupyterLab, VS Code, or Google Colab.
2. Make sure `Student Social Media And Mental Health Impact.csv` is in the same directory as the notebook.
3. Run the cells from top to bottom.

## Notes

- The notebook was created for exploratory analysis and visualization.
- If you want to turn this into a predictive modeling project, the next step would be to add preprocessing, train/test split, model training, and evaluation metrics.