# ProjectGettingAndCleaningData
Getting and Cleaning Data Course Project

AUTOR: Félix Sebatián Rincón Tobo <br />
CONTENT: FInal project for the Getting and Cleaning Data Course in coursera<br />
DATE:  2020-05-03<br />
VERSION: 1.0<br />


## OBJECTIVE
Describe the variables in recordsStep5.txt


## VARIABLES
### subject
* type:factor
* values:(1:30)
* description: identifies the subject who performed the activity.

### activity
* type:factor
* values:("walking","walking_upstairs", "walking_downstairs","sitting","standing","laying")
* description: identifies activity performed for the subject. 


## signal
* type:factor
* values:("fBodyAcc","fBodyAccJerk","fBodyGyro","tBodyAcc","tBodyAccJerk","tBodyGyro","tBodyGyroJerk","tGravityAcc")
* description:contains the name of the posible signals measured.

### variable
* type:factor
* values:("mean"", "std")
* description: describe if the value is a mean (mean) or a standard deviation (std).

### variable
* type:numeric
* values:(min= -0.996335, max = 0.476947)
* description: show the average of the all measures made in all axis grouped by (subject, activity,signal,variable).
