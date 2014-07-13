Getting and Cleaning Data: Course Project
===

Introduction
------------
Repo contains work for Course project for Coursera course "Getting and Cleaning data".

Raw data
------------------

The features (561) are unlabeled and can be found in the x_test.txt. 
The activity labels are in the y_test.txt file.
The test subjects are in the subject_test.txt file.

Above is true also for the training set.

Script and tidy dataset
-------------------------------------
A script called run_analysis.R merges the test and training set.
Before running,

1. the UCI HAR Dataset must be extracted 
2. the UCI HAR Dataset must be availble in a directory called "UCI HAR Dataset"

After merging testing and training, labels are added and only columns that have to do with mean and standard deviation are kept.

The script creates a tidy data set containing the means of all the columns per test subject and per activity.

Code Book
-------------------
CodeBook.md file explains the transformations performed and the resulting data and variables.
