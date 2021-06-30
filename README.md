---
title: "Getting and Cleaning Data Week 4 Course Project"
author: "Dom Foord"
date: "29/06/2021"
output:
  html_document:
    df_print: paged
---

## Getting and Cleaning Data Week 4 Course Project

This repo was created as part of the Week 4 assignment for the Getting and Cleaning Data Coursera course. The instructions for the assignment are as follows:

* We download the corresponding data from https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip  
* We create one R script called run_analysis.R that does the following. 

1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement. 
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive variable names. 
5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

The repo consists of four files - a zip file containing the data, the R Script file run_analysis.R, a codebook containing an explanation of all the analysis run on the data, and this readme.

## Data description

The variables in the X data are sensor signals generated from waist-mounted smartphones on 30 subjects. The Y data indicates the type of action undertaken.

## Running Instructions

To get the file run_analysis.R working, simply download all the files into your working directory/clone the repo and run the file. It generates a dataset containing variables based on the mean and standard deviation of the Y variables. It will then generate the file tidydata.txt, the required output of the assignment.
