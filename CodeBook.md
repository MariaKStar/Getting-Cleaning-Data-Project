Original Data 

The study, Human Activity Recognition Using Smartphones Dataset data was carried out by Jorge L. Reyes-Ortiz, Davide Anguita, Alessandro Ghio, Luca Oneto at Smartlab - Non Linear Complex Systems Laboratory, Genoa, Italy. 

The experiments have been carried out with a group of 30 volunteers within an age bracket of 19-48 years.  Each person performed six activities (WALKING, WALKING UPSTAIRS, WALKING DOWNSTAIRS, SITTING, STANDING, LAYING) wearing a smartphone (Samsung Galaxy S II) on the waist. The data have been collected from the accelerometers from the Samsung Galaxy S smartphone. In particular, using its embedded accelerometer and gyroscope, the 3-axial linear acceleration and 3-axial angular velocity at a constant rate of 50Hz the data were captured. 
For more information about this study see the link:

http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

The dataset includes the following files:

- 'README.txt'

- 'features_info.txt': Shows information about the variables used on the feature vector.

- 'features.txt': List of all features ( 562 variables)
- 'train/X_train.txt': Training set.

- 'train/y_train.txt': Training labels.

- 'test/X_test.txt': Test set.

- 'test/y_test.txt': Test labels.

The following files are available for the train and test data. Their descriptions are equivalent. 

- 'train/subject_train.txt': Each row identifies the subject who performed the activity for each window sample. Its range is from 1 to 30. 

- 'train/Inertial Signals/total_acc_x_train.txt': The acceleration signal from the smartphone accelerometer X axis in standard gravity units 'g'. Every row shows a 128 element vector. The same description applies for the 'total_acc_x_train.txt' and 'total_acc_z_train.txt' files for the Y and Z axis. 

- 'train/Inertial Signals/body_acc_x_train.txt': The body acceleration signal obtained by subtracting the gravity from the total acceleration. 

- 'train/Inertial Signals/body_gyro_x_train.txt': The angular velocity vector measured by the gyroscope for each window sample. The units are radians/second. 

