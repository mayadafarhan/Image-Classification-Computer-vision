Project Description

A computer vision project that performs image classification using deep learning and transfer learning. The project classifies images into six categories by using the pre-trained VGG16 convolutional neural network, trained on the ImageNet dataset, as a feature extractor.

The Intel Image Classification dataset was used, consisting of 14,034 training images and 3,000 test images. Images are loaded and resized to 224×224 pixels using Keras ImageDataGenerator. The VGG16 convolutional layers are frozen to retain their learned features, while a custom classification head with Flatten and fully connected Dense layers is added.

The model was implemented in Python using TensorFlow and Keras, with NumPy for numerical operations. It was compiled using the Adam optimizer and categorical cross-entropy loss and trained to generate probability-based predictions through a six-class Softmax output layer.
