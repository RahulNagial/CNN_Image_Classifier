# CNN_Image_Classifier
## Flower Image Classifier: Project Overview

* Used TensorFlow and Keras to build a convolutional neural network (CNN) architecture that predicts flower species out of 17 possible classes. 
* Leveraged transfer learning on pre-trained VGG16 model to speed up model fitting and increase its accuracy. 
* Incorporated data augmentation techniques (such as zoom, horizontal flip, rotation) on raw images to increase number of training examples and thus prevent overfitting during model fitting. 
* Achieved ~85% accuracy on validation images with 64 training images per class.

For the image dataset used in this analysis refer: https://www.robots.ox.ac.uk/~vgg/data/flowers/17/. 

Note: I used Kaggle enviornment to gain GPU access to build the image classifier. 
