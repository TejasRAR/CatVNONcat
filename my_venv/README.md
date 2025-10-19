I have used L2 normalization to prevent overfitting due to high variance and
I have used HE initialisation to initialise weights as RELU is being used in the hidden layers

Overfitting is a condition where the training accuracy is high but the testing accuracy is low.
This happens due to a condition where the bias of the model is low but the variance is high and the model is not learning features
anymore but rather memorizing the patterns of the training dataset which is why it performs poorly on the test set.

One of the solutions (one of the solutions from Changing architecture/Training the model ) for overfitting is to use regualarization techniques which impose a "penalty" on the weights
if they are too large and downsizes them, this prevents the model from "memorizing" the data and encourages the model
to "learn the features".

The other solutions are

1.  Changing architecture of the model
2.  Training the model on more data using techniques like data augmentation
3.  Early stopping, where we stop the model when we deduce that it is not learning features
    but rather memorizing them

TO-DO

1.Implement Dropout regularization and Early stopping to attain 80% + accuracy in Test data
2.Learn and Use Git to control versions of the code
3.Go through the base code again
4.Watch at least 1-2 lecture videos

(Optional) Check GPU utilisation
