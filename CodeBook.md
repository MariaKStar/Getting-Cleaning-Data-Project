Original Data 

The study, Human Activity Recognition Using Smartphones Dataset data was carried out by Jorge L. Reyes-Ortiz, Davide Anguita, Alessandro Ghio, Luca Oneto at Smartlab - Non Linear Complex Systems Laboratory, Genoa, Italy. 

The experiments have been carried out with a group of 30 volunteers within an age bracket of 19-48 years.  Each person performed six activities (WALKING, WALKING UPSTAIRS, WALKING DOWNSTAIRS, SITTING, STANDING, LAYING) wearing a smartphone (Samsung Galaxy S II) on the waist. The data have been collected from the accelerometers from the Samsung Galaxy S smartphone. In particular, using its embedded accelerometer and gyroscope, the 3-axial linear acceleration and 3-axial angular velocity at a constant rate of 50Hz the data were captured. 
For more information about this study see the link:

http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

The dataset includes the following files:

- 'README.txt'
- 'features_info.txt': Shows information about the variables used on the feature vector.
- 'features.txt': List of all features 
- 'train/X_train.txt': Training set.
- 'train/y_train.txt': Training labels.
- 'test/X_test.txt': Test set.
- 'test/y_test.txt': Test labels.

Project Run_Analysis Data

For the purposes of this project analysis we selected the following variables:, subject, activity label and the features for means and standard deviations. 
The following is a list of all variables has been included in the output:

1.	subject: The identifier of each volunteer (1-30) of the subject performing the activity

2.	activity: The activity label (WALKING, WALKING UPSTAIRS, WALKING DOWNSTAIRS, SITTING, STANDING, LAYING)

3.	tbodyaccmeanx: The mean of the time signal of body acceleration along the X axis

4.	tbodyaccmeany: The mean of the time signal of body acceleration along the Y axis

5.	tbodyaccmeanz: The mean of the time signal of body acceleration along the Z axis

6.	tbodyaccstdx: The standard deviation of the time signal of body acceleration along the X axis

7.	tbodyaccstdy: The standard deviation of the time signal of body acceleration along the Y axis

8.	tbodyaccstdz: The standard deviation of the time signal of body acceleration along the Z axis

9.	tgravityaccmeanx: The mean of the time signal of gravity acceleration along the X axis

10.	tgravityaccmeany: The mean of the time signal of gravity acceleration along the Y axis

11.	tgravityaccmeanz: The mean of the time signal of gravity acceleration along the Z axis

12.	tgravityaccstdx: The standard deviation of the time signal of gravity acceleration along the X axis

13.	tgravityaccstdy: The standard deviation of the time signal of gravity acceleration along the Y axis

14.	tgravityaccstdz: The standard deviation of the time signal of gravity acceleration along the Z axis

15.	tbodyaccjerkmeanx: The mean of the time signal of jerk along the X axis

16.	tbodyaccjerkmeany: The mean of the time signal of jerk along the Y axis

17.	tbodyaccjerkmeanz: The mean of the time signal of jerk along the Z axis

18.	tbodyaccjerkstdx: The standard deviation of the time signal of jerk along the X axis

19.	tbodyaccjerkstdy: The standard deviation of the time signal of jerk along the Y

20.	tbodyaccjerkstdz: The standard deviation of the time signal of jerk along the Z axis

21.	tbodygyromeanx: The mean of the time signal of body gyroscope along the X axis

22.	tbodygyromeany: The mean of the time signal of body gyroscope along the Y axis

23.	tbodygyromeanz: The mean of the time signal of body gyroscope along the Z axis

24.	tbodygyrostdx: The standard deviation of the time signal of body gyroscope along the X 

25.	tbodygyrostdy: The standard deviation of the time signal of body gyroscope along the Y axis

26.	tbodygyrostdz: The standard deviation of the time signal of body gyroscope along the Z axis

27.	tbodygyrojerkmeanx: The mean of the time signal of gyroscope jerk along the X axis

