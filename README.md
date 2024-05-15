# Data Cleaning Montreal Canadiens
<img src='https://media.d3.nhle.com/image/private/t_ratio16_9-size50/v1698081035/prd/assets/canadiens/assets/3067_Canadiens_com_23-24_05_1920x1080_rouge.jpg'>
<img  src='https://img.shields.io/badge/Colab-F9AB00?style=for-the-badge&logo=googlecolab&color=525252'>

## About 

As a Montreal Canadiens fan, I decided to do a cleaning of the team's data in a public dataset called NHL Stanley Cup Playoffs
The main objective with this process is:
* to do a good cleaning of the data, taking into account null and unimportant values <br />
* understand some characteristics of the team during the playoffs
* answer the following questions:
    1. How did the Montreal Canadiens perform overall in the playoffs over the years?
    2. What was the Montreal Canadiens' best playoff season?
    3. What was the Montreal Canadiens' worst playoff season?
    4. What years did the Montreal Canadiens win the Stanley Cup?
    5. What is the Montreal Canadiens' success rate in playoff series compared to other NHL teams?
    6. What is the average number of goals scored and conceded by the Montreal Canadiens in each playoff season?
    7. How has the Montreal Canadiens' playoff performance changed over the decades?
    8. Who were the Montreal Canadiens' most frequent opponents in the playoffs?
  
The process can be found in the file: Data_Cleaning_MontrealCanadiens.ipynb

## Getting started
First, it's necessary run pandas in your device:
```
import pandas as pd
```
Then, you will need to import the titanic dataset. It's available in this repository as _nhlplayoffs.csv_ or at https://www.kaggle.com/datasets/mattop/nhl-stanley-cup-playoffs-1918-2022
```
titanic = pd.read_csv ('nhlplayoffs.csv')
```

## Your opinion
I'm just curious in the world of data. If you have any suggestions on how to improve the process, feel free to do!
