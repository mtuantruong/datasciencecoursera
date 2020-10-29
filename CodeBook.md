# Code Book
generated 2014-07-10 11:04:30 during sourcing of `run_analysis.R`

## Actions performed on data:
* Create data dir `./data`
* Downloading zip file: [https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip](https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip) to `./data`
* Unzip file: `./data/data.zip` to `./data/UCI HAR Dataset`
* Load reshape2 package
* Read data
* 1/ Merges the training and the test sets to create one data set
* 2/ Extracts only the measurements on the mean and standard deviation for each measurement.
* 4/ Appropriately labels the data set with descriptive activity names
* 3/ Uses descriptive activity names to name the activities in the data set
* 5/ Creates a second, independent tidy data set with the average of each variable for each activity and each subject.
* Last, write `tidyData` to file  `./data/tidy_data.txt`
