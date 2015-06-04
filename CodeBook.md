# CodeBook for run_analysis.R

This file describes at detailed level how each step in run_analysis.R script works:

## step-1: merges the training and the test sets to form a new dataset
- the train data is divided into three files:
     - X_train.txt
     - y_train.txt
     - subject_train.txt
- the test data is divided into three files:
     - X_test.txt
     - y_test.txt
     - subject_test.txt
- there are all together 30 subjects in the research work.
- the main objective of step 1 is to combine dataset from the train and test dataset.
- to read the text files, the command read.table() is used.
- make sure that the working directory is set correctly and the working folder name for the dateset is "dataset".

## step-2: Extracts only the measurements on the mean and standard deviation for each measurement.








prepared by Choo-Yee Ting
