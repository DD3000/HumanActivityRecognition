##CodeBook

The file "combinedTidyAverage.txt" represents the output of the run_analysis.R script.  

In "combinedTidyAverage.txt", the smartphone data is summarized.  Namely, all measurements of means and standard deviations
are grouped by activity and subject and each of their average is recorded.  

See the following link for more information about the original datasource:
http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

The data ingested by run_analysis.R is here:
https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

Here are the variables that are written out to "combinedTidyAverage.txt":

"activity" - Activity represents the actions being taken by the individual.  This takes one of the following values:
              "LAYING"             
              "SITTING"            
              "STANDING"           
              "WALKING"           
              "WALKING_DOWNSTAIRS" 
              "WALKING_UPSTAIRS"

"subject"  - This represents the person who performed the action.  There were 30 people who performed the action, so this takes on a value 1-30.

"measurement" - This represents the particular measurement that's being summarized.  It includes the following 79 values:
              "fBodyAcc-mean()-X"               "fBodyAcc-mean()-Y"               "fBodyAcc-mean()-Z"              
              "fBodyAcc-meanFreq()-X"           "fBodyAcc-meanFreq()-Y"           "fBodyAcc-meanFreq()-Z"          
              "fBodyAcc-std()-X"                "fBodyAcc-std()-Y"                "fBodyAcc-std()-Z"               
              "fBodyAccJerk-mean()-X"           "fBodyAccJerk-mean()-Y"           "fBodyAccJerk-mean()-Z"          
              "fBodyAccJerk-meanFreq()-X"       "fBodyAccJerk-meanFreq()-Y"       "fBodyAccJerk-meanFreq()-Z"      
              "fBodyAccJerk-std()-X"            "fBodyAccJerk-std()-Y"            "fBodyAccJerk-std()-Z"           
              "fBodyAccMag-mean()"              "fBodyAccMag-meanFreq()"          "fBodyAccMag-std()"              
              "fBodyBodyAccJerkMag-mean()"      "fBodyBodyAccJerkMag-meanFreq()"  "fBodyBodyAccJerkMag-std()"      
              "fBodyBodyGyroJerkMag-mean()"     "fBodyBodyGyroJerkMag-meanFreq()" "fBodyBodyGyroJerkMag-std()"     
              "fBodyBodyGyroMag-mean()"         "fBodyBodyGyroMag-meanFreq()"     "fBodyBodyGyroMag-std()"         
              "fBodyGyro-mean()-X"              "fBodyGyro-mean()-Y"              "fBodyGyro-mean()-Z"             
              "fBodyGyro-meanFreq()-X"          "fBodyGyro-meanFreq()-Y"          "fBodyGyro-meanFreq()-Z"         
              "fBodyGyro-std()-X"               "fBodyGyro-std()-Y"               "fBodyGyro-std()-Z"              
              "tBodyAcc-mean()-X"               "tBodyAcc-mean()-Y"               "tBodyAcc-mean()-Z"              
              "tBodyAcc-std()-X"                "tBodyAcc-std()-Y"                "tBodyAcc-std()-Z"               
              "tBodyAccJerk-mean()-X"           "tBodyAccJerk-mean()-Y"           "tBodyAccJerk-mean()-Z"          
              "tBodyAccJerk-std()-X"            "tBodyAccJerk-std()-Y"            "tBodyAccJerk-std()-Z"           
              "tBodyAccJerkMag-mean()"          "tBodyAccJerkMag-std()"           "tBodyAccMag-mean()"             
              "tBodyAccMag-std()"               "tBodyGyro-mean()-X"              "tBodyGyro-mean()-Y"             
              "tBodyGyro-mean()-Z"              "tBodyGyro-std()-X"               "tBodyGyro-std()-Y"              
              "tBodyGyro-std()-Z"               "tBodyGyroJerk-mean()-X"          "tBodyGyroJerk-mean()-Y"         
              "tBodyGyroJerk-mean()-Z"          "tBodyGyroJerk-std()-X"           "tBodyGyroJerk-std()-Y"          
              "tBodyGyroJerk-std()-Z"           "tBodyGyroJerkMag-mean()"         "tBodyGyroJerkMag-std()"         
              "tBodyGyroMag-mean()"             "tBodyGyroMag-std()"              "tGravityAcc-mean()-X"           
              "tGravityAcc-mean()-Y"            "tGravityAcc-mean()-Z"            "tGravityAcc-std()-X"            
              "tGravityAcc-std()-Y"             "tGravityAcc-std()-Z"             "tGravityAccMag-mean()"          
              "tGravityAccMag-std()"

"avgMeasurement" - This is the average measurement value of each activity/subject/measurement.  It's a floating point number.

