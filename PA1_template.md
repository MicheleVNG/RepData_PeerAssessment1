# Reproducible Research: Peer Assessment 1


## Loading and preprocessing the data

Load required libraries


```r
suppressPackageStartupMessages(library(tidyverse))
suppressPackageStartupMessages(library(lubridate))
```

Import the data and clean the date variable:


```r
unzip("activity.zip")
activityData <- read.csv("activity.csv")
activityData$date <- ymd(activityData$date)
```


## What is mean total number of steps taken per day?



## What is the average daily activity pattern?



## Imputing missing values



## Are there differences in activity patterns between weekdays and weekends?
