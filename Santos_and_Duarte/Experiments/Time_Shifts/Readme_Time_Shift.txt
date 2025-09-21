This folder contains the results of different executions of the method proposed in [1] with various time-shifts(1, 5 and 10) 
It contains the subdirectories "./Shift_$KAPPA$/", with (KAPPA = 1, 5, 10). 
Each subdirectory has the following items:
   1- The subdirectory "./Shift_$KAPPA$/Organized_Processed/" which contains the dataset proposed in [2] in an organized format 
     alongside with the corresponding experimental results.
   2- The file './Shift_$KAPPA$/SubjectVectors.txt' containing the final vectors of all the subjects in the dataset proposed in [2] after the method described in [1] 
     has been applied on it with the corresponding time-shift. 
   3- The file './Shift_$KAPPA$/Vectors.txt' which is a copy of the file './Shift_$KAPPA$/SubjectVectors.txt' where each line 
      starts with the subjects' Id WITHOUT squared bracked, and the lines of this file are sorted in increasing NUMERIC order 
	  of the subjects' identifiers. The file './Shift_$KAPPA$/Vectors.txt' must be MANUALLY generated from the content of the file "SubjectVectors.txt". 
________________________________________________________________________________________________   

[1] Tsagmo Denkeng, A.J., Mohammad Mourad, A., Iloga, S., Mballa Mba, R.M., Baazaoui, H., Djotio, T., Romain, O. 
"Efficient characterization of the human balance using HMMs" 
(Under review).

[2] Santos, D.A., Duarte, M.
"A public data set of human balance evaluations."
PeerJ 4, 2648 (2016)