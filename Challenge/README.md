# Nonprofit Networking Challenge
In this challenge a sequential keras deep learning model was built to assist Alphabet Soup, a nonprofit foundation, in determining what 
projects are likely to be successfuland should receive future funding from the foundation.

The current model has 3 hidden layers with 10 neurons in the first layer, 7 neurons in the second layer, and 3 neurons in the third layer. 
Different variations of the model were tested going as high as 5 hidden layers with 30 neurons in 1 layer. However, the different amount of layers did not affect the 
accuracy to go above 72%. The current combination of hidden layers and neurons gave an accuraccy score of 72.5% which is one of the higher 
scores that were tested. 

Unfortunately, the target model performance was not achieved. Steps that were taken to try to improve the models performance included 
testing different hidden layer and neuron combinations as well as testing different activation functions. The Leaky ReLU function seemed 
promising as the scaled input data included a good amount of negative values, however it did not improve the accuracy score in the end. 
Furthermore, the data itself was taken another look at and certain arbitrary columns such as name and ID were removed.

In the future, I would implement a Support Vector Machine Model to see if it has comaprable results to this model. Since the output data is 
binary, trying to classify groups into succesful or not, I believe SVM could have an advantage. The data had a lot of features and SVM has 
the ability to create multidimensional borders which can prove to be useful when classifying this type of data.



