# HOG-features
the Histograms of Oriented Gradients (HOG) feature for detecting human in 2D images
Compute the HOG descriptor for each of the training and test images.
Compute the mean descriptor for the positive training images and the mean descriptor for the negative training images. 
Next, compute the Euclidean distance from each positive sample to the mean descriptor of the positive samples, and compute the Euclidian distance from each negative sample to the mean descriptor of the negative samples.
Start with some arbitrary W value, use the Error-Correcting procedure you have learned in class to train a 2-class linear classifier that will classify an input HOG descriptor to human or non-human.
