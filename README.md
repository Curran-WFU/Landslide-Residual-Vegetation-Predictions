# Landslide-Residual-Vegetation-Predictions
Welcome.  This site contains:
A dataset of landslide characteristics, Copy of ls_data_SVM.1_28_2021.csv. 
A Python program (iynb format) for using the scikit-learn Support Vector Machine binary classifier (Github_AI_0_SVM_Accuracies_Predictions.ipynb).  To get bootstrap probabilities that a landslide site contained residual vegetation, the program allows the user to specify the number times the SVM classifier runs, with each run using a different pseudorandom state (from 0 up to the user-specified number -1).  I used from between 20 and 100 runs in my analyses; the final residual vegetation predictions were made using 100 runs.  Then, to view the prediction scores can be viewed using Github_AI_1_Make_Predictions.ipynb 
