---
layout: default
title: Generated cohort and survey datasets
parent: Generated data
nav_order: 2
---

# Generated cohort and survey datasets for code testing

## Fake Cohort1 

[Make A Fake Cohort 1](https://github.com/AMNakamura/miscellanea/blob/master/MakeFakeData/MakeAFakeCohort.md) generates a series of sample cohorts from user inputs (cohort start and end dates, sample categorical groupings, and seasonal terms). 
Cohort members are randomly selected to enter and leave the cohort at any time, and to switch group membership mid-way through. Seasonal weights create optional yearly seasonal patterns in the data. 

[Data link](https://github.com/AMNakamura/miscellanea/blob/master/datasets/FakeCohort1.txt)

## Generated surveys

## Fake Survey1

[Make A Fake Survey](https://github.com/AMNakamura/miscellanea/blob/master/MakeFakeData/MakeFakeSurvey1.md) makes use of [MLRun’s demo-stocks “reviews” dataset](https://github.com/mlrun/demo-stocks) for sentiment analysis, topic modeling, and other analyses of text, adding some additional columns with random rating panels.
Customize as needed to mimic data extracted from sources like SPSS or the Qualtrics API, where data will be labeled already (for Qualtrics, for example, the labels will match the survey question text).

[Data link](https://github.com/AMNakamura/miscellanea/blob/master/datasets/SurveyFake1.txt)

