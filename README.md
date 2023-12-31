# Training-a-CNN

Business Problem: Improving Image Classification Accuracy Using CNN on CIFAR-10 Dataset

Description:
The business problem is to develop a Convolutional Neural Network (CNN) model to improve image classification accuracy on the CIFAR-10 dataset. The CIFAR-10 dataset consists of 60,000 32x32 color images divided into 10 classes, with 6,000 images per class. The dataset is split into 50,000 training images and 10,000 test images. The goal is to create a solution using TensorFlow.

Tasks:

- Dataset Exploration and Visualization: Load the CIFAR-10 dataset and examine the images to understand their characteristics and content.
- CNN Model Training: Design and train a CNN model with three hidden convolutional layers. The first layer should use 64 11x11 filters followed by 2x2 max pooling with a stride of 2. The next two convolutional layers should use 128 3x3 filters, all activated by the Rectified Linear Unit (ReLU) function. Include an average pooling layer before the softmax layer, pooling across the preceding feature map. The model should be trained using all the training data and evaluated on the test data. Plot the training loss as a function of epochs and determine the accuracy on the test data. Discuss the architecture and hyperparameters used in the model, including weight initialization.
- Filter Visualization: Visualize the learned 11x11x3 filters from the first convolutional layer as an RGB image array. Create a large RGB image composed of smaller images, arranging them in a 4-row and 16-column grid. Normalize each filter by performing contrast stretching. This involves subtracting the smallest value from each filter and dividing it by the new largest value.
- Batch Normalization Integration: Enhance the existing CNN architecture by adding batch normalization between each of the hidden layers. Compare the training loss with and without batch normalization across epochs. Calculate the final test error. Additionally, visualize the filters after batch normalization.
