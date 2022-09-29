---
title: "README"
author: "yannihpl"
date: "9/29/2022"
---

Getting and Cleaning Data Course Project - Peer-graded Assignment
This README file is yannihpl's submission for assignment project. Included are the instructions on how to generate tidy datasets.

Dataset
Human Activity Recognition Using Smartphones

Codebook
CodeBook.md is the codebook that describes the datasets, variables, and transformations conducted

The R script called run_analysis.R performs the data preparation following the 5 steps specified in the course project’s definition:
- Merges the training and the test sets to create one data set.
- Extracts only the measurements on the mean and standard deviation for each measurement.
- Uses descriptive activity names to name the activities in the data set
- Appropriately labels the data set with descriptive variable names.
- From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

The newly generated tidy dataset (DataFinal) contained variables calculated based on the mean and standard deviation. Each row of the dataset is an average of each activity type for all subjects. 