28.	tbodygyrojerkmeany: The mean of the time signal of gyroscope jerk along the Y axis

29.	tbodygyrojerkmeanz: The mean of the time signal of gyroscope jerk along the Z axis

30.	tbodygyrojerkstdx: The standard deviation of the time signal of gyroscope jerk along the X axis

31.	tbodygyrojerkstdy: The standard deviation of the time signal of gyroscope jerk along the Y axis

32.	tbodygyrojerkstdz: The standard deviation of the time signal of gyroscope jerk along the Z axis

33.	tbodyaccmagmean: The mean of the time signal of magnitude of body acceleration

34.	tbodyaccmagstd: The standard deviation of the time signal of magnitude of body acceleration

35.	tgravityaccmagmean: The mean of the magnitude of the time signal of gravity acceleration

36.	tgravityaccmagstd: The standard deviation of the time signal of magnitude of gravity acceleration

37.	tbodyaccjerkmagmean: The mean of the time signal of magnitude of jerk

38.	tbodyaccjerkmagstd: The standard deviation of the time signal of magnitude of jerk

39.	tbodygyromagmean: The mean of the magnitude of the time signal of gyroscope

40.	tbodygyromagstd: The standard deviation of the time signal of magnitude of gyroscope

41.	tbodygyrojerkmagmean: The mean of the time signal of magnitude of gyroscope jerk

42.	tbodygyrojerkmagstd: The standard deviation of the time signal of magnitude of gyroscope jerk

43.	fbodyaccmeanx: The mean of the Fast Fourier Transform (FFT) of body acceleration along the X axis

44.	fbodyaccmeany: The mean of the FFT of body acceleration along the Y axis

45.	fbodyaccmeanz: The mean of the FFT of body acceleration along the Z axis

46.	fbodyaccstdx: The standard deviation of the FFT of body acceleration along the X axis

47.	fbodyaccstdy: The standard deviation of the FFT of body acceleration along the Y axis

48.	fbodyaccstdz: The standard deviation of the FFT of body acceleration along the Z axis

49.	fbodyaccjerkmeanx: The mean of the FFT of body acceleration jerk along the X axis

50.	fbodyaccjerkmeany: The mean of the FFT of body acceleration jerk along the Y axis

51.	fbodyaccjerkmeanz: The mean of the FFT of body acceleration jerk along the Z axis

52.	fbodyaccjerkstdx: The standard deviation of the FFT of body acceleration jerk along the X axis

53.	fbodyaccjerkstdy: The standard deviation of the FFT of body acceleration jerk along the Y axis

54.	fbodyaccjerkstdz: The standard deviation of the FFT of body acceleration jerk along the Z axis

55.	fbodygyromeanx: The mean of the FFT of the gyroscope signal along the X axis

56.	fbodygyromeany: The mean of the FFT of the gyroscope signal along the Y axis

57.	fbodygyromeanz: The mean of the FFT of the gyroscope signal along the Z axis

58.	fbodygyrostdx: The standard deviation of the FFT of the gyroscope signal along the X axis

59.	fbodygyrostdy: The standard deviation of the FFT of the gyroscope signal along the Y axis

60.	fbodygyrostdz: The standard deviation of the FFT of the gyroscope signal along the Z axis

61.	fbodyaccmagmean: The mean of the FFT of the magnitude of body acceleration

62.	fbodyaccmagstd: The standard deviation of the FFT of the magnitude of body acceleration

63.	fbodybodyaccjerkmagmean: The mean of the FFT of the magnitude of body acceleration jerk

64.	fbodybodyaccjerkmagstd: The standard deviation of the FFT of the magnitude of body acceleration jerk

65.	fbodybodygyromagmean: The mean of the FFT of the magnitude of body jerk

66.	fbodybodygyromagstd: The standard deviation of the FFT of the magnitude of body jerk

67.	fbodybodygyrojerkmagmean: The mean of the FFT of the magnitude of gyroscope body jerk

68.	fbodybodygyrojerkmagstd: The standard deviation of the FFT of the magnitude of gyroscope body jerk


