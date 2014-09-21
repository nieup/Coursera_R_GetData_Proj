Coursera_R_GetData_Proj
=======================

# This repo contains my submission for the project of the Coursera Course 'Getting and Cleaning Data' 

In this project we extracted data from smartphones accelerometers in order to arange them in a clean 
and processed tidy_Data set. 

This file describes the overall philosophy of this task, you will find in this repository 
the README file, a CodeBook descibing the variables used in the tidy_Data set and in the prossing 
also, the script that was used to produce the tidy_Data set requested in the assignement 
and the tidy_Data set a backup of what is already present on the assignement submission on Coursera 


# Steps of Processing the Data : 
* Get the raw data from the differents text files (features, labels and measurements)
* Merge the data first by "test" and "train" and giving names to the attributes 
* Merge all the data together in one Clean_data data set 
* Extract the variables corresponding to mean and standard deviantion measurement 
* Process mean calculation over Subject for each Label 
* Insert proper denomination to columns and variables 
* Save the data in the appropriate file : "tidy_Data.txt" 

