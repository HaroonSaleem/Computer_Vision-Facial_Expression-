# Computer_Vision-Facial_Expression.

*Emotion Recognition Using CNN**

This repository contains code for training a convolutional neural network (CNN) to classify human emotions from facial expressions. The dataset used for training is the FER2013 dataset, which contains 28,708 images of faces with seven different emotion labels (Angry, Disgust, Fear, Happy, Sad, Surprise, Neutral).

The CNN model used in this repository is a simple 4-layer network with two convolutional layers, two max pooling layers, and two fully connected layers. The model is trained using the Adam optimizer   
 and the categorical crossentropy loss function. The accuracy on the test set is 60.2%.

**How to Use This Code**

1. Clone this repository.
2. Install the dependencies using `pip install requirements.txt`.
3. Download the FER2013 dataset from [https://github.com/cfp/FER2013](https://github.com/cfp/FER2013).
4. Extract the FER2013 dataset into the `data` directory.
5. Run the `train.py` script.
6. The model will be trained and saved to `model.h5`.
7. The accuracy on the test set will be printed to the console.

**Dependencies**

* numpy
* tensorflow
* matplotlib

**License**

This code is licensed under the MIT License.

**Acknowledgements**

This code is based on the tutorial "How to Build a CNN for Image Classification in Python" by PyImageSearch.com.
