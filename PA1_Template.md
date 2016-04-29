##Reprodcuicble_research data Course Project Assignmet 1
#####Aalysis of Data from a personal activity monitoring devices such as Fitbit, Nike Fuelband, or Jawbone Up.
The monitoring device collects data at 5 minute intervals through out the day. The data consists of two months of data from an anonymous individual collected during the months of October and November, 2012 and include the number of steps taken in 5 minute intervals each day.
The variables included in the dataset 'Activity monitoring data' are:

steps: Number of steps taking in a 5-minute interval (missing values are coded as NA)
date: The date on which the measurement was taken in YYYY-MM-DD format
interval: Identifier for the 5-minute interval in which measurement was taken
The dataset is stored in a comma-separated-value (CSV) file and there are a total of 17,568 observations in this dataset.

Loading and preprocessing the data


Loaded the data (i.e. read.csv())
Processed/transformed the data (if necessary) into a suitable format 
Calculated mean total number of steps taken per day.

Ignored the missing values in the dataset.

Calculated the total number of steps taken per day
Plotted a histogram of the total number of steps taken each day
Calculated and report the mean and median of the total number of steps taken per day
Calculated the average daily activity pattern.

Made a time series plot (i.e. type = "l") of the 5-minute interval (x-axis) and the average number of steps taken, averaged across all days (y-axis)
Calculated 5-minute interval, on average across all the days in the dataset, contains the maximum number of steps.

####Imputing missing values

Calculated and reported the total number of missing values in the dataset (i.e. the total number of rows with NAs)
Devised a strategy for filling in all of the missing values in the dataset. See the code.
Created a new dataset that is equal to the original dataset but with the missing data filled in.
Plotted a histogram of the total number of steps taken each day and Calculated and reported the mean and median total number of steps taken per day. Do these values differ from the estimates from the first part of the assignment? What is the impact of imputing missing data on the estimates of the total daily number of steps?
Verified if there are any differences in activity patterns between weekdays and weekends.

The weekdays() function was used to verif the differences between weekdays and weekends. Use the dataset with the filled-in missing values for this part.

Created a new factor variable in the dataset with two levels – “weekday” and “weekend” indicating whether a given date is a weekday or weekend day.
Made a panel plot containing a time series plot (i.e. type = "l") of the 5-minute interval (x-axis) and the average number of steps taken, averaged across all weekday days or weekend days (y-axis). 
