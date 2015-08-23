# This readme file is an overview for a course project for the Johns Hopkins Coursera course Getting and Cleaning Data

## Project Assignment
Create an R script named run_analysis.R that does the following.
1. Merges the training and the test sets to one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement.
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive activity names.
5. Creates a second, independent tidy data set with the average of each variable for each activity and each subject.

## To Complete the Project
1. Download the data source and put into a folder on your local drive. You'll have a ```UCI HAR Dataset``` folder.
2. Put ```run_analysis.R``` in the parent folder of ```UCI HAR Dataset```, then set it as your working directory using ```setwd()``` function in RStudio.
3. Run ```source("run_analysis.R")```, then it will generate a new file ```tiny_data.txt``` in your working directory.

## Dependencies
```run_analysis.R``` file will help you to install the dependencies automatically. It depends on ```reshape2``` and ```data.table```. 
