# Getting and Cleaning Data -Project
This is the project for the Getting and Cleaning Data Coursera course. The R script, *run_analysis.R*, performs the following activities:
* Download the dataset if it does not already exist in the working directory
* Unzips the dataset file
* Loads the activity and feature info
* Loads the activity and subject data for each training and test datasets
* Assigns column names to the test and train datasets
* Merges the two datasets
* Extracts measurement on the mean and standard deviation
* Creates a tidy dataset that consists of the average (mean) value of each variable for each subject and activity pair.

The end result is shown in the file *secTidySet.txt*.
