# Digit-Recognizer
This is model developed to detect Hand written digits from the MNIST data.

This model is developed in python using Tensorflow, Keras, Numpy and pandas. It is a basic implementation of a standard CN network with very few layers.
There are several versions of the model. The latest one gives 97% accuracy in kaggle . However som of the previous verrsions gave 99.35% accuacy. All the versions have the follwing strucure:

Conv2D()

Conv2D()
Maxpooling()

Conv2D()
Maxpooling()

Conv2D()
Maxpooling()

Dense()           The number of dense layers for the best  model was 3 (256 -> 128 - > 10)
Dense()
Dense()
Dense()

THe above model was trained on the MNIST hand digit data. 
