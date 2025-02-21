UCI-HAR-project
===============

Wearable Company Analysis

This project to create a tidy dataset for Wearable Company in order to do further analysis for it. 
For more information about the company business check this address 
http://www.insideactivitytracking.com/data-science-activity-tracking-and-the-battle-for-the-worlds-top-sports-brand/

Data has been collected from the accelerometers from the Samsung Galaxy S smartphone. 
A full description is available at the site where the data was obtained: 

http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones 

Here are the data for the project: 
https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip 

We will create one R script called run_analysis.R that does the following.:

- Merges the training and the test sets to create one data set.
- Extracts only the measurements on the mean and standard deviation for each measurement. 
- Uses descriptive activity names to name the activities in the data set
- Appropriately labels the data set with descriptive variable names. 
- From the data set in step 4, creates a second, independent tidy data set with the average of 
each variable for each activity and each subject.


Unzip the source (https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip) into a folder 
on your working directory name it "UCI HAR project"

it will create a folder named "UCI HAR Dataset"

Put run_analysis.R into working directory\UCI HAR project

In RStudio: source("UCI HAR project/run_analysis.R")

run result <- read.table("UCI HAR project/UCI HAR Dataset/avrg_data_set.txt") to read the final data.

Regards,
Mohammad.
