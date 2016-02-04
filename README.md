The Cleaning and Data Project for week4 of the course Getting and Cleaning Data - resubmission
Loading the libraries.
Required files are in the working directory.
The Files are;
 "activity_labels.txt", "features.txt", "subject_test.txt"
 "subject_train.txt", "X_text.txt", "X_train.txt", "y_test.txt", "y_train.txt"
Reading the files into R
Merging the data objects for test and training by set (train and test)
 Merging the train files
 Merging the test files
 Merging the test and train files ingto a new set
  subject and activities variables added
  Names "subject" and "activity" updated for the first two columns instead of V1 V1
  Generating the vectors for selecting and naming columns
    Generating the Logical Vectors
    adding to the logical vector two entries "TRUE" for the Subject and Activity Names
  Generating the new data frame with only the selected variables.
    Naming the variables as per the features files
    Adding the rows to features with the Names "subject" and "entity" 
    This to match the V2 column in features with the names in the merged file
 Updating activities labels)
 Generating a vector with the new names
 Updating variables names in the final set
 Creating a second tidy data set with the average of each variable, for each activity and each subject
Writing the text file
