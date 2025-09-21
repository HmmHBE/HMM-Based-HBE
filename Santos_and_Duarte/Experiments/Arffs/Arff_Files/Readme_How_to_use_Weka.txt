Run WEKA to perform classification experiments as those of the Section 6.3 in [1].
The '.arff' files taken as input by WEKA and used in [1] are saved in the subdirectories 
"./Age10/" and "./BEST10/".

To run WEKA, please execute the following instructions:

   1- Download and install WEKA soft (WEKA 3.9 was used in [1])
   2- Run WEKA
   3- Click the button 'Explorer' to open a new window.
   4- In the 'Preprocess' tab, click the button 'Open file...' to select your '.arff' file.
   5- In the 'Classify' tab and below the button 'More options...', select the attribute 
     'class' that will be used as class during the classification. 
   6- Under the title 'Classifier', click the button 'Choose' to select to select the desired 
     classifier. The following classifiers experimented in [1] with their default 
	 parameters are available in the group named 'functions':
		- 'SMO' -> SVMs with polynomial kernel
		- 'J48' -> Decision trees
   7- Under the 'Test options' title, select the radio button 'Cross-validation' 
     then fix your desired number of folds (the value 10 was used in [1]).
   8- Click the 'Start' button to perform the classification, the results are displayed
     under the title 'Classifier output'.   
________________________________________________________________________________________________   

[1] Tsagmo Denkeng, A.J., Mohammad Mourad, A., Iloga, S., Mballa Mba, R.M., Baazaoui, H., Djotio, T., Romain, O. 
"Efficient characterization of the human balance using HMMs" 
(Under review).
