# Variable Descriptions

Source of where the data was obtained - http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones
Original source data - https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

y_train - used to hold the data from the file y_train.txt
X_train - used to hold the data from the file X_train.txt
subject_train - used to hold the data from the file subject_train.txt
traindata - Used to store the combined data of the training variables

y_test - used to hold the data from the file y_test.txt
X_test - used to hold the data from the file X_test.txt
subject_test - used to hold the data from the file subject_test.txt
testdata - Used to store the combined data of the training variables
    
comData - Used to hold the combined data from the variables traindata and testdata

features - used to hold the data from the file features.txt
selFeat - Used to hold the selected features from the features variable

comData - Reused to store only the select feature columns

activity_labels - used to hold the data from the file activity_labels.txt

tidydata - Used to store the aggregate data from the comData. The aggregate used is mean. The calculation is performed at the activity/subject grouping
