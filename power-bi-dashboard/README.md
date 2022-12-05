# PowerBI Dashboard: Kaggle Survey 2022

Dashboard which allows the audience to analyze and understand the the impact, priorities or concerns of a group of DS/ML practitioners.

## Link of the dashboard:
[![portfolio](https://img.shields.io/badge/%F0%9F%94%97-Go%20to%20Dashboard-lightgrey?style=for-the-badge)](https://app.powerbi.com/view?r=eyJrIjoiYzk4MzdkNTItZmUxYS00ZjFmLWFjYjUtMWY5MzQxM2Q0YjU1IiwidCI6IjU3OGQ5ZjNlLTlkMTItNDBiMi1hNjJlLWI3NzdiZGYyNTVhMiJ9)

[![Dashboard](https://github.com/asksawant/kaggle-survey-2022/blob/main/power-bi-dashboard/assets/dashboard-gif.gif)](https://app.powerbi.com/view?r=eyJrIjoiYzk4MzdkNTItZmUxYS00ZjFmLWFjYjUtMWY5MzQxM2Q0YjU1IiwidCI6IjU3OGQ5ZjNlLTlkMTItNDBiMi1hNjJlLWI3NzdiZGYyNTVhMiJ9)

Note: _I have made the dashboard for only 1 question. Though there are totel 43 questions in the dataset. The personal aim of the project is to 
demonstrate the PowerBI skills._

## Designing Dashboard

### Problem Definition

#### Goal of the Dashboard

A dashboard which will allow audience to understand the impact, priorities or concerns of a group of DS/ML practitioners.

#### Determine the audience’s analytical maturity

Audience using the dashboard are Data Science & Machine learning students or professionals. As the audience is technical sound we can create an interactive dashboad.

#### Determine the Dashboard content

Home page: will help audience to navigate to various questions present in the power Bi report

Report pages: will help audience to analyze the impact, priorities or concerns of a group for the pariticular question.

Should contain the following elements:

- Filters - which can filter the population to the desired group
- Size of the selected group
- Answers(Products, Platforms, Tools etc) mentioned together by the selected group
- Top 5 Answers(Products, Platforms, Tools etc) for the question
- Distribution of the Answers(Products, Platforms, Tools etc) for the question for last five years
- Trend of the Answers(Products, Platforms, Tools etc) for last five years

#### Determine the Views to answer the questions

|Question| View |
|--|--|
| Size of the selected group | BANS or CARDS |
| Answers(Products, Platforms, Tools etc) mentioned together by the selected group:| MATRIX |
| Distribution of the Answers(Products, Platforms, Tools etc) for the question for last five years | MATRIX |
| Top 5 Answers(Products, Platforms, Tools etc) for the question | BAR Chart |
| Trend of the Answers(Products, Platforms, Tools etc) for last five years | LINE Chart |
| Filtering the population | SLICERS |
| Reseting the filters | BUTTON |
| Go back to homepage | BUTTON |
| Change view from percent to count | BUTTON |

### Design

#### Getting the inspiration for design

Using Pinterest for the design inspiration

#### Creating the template

- Tools: Figma
- Size: 1300 x 800 px
- Color palatte
![Dashboard](https://github.com/asksawant/kaggle-survey-2022/blob/main/power-bi-dashboard/assets/color-palette.png)
- Selecting the font
- Output of the template design

#### Dashboard Design and Deployement

Steps

- Loading the required data in the Power BI
    - Loaded the data throught Text/CSV files
- Cleaning or Transforming the data (if required)
    - Use first row as header
    - Datatype of data column in the fact table
- Power BI modelling
    - Checking the relationships between the Fact and Dimension table
[![Datamodeling](https://github.com/asksawant/kaggle-survey-2022/blob/main/power-bi-dashboard/assets/power-bi-data-modeling.jpg)]
- Creating the measures for the questions using DAX
[![Dax](https://img.shields.io/badge/%F0%9F%94%97-Go%20to%20DAX_File-lightgrey?style=for-the-badge)](https://github.com/asksawant/kaggle-survey-2022/blob/main/power-bi-dashboard/Dax-measures)
