Course book for run_analysis.R script:

Please refer to the "README.md" file for the details to run the "run_analysis.R" script.

The run_analysis.R performs the following:

1. Merges the training and the test sets to create one data set. 
	The value of 'X' contains the merged data set of X_train.txt and X_test.txt. 
	The value of 'Y' contains the merged data set of y_train.txt and y_test.txt.
	The value of 'S' contains the merged data set of subject_train.txt and subject_test.txt.
	
2. Extracts only the measurements on the mean and standard deviation for each measurement.
	This section of the code reads features.txt file and perform the operations to extract only the measurements on the mean and standard deviation for each measurement.
	
3. Uses descriptive activity names to name the activities in the data set.
	This section of the code reads activity_labels.txt file and uses descriptive activity names to name the following activities in the data set.
	Activities: Walking, Walkingupstarirs, Walkingdownstairs, Sitting, Standing, Laying
	
4. Appropriately labels the data set with descriptive variable names. 
	All feature names (attributes) and activity names are converted to lower case, underscores and brackets () are removed.
	It will merge the data frame containing features with data frame containing activity labels and subject ID's and the result is saved as "tidy_dataset.txt"
	The resultant attribute names are tbodyacc-mean-x, tbodyacc-mean-y, tbodyacc-mean-z, tbodyacc-std-x, tbodyacc-std-y, tbodyacc-std-z, tgravityacc-mean-x, tgravityacc-mean-y
	
5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject. The result is stored in "data_set_with_averages.txt" file.

	
	
	
 	




