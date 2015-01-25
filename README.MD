Getting and Cleaning Data: Course Project - Smartphones Data Set

This set of scripts downloads and tidies the data from the UCI Human Activity Recognition Using Smartphones Data Set.

Dependencies

This project depends on the reshape2 R package

Project Scripts

1. run_analysis.R
run_analysis.R is the main point of entry. It sources all other files in the project, defines the main RunAnalysis() function and calls the RunAnalysis() function.

2. download_data.R
RunAnalysis() calls DownloadData(), contained in the file download_data.R. DownloadData() checks to see if the original data has already been downloaded, and if not, downloads the ZIP file to./HAR Dataset.zip, and unzips it to ./UCI HAR Dataset.
merge_data.R

3.  merge_data.R.
After downloading the data, RunAnalysis() calls MergeData(), which is contained in merge_data.R.
MergeData() makes the following call:
ReadDataset(): This is called first with the train dataset, then with the test dataset. It takes the X file, which contain the sensor readings, the y file, containing the activity label for each observation, the subject file, containing the subject identifiers for each observation, the features list from step 1, and the labels table from step 2. It reads the X file, y file and subject file into data frames. Next, it sets the names of the X dataset to the features list, then appends the y file column, and the subject file column to the end. It then merges with the labels data frame based on the activity id to add the activity label to the dataset. Then, it normalizes and downcases the variable names.
Then, it creates a dataset which has only the variables with mean and std, subject, activity and removes the non-alfanumeric characters: e.g. tBodyAcc-mean()-X becomes tbodyaccmeanx.
MergeData() merges the test and train dataset rows together and returns the merged dataset.

4. average_data.R
After merging the data, RunAnalysis() passes the resulting dataset to AverageData(), contained in average_data.R. AverageData()uses the reshape2 package to melt the dataset based on subjectand activity, and then dcast it together based on those two fields, providing the mean. The final result is a data frame containing the means of each of the included features for each combination of subject and activity.

Output
The final result is output in CSV format to ./averages.txt using the write.table
