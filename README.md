This repository is a Promit Saha's assignment submission for Getting and Cleaning Data course project. It has the instructions on how to run analysis on Human Activity recognition dataset.
Dataset

Human Activity Recognition Using Smartphones
Files

    CodeBook.md  describes the variables, the data, and any transformations or work that I performed to clean data
    run_analysis.R performs the data preparation and then followed by the 5 steps required as described in the course project’s definition:
        Merges the training and the test sets to create one data set.
        Extracts only the measurements on the mean and standard deviation for each measurement.
        Uses descriptive activity names to name the activities in the data set
        Appropriately labels the data set with descriptive variable names.
        From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

    FinalData.txt is the exported final data after going through all the sequences described above.
    
 The dataset includes the following files:


- 'README.txt'

- 'features_info.txt': Shows information about the variables used on the feature vector.

- 'features.txt': List of all features.

- 'activity_labels.txt': Links the class labels with their activity name.

- 'train/X_train.txt': Training set.

- 'train/y_train.txt': Training labels.

- 'test/X_test.txt': Test set.

- 'test/y_test.txt': Test labels.

The following files are available for the train and test data. Their descriptions are equivalent. 

- 'train/subject_train.txt': Each row identifies the subject who performed the activity for each window sample. Its range is from 1 to 30. 

- 'train/Inertial Signals/total_acc_x_train.txt': The acceleration signal from the smartphone accelerometer X axis in standard gravity units 'g'. Every row shows a 128 element vector. The same description applies for the 'total_acc_x_train.txt' and 'total_acc_z_train.txt' files for the Y and Z axis. 

- 'train/Inertial Signals/body_acc_x_train.txt': The body acceleration signal obtained by subtracting the gravity from the total acceleration. 

- 'train/Inertial Signals/body_gyro_x_train.txt': The angular velocity vector measured by the gyroscope for each window sample. The units are radians/second. 

Notes: 
======
- Features are normalized and bounded within [-1,1].
- Each feature vector is a row on the text file.

For more information about this dataset contact: activityrecognition@smartlab.ws
