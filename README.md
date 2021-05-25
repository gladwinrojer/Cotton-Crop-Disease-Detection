# Cotton-Plant-Disease-Prediction

   Given an image of the cotton plant leaf, we will be able to detect the
kind of disease the cotton plant has been affected by. I have gathered hundreds
of cotton plant images and trained the deep learning model to predict the
kind of disease the plant is affected by. I have also deployed the model
into a web application using Flask through which the farmer can simply
upload the leaf image and with a single click, the application will tell the
kind of disease and various methods for the cure.

   The dataset consists of cotton plant leaf images. The dataset is divided into
three class labels namely healthy plant, unhealthy plant, unhealthy plant with burnt
leaf. The images from the dataset is pre-processed and the active contours around
the plants are captured. Once the features are extracted , the image is passed into
Convolutional Neural Network. The CNN model is trained in order to classify the
infected plant and the leaf from the image.
The last layer of the CNN model contains three output units for classification.
The accuracy of the model is tested and the best fit model is taken for deploying in
the web application.

   The model is implemented into a web application using Flask, where the
infected plant parts are identified and the precaution measures are displayed in the
webpage.
