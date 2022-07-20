# DSCI100 - Data Science 100 Project

## Goal
Determine which factors have the most positive impact on a movie's "success", which is determined in part by revenue generated.

## Methods
This project imports data from Kaggle's API using the httr library. Data for ~45000 movies is wrangled and cleaned. Exploratory analysis determined the most impactful variables to study. K-nearest neighbor (a non-parametric supervised learning classifier) is used to determine which variables, and in what combinations, are most positively impactful.

## Packages Used
tidyverse  
repr  
jsonlite  
purrr  
tidymodels  
gridExtra  
httr  
GGally  
dplyr  
cowplot  