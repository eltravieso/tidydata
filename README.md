# Getting and Cleaning Data Final Assignment

## Assignment Directions
You should create one R script called run_analysis.R that does the following. 

- Merges the training and the test sets to create one data set.
- Extracts only the measurements on the mean and standard deviation for each measurement. 
- Uses descriptive activity names to name the activities in the data set
- Appropriately labels the data set with descriptive variable names. 
- From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

## Package Setup

- Create folder called tidydata and save source files() in this folder
- Set tidydata folder as working directory

## Package Description
- Load training data into three data frames and then combine them into one
- Load test data into three data frames and then combine them into one
- Combine training and test data into one data frame 

- Load features file into data frame and collect the desired rows
- Select desired columns from combined data using the select features in previous step

- Load activity file and use the values to update the ids in the combined data
- Rename the activity column with a descriptive name

- loop through the columns in the combined data and replace the names using the selected features

- Create new data frame with the average of each column grouped by Activity and Subject
- Remove unwanted columns
- Output results into text file   
