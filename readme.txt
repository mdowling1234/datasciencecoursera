Peer-graded Assignment: Getting and Cleaning Data Course Project
This repository is a containing M.Dowling's submission for the assignment.

DataSet -
The submitted FinalData.txt is a tidy dataset grouping the means and standard 
deviation data by groups broken down into subejcts and then into activities.

run_analysis.R is the R script that loads in the colomns we want from
pre-existing datasets and then processes them in order to make the into a tidy dataset.
A short synopsis: load individual data sets, then merge them into one larger complete dataset,
then clean-up the naming conventions used throughout the data and replace it with names that are
easier to understand, then pull out only data that is associated with mean and std dev.,
lastly group the data by subject and activity, and write the FinalData to a .txt file
