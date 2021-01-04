# BoneNeuralNetwork
Neural Network For CS401

A Neural Network I built for a Binary Classification problem in school, attaining a maximum 86 percent accuracy on validation set.

The file train-io.txt is a 300,000 * 13 data file, and the data is i.i.d..

The file test-in.txt is a 10,000 * 12 data file, there is no classification column, this column was held back for grading purposes. 

The network was trained on the first 2/3 of the training data.

Validation was carried out on the reminaing 1/3 of the training data.

The developed model was then used to make predictions on the test-in.txt set, the predictions were then printed out to a seperate file test-out.txt.
