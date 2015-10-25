Getting and Cleaning Data - Course Project

The following files are in scope of this assignement:

run_analysis.R

No libraries are required for run_analysis.R.

1) Read datasets from the Internet 
2) Unzip the datasets 
3) read following files using read.tables
subject_train.txt
subject_test.txt
y_train.txt
y_test.txt
x_train.txt
x_test.txt
features.txt
activity_labels.txt

4)merge datasets and choose apprropritae column name

Refer CodeBook.md for a detailled description of the steps executed by run_analysis.R

data/tidy.txt

Resulting tidy dataset as per assignement.

CodeBook.md

Description of tidy.txt and steps to transform the data.

After run_analysis.R is run, "data" folder will contain Dataset.zip (initial data downloaded from the Internet), and tidy.txt, the tidy dataset generated for the project. 

"UCI HAR Dataset" folder contains the original data unziped from Dataset.zip.

