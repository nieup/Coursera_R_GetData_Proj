# This is the Code Book for the Course Project for Coursera Cleaning Data Class
## In this file you will find a description of every variable used in the process of cleaning up the data and of the variables in the tidy_Data set. 

In the process :
=================================
## Primary variables :  
* SubJ_Test contains data from the Subject in the Test
* X_Test contains data from the Mesurement in the Test
* Y_Test contains data from the Activity also described as "Label" in the Test
* Clean_Test contains data from the Test Set cleaned (named, labeled and  merged) 

* SubJ_Train contains data from the Subject in the Train
* X_Train contains data from the Mesurement in the Train
* Y_Train contains data from the Activity also described as "Label" in the Train
* Clean_Train contains data from the Train Set cleaned (named, labeled and  merged) 

* Clean_Data contains data from the Train and Test Sets 
* Note : there will not be any diffrence anymore bettwen train and test data 

* tidy_dataV1 contains data from the Train and Test Sets with measurement variables corresponding to mean and standard deviantion

* Matrix_tidy_Data Matrix containing the processed data where data corresdonds to the mean one variable for each Subject over one Label

* tidy_Data contains the processed data described in Matrix_tidy_Data with attrubites(column names and characters labels) 

## Secondary variables : 
* features contains the table read from the feature file essentially description of measurements 

* Vect_features conntains the character features, is used to give names to the columns of our primary data set 

* Sel_features conntains the character features, is used to give names to the columns of our Selected data set

* Labels_Ref contains the table read from the activty labels file essentially description of activity undertaen by subjects 

* Labels conntains the character Labels, is used to give values of the second column of our data set

* Index_Mean contains the Index of the measurement of mean variables 

* Index_Std contains the Index of the measurement of standard deviantion variables

* Index regroups the two previous Indexes to form one regrouping both Mean and Std variables 

* Index_Subj used in the mean calculation Index of rows corresponding to the Subject i 

* Buff_Data_Subj used in the mean calculation Subset of tidy_data corresponding to Subject i 

* Index_Label used in the mean calculation Index of rows corresponding to the Label j 

* Buff_Data_Subj_Label used in the mean calculation Subset of Buff_Data_Subj used corresponding to Label j 

* i, j and k are counting  variables 

In the tidy_Data :
==========================
## 81 variables and 180 observations (30 Subjects * 6 Labels)  
* "Subject" int in 1:30 corresponding to the id of the subject 
* "Label" char 6 different values describing the activity in which the subject was studied  
* 79 different types of measurement containing the mean value per Suject and Activity Label 








