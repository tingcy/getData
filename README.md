# getData
This file describes at high-level how run_analysis.R script functions.

Download the dataset(https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip) for this course project and unzip it. Place the dataset into a folder named dataset.
the run_analysis.R file must be outside the dataset folder.
Load the run_analysis.R file into your RStudio.
After executing the R file, you shall notice that 2 files apprear in same directory as you place the R file.
cleanDataSet_columnmean.txt
cleanDataset.txt
You may want to view the 2 files by using the command:
df1<-read.table(“cleanDataset_columnmean.txt”)
df2<-read.table(“cleanDataset.txt”)
prepared by Choo-Yee Ting
