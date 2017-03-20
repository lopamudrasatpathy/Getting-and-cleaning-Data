## Coursera Getting and Cleaning Data Course Project

##Lopamudra Satpathy


## The data collected from the accelerometers from the Samsung Galaxy S smartphone and the full description is available at the site where the data was obtained:

http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

##Here are the data for the project:
https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

## Description of the R script named run_analysis.R


#Training and Test data set should be merged into one Data set.
#For each measurement, dimension of mean and standard deviation need to be extracted.
#In the Data set, the name which describes the activity should be used as Descriptive Activity Name.
#The variable names should be described with a suitable manner properly at each label of the Data set.
#A tidy Data set is formed with the average of each variable for each activity and each subject.

##Procedure :
#1. Download the data source and put into a folder on your local drive where you will have a UCI HAR Dataset.
#2.Put run_analysis.R in the parent folder of UCI HAR Dataset, then use it as your working directory.
#3.Run source("run_analysis.R"), then it will generate a new file named as tidy.txt in your working directory.

##R Packages:
#run_analysis.R file will help you to install the dependencies automatically.It depends on reshape2 and data.table package.