Our data 
For the purposes of this project analysis we selected the following variables:, subject, activity label and the features for means and standard deviations.  The following is a list of all variables has been included in the output:
•	subject: The identifier of each volunteer (1-30) of the subject performing the activity
•	activity: The activity label (WALKING, WALKING UPSTAIRS, WALKING DOWNSTAIRS, SITTING, STANDING, LAYING)
•	tbodyaccmeanx: The mean of the time signal of body acceleration along the X axis
•	tbodyaccmeany: The mean of the time signal of body acceleration along the Y axis
•	tbodyaccmeanz: The mean of the time signal of body acceleration along the Z axis
•	tbodyaccstdx: The standard deviation of the time signal of body acceleration along the X axis
•	tbodyaccstdy: The standard deviation of the time signal of body acceleration along the Y axis
•	tbodyaccstdz: The standard deviation of the time signal of body acceleration along the Z axis
•	tgravityaccmeanx: The mean of the time signal of gravity acceleration along the X axis
•	tgravityaccmeany: The mean of the time signal of gravity acceleration along the Y axis
•	tgravityaccmeanz: The mean of the time signal of gravity acceleration along the Z axis
•	tgravityaccstdx: The standard deviation of the time signal of gravity acceleration along the X axis
•	tgravityaccstdy: The standard deviation of the time signal of gravity acceleration along the Y axis
•	tgravityaccstdz: The standard deviation of the time signal of gravity acceleration along the Z axis
•	tbodyaccjerkmeanx: The mean of the time signal of jerk along the X axis
•	tbodyaccjerkmeany: The mean of the time signal of jerk along the Y axis
•	tbodyaccjerkmeanz: The mean of the time signal of jerk along the Z axis
•	tbodyaccjerkstdx: The standard deviation of the time signal of jerk along the X axis
•	tbodyaccjerkstdy: The standard deviation of the time signal of jerk along the Y axis
•	tbodyaccjerkstdz: The standard deviation of the time signal of jerk along the Z axis
•	tbodygyromeanx: The mean of the time signal of body gyroscope along the X axis
•	tbodygyromeany: The mean of the time signal of body gyroscope along the Y axis
•	tbodygyromeanz: The mean of the time signal of body gyroscope along the Z axis
•	tbodygyrostdx: The standard deviation of the time signal of body gyroscope along the X axis
•	tbodygyrostdy: The standard deviation of the time signal of body gyroscope along the Y axis
•	tbodygyrostdz: The standard deviation of the time signal of body gyroscope along the Z axis
•	tbodygyrojerkmeanx: The mean of the time signal of gyroscope jerk along the X axis
•	tbodygyrojerkmeany: The mean of the time signal of gyroscope jerk along the Y axis
•	tbodygyrojerkmeanz: The mean of the time signal of gyroscope jerk along the Z axis
•	tbodygyrojerkstdx: The standard deviation of the time signal of gyroscope jerk along the X axis
•	tbodygyrojerkstdy: The standard deviation of the time signal of gyroscope jerk along the Y axis
•	tbodygyrojerkstdz: The standard deviation of the time signal of gyroscope jerk along the Z axis
•	tbodyaccmagmean: The mean of the time signal of magnitude of body acceleration
•	tbodyaccmagstd: The standard deviation of the time signal of magnitude of body acceleration
•	tgravityaccmagmean: The mean of the magnitude of the time signal of gravity acceleration
•	tgravityaccmagstd: The standard deviation of the time signal of magnitude of gravity acceleration
•	tbodyaccjerkmagmean: The mean of the time signal of magnitude of jerk
•	tbodyaccjerkmagstd: The standard deviation of the time signal of magnitude of jerk
•	tbodygyromagmean: The mean of the magnitude of the time signal of gyroscope
•	tbodygyromagstd: The standard deviation of the time signal of magnitude of gyroscope
•	tbodygyrojerkmagmean: The mean of the time signal of magnitude of gyroscope jerk
•	tbodygyrojerkmagstd: The standard deviation of the time signal of magnitude of gyroscope jerk
•	fbodyaccmeanx: The mean of the Fast Fourier Transform (FFT) of body acceleration along the X axis
•	fbodyaccmeany: The mean of the FFT of body acceleration along the Y axis
•	fbodyaccmeanz: The mean of the FFT of body acceleration along the Z axis
•	fbodyaccstdx: The standard deviation of the FFT of body acceleration along the X axis
•	fbodyaccstdy: The standard deviation of the FFT of body acceleration along the Y axis
•	fbodyaccstdz: The standard deviation of the FFT of body acceleration along the Z axis
•	fbodyaccjerkmeanx: The mean of the FFT of body acceleration jerk along the X axis
•	fbodyaccjerkmeany: The mean of the FFT of body acceleration jerk along the Y axis
•	fbodyaccjerkmeanz: The mean of the FFT of body acceleration jerk along the Z axis
•	fbodyaccjerkstdx: The standard deviation of the FFT of body acceleration jerk along the X axis
•	fbodyaccjerkstdy: The standard deviation of the FFT of body acceleration jerk along the Y axis
•	fbodyaccjerkstdz: The standard deviation of the FFT of body acceleration jerk along the Z axis
•	fbodygyromeanx: The mean of the FFT of the gyroscope signal along the X axis
•	fbodygyromeany: The mean of the FFT of the gyroscope signal along the Y axis
•	fbodygyromeanz: The mean of the FFT of the gyroscope signal along the Z axis
•	fbodygyrostdx: The standard deviation of the FFT of the gyroscope signal along the X axis
•	fbodygyrostdy: The standard deviation of the FFT of the gyroscope signal along the Y axis
•	fbodygyrostdz: The standard deviation of the FFT of the gyroscope signal along the Z axis
•	fbodyaccmagmean: The mean of the FFT of the magnitude of body acceleration
•	fbodyaccmagstd: The standard deviation of the FFT of the magnitude of body acceleration
•	fbodybodyaccjerkmagmean: The mean of the FFT of the magnitude of body acceleration jerk
•	fbodybodyaccjerkmagstd: The standard deviation of the FFT of the magnitude of body acceleration jerk
•	fbodybodygyromagmean: The mean of the FFT of the magnitude of body jerk
•	fbodybodygyromagstd: The standard deviation of the FFT of the magnitude of body jerk
•	fbodybodygyrojerkmagmean: The mean of the FFT of the magnitude of gyroscope body jerk
•	fbodybodygyrojerkmagstd: The standard deviation of the FFT of the magnitude of gyroscope body jerk

