# Getting-And-Cleaning-Data
This repository contains files required in the online course Getting and Cleaning Data, John Hopkins University, Coursera

##run_analysis.R
*This is the script required in the online course Getting and Cleaning Data, John Hopkins University, Coursera.  
It performs the following:
1. Downloads the Human Activity Recognition Using Smartphones Dataset from http://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip.
2. Merges the training and the test sets to create one data set.
3. Extracts only the measurements on the mean and standard deviation for each measurement. 
4. Uses descriptive activity names to name the activities in the data set.
5. Appropriately labels the data set with descriptive variable names. 
6. Creates a second, independent tidy data set with the average of each variable for each activity and each subject and writes it in a text file called tidydata.txt.

## Instructions in running the script: 
1. Copy run_analysis.R to your working directory.
2. In R editor, set your working directory using the setwd() command.
3. Run the script using source("run_analysis.R") command.
4. Find the output file tidydata.txt in the subdirectory myData\UCI HAR Dataset.
