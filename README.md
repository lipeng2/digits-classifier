# digits-classifier
The project is a rapid development of CNN model for classifying hand written digits. The training data is obtained from the 
[Digit Recognizer](https://www.kaggle.com/c/digit-recognizer/discussion/27737) competition on kaggle.

## Overview

The model has 9 sequential convolutional layers and 5 full connected layers at the end. It is built by deploying keras API (TensorFlow backend). Steps of the projects as followed:

* prepare data (format, normalization, train/test split, augmentation)
* design model's architecture
* train model
* fine tune parameters
* evaluation on the trained model

### Discussion
More details about the dataset, including algorithms that have been experimented on it and their levels of success, can be found at [here](http://yann.lecun.com/exdb/mnist/index.html).
Additionally, The best published result is [here](https://arxiv.org/pdf/1202.2745.pdf)
