# Analysing Air Quality Features and Predicting PM2.5 Level
***Authors***: Zehao Jiang, Shuai Liu, Haonan Chen
## Abstract
We obtain this dataset from UCI datasets. 
This dataset includes hourly air pollutants data from 12 nationally-controlled air-quality monitoring site. 
We first performed data cleaning, EDA, feature engeneering to fully explore the data. 
Then we use multiple methods trying to predict PM2.5 level using other features. 
We made comparison between different methods and discussed what we can do to further improve in the future.
## Introduction
A vast part of China is experiencing chronic air pollution with severe fine particulate matter(PM) concentration and PM2.5 in particular. PM2.5 is the fine PM with diameter of less than 2.5 μm which leads to great harm to human bodies.

In this study, we conducted analyses on different air quality features and tried to find the relationship between PM2.5 and other air quality variables.

First, we took a look to the data itself and clean it for future analysis. By EDA, we visually found out a lot of information about the variables and had a rough understanding of their relationship. By conducting feature engeneering, we dropped some redundant features and successfully convert time feature to make more sence in our future predicting.

We used linear regression, KNN and random forest to predict PM2.5 level using other variables. We compared their performance and computational efficiency.

At last, we looked back at our study and made some conclusions. Of course there are still works we could do in the future and we would like to explore deeper into this data.

## Description of Data
This data set includes hourly air pollutants data from 12 nationally-controlled air-quality monitoring sites. The air-quality data are from the Beijing Municipal Environmental Monitoring Center. The meteorological data in each air-quality site are matched with the nearest weather station from the China Meteorological Administration. The time period is from March 1st, 2013 to February 28th, 2017. Missing data are denoted as NA.
