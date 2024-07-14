# Emotion Detection Model


## Project Overview

This project focuses on developing an emotion detection model using TensorFlow and Keras. The primary goal is to create a robust neural network that can classify human emotions based on facial expressions into seven categories: happy, sad, fear, angry, surprise, disgust, and neutral.


## Training and Evaluation

Training and Evaluation
The emotion detection model was trained using a dataset of approximately 2900 images, split into training, validation, and test sets with the following proportions:

Training Set: 80% (about 2320 images),
Validation Set: 10% (about 290 images),
Test Set: 10% (about 290 images)

## Evaluation Metrics
Training Accuracy: 97.78%

Validation Accuracy: 82.50%


## Contributing

I contributed to building the model using a pre-trained VGG (pVGG) model and employed various techniques to improve accuracy, including:

Data Augmentation: Applied techniques such as random flipping and rotation to increase the robustness of the model.

Dropout Layering: Included dropout layers to prevent overfitting by randomly dropping neurons during training.

Convolutional Neural Networks (CNN): Used multiple convolutional layers to capture spatial hierarchies in the input images.
The model was trained for 50 epochs with a batch size of 60, using the Adam optimizer and sparse categorical crossentropy loss function.



# Emotion_Detection_CNN

Data Set Link - https://www.kaggle.com/jonathanoheix/face-expression-recognition-dataset
