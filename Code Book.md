The result of the project is a data.frame with it’s corresponding text file.
“average _tidy” and “average_tidy_data_set.txt
The source data for this set come from from the source data sets
For the “Human Activity Recognition Using Smartphones Dataset”
The original data sets for training and test were merged into a singles data set. Then the variables to analyze were reduced for the ones that measured the mean and the standard deviation. The activity codes were updated with the 6 activity names. Finally, a new data set “average_tidy” was generated with the average for each activity and each subject.

DATA DICTIONARY:

The variables in the data frame “average_tidy” are indicated in the table below.
The variables names were deducted using the the documents from the source data sets
For the “Human Activity Recognition Using Smartphones Dataset
The link for the data is “https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip “
Specifically the files README and features_info
The initial t and f were changed for time and frequency. Acc was changed to accelerometer, Gyro for gyroscope, Mag for magnitude, the term BodyBody was replaced by body.


The variables are the average of the observations for the subject in the activity indicated in the row



subject                                        
Number identifying each volunteer
activity                                      
Label identifying each activity executed by the volunteer (6 activities) “walking, walking_upstairs, walking_downstairs, sitting, standing, laying” while wearing a smartphone (Samsung Galaxy S II) on the
waist.
timebodyaccelerometer-mean()-X                 

timebodyaccelerometer-mean()-Y                

timebodyaccelerometer-mean()-Z                 

timebodyaccelerometer-std()-X                 

timebodyaccelerometer-std()-Y                  

timebodyaccelerometer-std()-Z                 

timegravityaccelerometer-mean()-X             

timegravityaccelerometer-mean()-Y             

timegravityaccelerometer-mean()-Z             

timegravityaccelerometer-std()-X              

timegravityaccelerometer-std()-Y               

timegravityaccelerometer-std()-Z              

timebodyaccelerometerJerk-mean()-X             

timebodyaccelerometerJerk-mean()-Y            

timebodyaccelerometerJerk-mean()-Z            

timebodyaccelerometerJerk-std()-X             

timebodyaccelerometerJerk-std()-Y              

timebodyaccelerometerJerk-std()-Z             

timebodygyroscope-mean()-X                    

timebodygyroscope-mean()-Y                    

timebodygyroscope-mean()-Z                     

timebodygyroscope-std()-X                     

timebodygyroscope-std()-Y                     

timebodygyroscope-std()-Z                     

timebodygyroscopeJerk-mean()-X                 

timebodygyroscopeJerk-mean()-Y                

timebodygyroscopeJerk-mean()-Z                 

timebodygyroscopeJerk-std()-X                 

timebodygyroscopeJerk-std()-Y                 

timebodygyroscopeJerk-std()-Z                 

timebodyaccelerometermagnitude-mean()         

timebodyaccelerometermagnitude-std()          

timegravityaccelerometermagnitude-mean()       

timegravityaccelerometermagnitude-std()       

timebodyaccelerometerJerkmagnitude-mean()      

timebodyaccelerometerJerkmagnitude-std()      

timebodygyroscopemagnitude-mean()              

timebodygyroscopemagnitude-std()              

timebodygyroscopeJerkmagnitude-mean()          

timebodygyroscopeJerkmagnitude-std()          

frequencybodyaccelerometer-mean()-X            

frequencybodyaccelerometer-mean()-Y           

frequencybodyaccelerometer-mean()-Z            

requencybodyaccelerometer-std()-X            

frequencybodyaccelerometer-std()-Y             

frequencybodyaccelerometer-std()-Z            

frequencybodyaccelerometerJerk-mean()-X        

frequencybodyaccelerometerJerk-mean()-Y       

frequencybodyaccelerometerJerk-mean()-Z       

frequencybodyaccelerometerJerk-std()-X        

frequencybodyaccelerometerJerk-std()-Y         

frequencybodyaccelerometerJerk-std()-Z        

frequencybodygyroscope-mean()-X                

frequencybodygyroscope-mean()-Y               

frequencybodygyroscope-mean()-Z                

frequencybodygyroscope-std()-X                

frequencybodygyroscope-std()-Y                 

frequencybodygyroscope-std()-Z                

frequencybodyaccelerometermagnitude-mean()     

frequencybodyaccelerometermagnitude-std()     

frequencybodyaccelerometerJerkmagnitude-mean() 

frequencybodyaccelerometerJerkmagnitude-std() 

frequencybodygyroscopemagnitude-mean()         

frequencybodygyroscopemagnitude-std()         

frequencybodygyroscopeJerkmagnitude-mean()     

frequencybodygyroscopeJerkmagnitude-std()


