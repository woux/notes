# Stat 331

## Introduction

Midterm 1: Wed, May 30, 9:30-11:20am

Midterm 2: Wed, June 27, 9:30-11:20am

## Chapter 1

Regression modelling is an activity that leads to a mathematical description of a process in terms of a set of associated variables. 

Two types of relationships. 

Deterministic (or functional) model: 
- No allowance for statistical or measurement error, has no variance or uncertainty
- If we know the value of x, we know the value of y
- unit conversions, known science formulas
- By ignoring what seems irrelevant for a specific purpose, we get simplicity or tractability.

```r
t <-1:5 # assign ‘t' variable the values 1, 2, 3, 4, 5 (time in seconds)
d <-0.5*9.8*t^2 # apply formula to obtain the distance ‘d‘
plot(d~t, xlab="Time(sec)", ylab="Distance fallen (m)", pch =16, col="red", main=" Falling.rock example")
lines( spline(t,d),col="blue") # pass a smooth curve through the points.
```
 