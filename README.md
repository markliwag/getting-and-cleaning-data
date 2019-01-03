# getting-and-cleaning-data
Peer review assignment 


Getting and Cleaning Data - Coursera

Programming assignment (peer review)

Data are collected from accelerometer and gyroscope of the Samsung Galaxy S smartphone. This data will be cleaned to prepare a tidy data set for 
later analysis. 

The repository has: 
Readme.md - provides an overview of data set and what to do with it. 
tidydata.txt - contains cleaned data set
Codebook.md - describes contents of data set
run_analysis.R - R script used to create the data set

The data set came from Human Activity Recognition using Smartphones Data Set. 

Training and test data were merged first, then measurement on the mean and standard deviation for each measurement were extracted, then measurements were 
averaged for each suject and activity, resulting in the final data set. 

Creating the tidy data set: 

run_analysis.R is used to create the transformed data set. Here are the steps: 
Download and unzip source data.
Read data.
Merge the training and the test sets.
Extract only the measurements on the mean and standard deviation for each measurement.
Use descriptive activity names to name the activities in the data set.
Appropriately label the data set with descriptive variable names.
Create a second, independent tidy set with the average of each variable for each activity and each subject.
Write the data set to the tidy_data.txt file.
