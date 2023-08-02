
# CIFAR-10 Convolutional Neural Network (CNN) Classifier

This repository contains code and resources for training a Convolutional Neural Network (CNN) model on the CIFAR-10 dataset for image classification.

## Dataset Preparation

Before running the code, make sure to install the required libraries by running the following commands:

```shell
pip install tensorflow
pip install seaborn
```

The dataset is loaded from the CIFAR-10 dataset using TensorFlow's built-in function. The images are normalized to have pixel values in the range [0, 1], and the labels are one-hot encoded.

## Model Architecture and Training

A CNN model is designed using Keras. The model consists of convolutional layers with max-pooling, followed by fully connected layers. The model is compiled with the Adam optimizer and categorical cross-entropy loss function.



## Model Evaluation

The trained CNN model is evaluated on the testing set to measure its performance. Metrics such as accuracy, precision, recall, and F1-score are calculated and presented using a classification report. Additionally, a confusion matrix is plotted to visualize the performance.



## Overfit Analysis

To analyze overfitting, training and validation accuracy and loss curves are plotted. Regularization techniques like dropout or L1/L2 regularization can be applied if overfitting is observed.



## License

This project is licensed under the [MIT License](LICENSE).


