Getting and Cleaning Data
=========================

This is a repository for code written for the Getting and Cleaning Data Coursera course.

## Course Project

* Step 1: Unzip the source (https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip) into a folder on your local home directory.

* Step 2: Put run_analysis.R into your local home directory.

* Step 3: In RStudio: setwd() to your local home directory, followed by: source("run_analysis.R")

* Step 4: Use data <- read.table("data_set_with_the_averages.txt") to read the data. It is 180x68 because there are 30 subjects and 6 activities, thus "for each activity and each subject" means 30 * 6 = 180 rows. Note that the provided R script has no assumptions on numbers of records, only on locations of files.