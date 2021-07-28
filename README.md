# ML-312-Project
# Speech emotion detection using the RAVDESS dataset          

The weights saved which gave us an average accuracu of 79% is added and named 312weight.h5.                 
To run the model with pre trained weights you can load it in your file.           
  
# load wights and test
If you wish to test it with our data, locate and load the xtest.csv and ytest.csv files.
Next, use the following code to reshape the data so that the model can evaluate it.

% making data compatible for model evaluation.                     
x_test = np.expand_dims(x_test, axis=2)             
x_test.shape, y_test.shape              


this changes our test set shape to        
(1839, 168, 1), (1839, 8))        
from                    
(1839, 168), (1839, 8))             


If you wish to run our model you can use our ipnyb file. If our random seed is required use the xtrain.csv and xtest.csv files.             

That is all!            

Goodluck! Happy coding.             



