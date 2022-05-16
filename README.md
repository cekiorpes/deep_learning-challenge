# deep_learning-challenge

## Charity Funding Predictor
Using neural networks to predict whether applicants for charity funding will be successful

The data was preprocessed and columns with several unique values were given a cutoff point for "rare" categorical variables. The clean data was then one-hot encoded to ensure that only numeric values were present in the data. Tenserflow Keras was then used to create the neural network model, which was compiled, trained, run, and evaluated for loss and accuracy. The model was then optimized with the goal of achieving a target predictive accuracy of 75% or higher. This was done by changing the values of data in bins in preprocessing, varying the number of layers in the model, as well as the number of nodes in each layer. Three attempts were made to achieve the target predictive accuracy - none of these attempts was able to achieve an accuracy of over 73%. 
