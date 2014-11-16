---
title: "PA1"
author: "Bernhard Thoni"
date: "Friday, November 14, 2014"
output: html_document
---

0. Task: some prerequisites here (loading libraries, setting options, etc)


1. Task: Loading and preprocessing the data

```r
my_data<-read.csv("activity.csv",header=TRUE)   
head(my_data)
```

```
##   steps       date interval
## 1    NA 2012-10-01        0
## 2    NA 2012-10-01        5
## 3    NA 2012-10-01       10
## 4    NA 2012-10-01       15
## 5    NA 2012-10-01       20
## 6    NA 2012-10-01       25
```

```r
tail(my_data)
```

```
##       steps       date interval
## 17563    NA 2012-11-30     2330
## 17564    NA 2012-11-30     2335
## 17565    NA 2012-11-30     2340
## 17566    NA 2012-11-30     2345
## 17567    NA 2012-11-30     2350
## 17568    NA 2012-11-30     2355
```

```r
plot(my_data)
```

![plot of chunk chunk_task1](./figures/chunk_task1-1.png) 

2. Task: Mean total Number of steps taken per day


