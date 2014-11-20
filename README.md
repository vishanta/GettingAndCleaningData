Getting and Cleaning Data : Peer Assessment
===========================================

This is the peer assessment for the course [getdata-009].

### How the script run_analysis.R perform?

1. The first part of the R script downloads the UCI HAR Dataset dataset (if it does not exist) in the file working directrory and unzips the file into the 'UCI HAR Dataset' directory.

2. The training and test datasets are loaded using 'read.table' and merges these two dataasets using rbind.

3. It extracts the mean and standard deviation from the features data set using 'grep' function and applied to the x data frame.

4. 'tolower' and 'gsub' functions are used for "Uses descriptive activity names to name the activities in the data set".

5. The datasets, x, y and subject are merged and 'merged.txt' is created using 'write.table' function.

6. Finally, tidy dataset 'average.txt' is created with the average of each variable for each activity and each subject.
