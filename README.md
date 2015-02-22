# Machine Learning Course Project

*Johns Hopkins University Coursera Data Science Specialization*

Please find the course project report on GitHub pages here:

http://mattmdedek.github.io/jhu-mach-learn-2/


## Overview

This repository holds work for the final course project for the *Practical Machine Learning* course of Johns Hopkins University's Coursera Specialization in Data Science. The goal of the project is to creat a model in R to predict whether an athlete is performing bicep dumbbell curls correctly. The data used to build and evaluate the model was obtained through Johns Hopkins University from the Human Activity Recognition Project:

groupware.les.inf.puc-rio.br/har


This data consists of readings from four 9-axis inertial measurement units (IMUs) placed on the subjects' waist, arms, forearms and dumbbells during exercise. Six subjects each performed 10 repititions of the dumbbell curl following instructions on five variations of exercise - one of correct form and four of incorrect form.

## Results of the Project

Three predictive models were built using the caret package in R:

* Classification and Regression Trees
* Stochastic Gradient Boosting with Cross-Validation
* Random Forests

The Random Forest model had the best performance with an estimated out-of-sample accuracy of 95.9%

## Contents of Repository

Files:

* MachineLearningCourseProject.Rmd - An R-Markdown document containing all of the R code used to generate and evaluate the predictive models.
* MachineLearningCourseProject.html - The compiled R-markdown document. This is also published on GitHub pages.

Directories:

* data/ Testing and Training data files (.csv)
* models/ Cached R objects of predictive models. The Stochasitic Gradient Boosting and Random Forest models take a very long time to build, so they are cached here
* submission/ Files containing answers to the graded submission portion of this course project.



