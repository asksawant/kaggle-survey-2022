# kaggle-survey-2022

[![install package][22]](https://app.powerbi.com/view?r=eyJrIjoiYzk4MzdkNTItZmUxYS00ZjFmLWFjYjUtMWY5MzQxM2Q0YjU1IiwidCI6IjU3OGQ5ZjNlLTlkMTItNDBiMi1hNjJlLWI3NzdiZGYyNTVhMiJ9)
[![use template][23]](https://www.kaggle.com/code/asksawant/macro-analysis-of-kaggle-survey-2022-using-heatmap)

[22]: https://custom-icon-badges.demolab.com/badge/-Check%20Dashboard-gold?style=for-the-badge&logo=package&logoColor=black
[23]: https://custom-icon-badges.demolab.com/badge/-EDA%20Notebook-teal?style=for-the-badge&logo=repo-template&logoColor=white

## Objective
- Macro level data analysis process which is reproducible every year to analyze and derive insights from the survey.
- Dashboard which will allow stakeholders to understand the impact, priorities or concerns of a group of DS/ML practitioners.

## Data Preparation
### Data Source
- Kaggle platform - flat excel file

### Data Cleaning
- Manually checking questions are similar in previous year surveys.
- Concatenating similar questions with the current year survey.
- Add a year column to identify the survey.
- Add a unique key to identify each respondent.
- Formatting the previous year survey answers as per the recent survey.

### Data formating
- Creating a dataset with melted format having question and answer as rows for each respondent.
- Identifying and creating facts and dimensions table for the dashboard.

## Data Analysis
- Methodology
  - Classifying the questions
    - Based on the kind of question asked: Single choice or Multiple choice
    - Based on the idea behind the question: learning, machine learning, etc.
  - Macro level analysis of questions
    - If the question is the single choice
      - Check the distribution using the heatmap
    - If the question is multiple-choice. We will analyze it in three directions.
      - How many products/services/platforms etc did the respondent mention
      - Which products/services/platforms etc did the respondent mention together (by creating an occurrence matrix)
      - Checking the distribution using heatmap.
      
Implemented macro level analysis of all the questions of survey using only Heatmaps.<br>
[![use template][23]](https://www.kaggle.com/code/asksawant/macro-analysis-of-kaggle-survey-2022-using-heatmap)

## Dashboard
[![install package][22]](https://app.powerbi.com/view?r=eyJrIjoiYzk4MzdkNTItZmUxYS00ZjFmLWFjYjUtMWY5MzQxM2Q0YjU1IiwidCI6IjU3OGQ5ZjNlLTlkMTItNDBiMi1hNjJlLWI3NzdiZGYyNTVhMiJ9)

