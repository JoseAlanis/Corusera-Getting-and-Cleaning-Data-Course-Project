# Corusera Getting and Cleaning Data Course Project by John Hopkins University

This is a Repo for the submission of the course project for Coursera's Getting and Cleaning Data by John Hopkins University

## What's in this Repo?

The Repo contains the following files:

- `README.md`, it provides generall infomration on the Repo and it's purpose.
- `new_data_tidy.txt`, tidy data set in tabular structure.
- `CodeBook.md`, a file describing the values, variables and transformations perfomed to generate the data comprised in `new_data_tidy.txt`.
- `run_analysis.R`, R-Code used to create a tidy version of the data.

## What was the course project about?

The purpose of the course project was to demonstrate one's ability to collect, work with, and clean a data set. The goal was also to prepare tidy data that can be used for later analysis.

## What's the nature of the data used in the course project?

Data was collected from accelerometers of Samsung Galaxy S smartphones. The original data set was built from recordings of 30 subjects performing activities of daily living (ADL) while carrying a waist-mounted smartphone with embedded inertial sensors (detailed informarmation can be found at [UCI's Machine Learing Repository Site](http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones), where the data was obtained).


## What transformations were performed to the original data?

The code comprised in `run_analysis.R` can be used to:

- Dowloading and unziping the original data set from UCI's Machine Learing Repository.
- Merge the training and the test data sets to create one data set.
- Extract only the measurements on the mean and standard deviation for each measurement.
- Use descriptive activity names to name the activities in the data set.
- Appropriately label the data set with descriptive variable names.
- Create a second, independent tidy data set with the average of each variable for each activity and each subject.
