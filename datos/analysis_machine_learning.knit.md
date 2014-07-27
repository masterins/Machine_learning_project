---
title: "analysis_machine_learning"
author: "Mario Jimenez Garcia"
date: "Sunday, July 27, 2014"
output: html_document
---
Introduction

The goal of your project is to predict the manner in which they did the exercise. This is the "classe" variable in the training set. You may use any of the other variables to predict with. You should create a report describing how you built your model, how you used cross validation, what you think the expected out of sample error is, and why you made the choices you did. You will also use your prediction model to predict 20 different test cases. 

Firts I need to read and put in correct format the data, for this using a readData function

readDatas <- function(file) 
{
    df <- read.csv(file,header=TRUE,na.strings=c("NA", "", "#DIV/0!"),sep=",")
}


After  thing I will do is load the data



