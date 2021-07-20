# BirdSpecies-Prediction

You can find the dataset from the https://www.kaggle.com/gpiosenka/100-bird-species

I sincierly thank Gerry for making this dataset public.

I have used Keras library to read, train, test, and predict the data.

The dataset consists of 38518 train images belongs to 270 classes and 1350 test images belongs to 270 classes.

Since it's a huge dataset with large variety of images i.e., 270 it's a good idea to implement transfer learning techniques rather than building a model from scratch. So, I have applied varies transfer learning algorithms available in Keras and noticed that Inception v3 performs great.

Used ADAM optimizer and accuracy as the evaluation metrics and 20 epochs to train the model.

**Results are amazing we got training accuracy of 97% and testing accuracy of 94.3%. This shows that although our model is performing execptionally well on training set it is not overfitted.**
