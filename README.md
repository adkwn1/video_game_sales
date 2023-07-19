## Video Game Sales
Author: Andrew Kwon

## Description

Exploratory and statistical data analysis project on global video game sales from 1980-2016. Project performs the following:
- Data cleaning
- Statistical analysis
- Correlation analysis
- Visualization
- Hypothesis testing of population means

Project code, comments, and analysis conducted in Jupyter notebook.

## Introduction

This project processes and analyzes historical data for video game sales up to the year 2016. The scope of the analysis for this project is to determine any patterns that could assist an advertisement campaign that would improve profitability of video game sales for the following year. Additionally, we'll run two hypothesis tests (population means) to aid our decision on what recommendations we should make as a result of our analysis.

## Dataset

**games.csv**
- *Name*: game title
- *Platform*: platforms of release
- *Year_of_Release*: Year game was released on specified platform
- *Genre*: game genre
- *NA_sales*: units sold in North America (in millions)
- *EU_sales*: units sold in Europe (in millions)
- *JP_sales*: units sold in Japan (in millions)
- *Other_sales* units sold in other regions (in millions)
- *Critic_Score*: profession game critic score (out of 100)
- *User_Score*: user score (out of 10)
- *Rating*: Entertainment Software Rating Board (ESRB) rating (https://www.esrb.org/ratings-guide/)

## Requirements

- pandas
- numpy
- plotly.express
- scipy.stats

## Screenshots

![yearly_sales](https://github.com/adkwn1/video_game_sales/assets/119823114/cadda6b5-5abf-45ee-90e4-be8b2cf61384)
![release_by_year](https://github.com/adkwn1/video_game_sales/assets/119823114/5b0a8786-ad2b-4dbe-b5f2-3bfdacca31db)
![sales_by_platform](https://github.com/adkwn1/video_game_sales/assets/119823114/519b0373-5e12-472f-aa64-48916ea67fd3)
![sale_by_genre](https://github.com/adkwn1/video_game_sales/assets/119823114/10e2e3ed-3fe6-4b6f-a935-f3aa8f17f264)
![corr_user](https://github.com/adkwn1/video_game_sales/assets/119823114/0aabf97b-80d4-4046-a2de-36d6ef8c08c2)
![corr_critic](https://github.com/adkwn1/video_game_sales/assets/119823114/9b1f231f-3786-49b2-911f-6d3a059c1762)
