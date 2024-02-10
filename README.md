# CNN Image Classifier - Sentience Model #
## Overview ##
The Sentience Model is a Convolutional Neural Network (CNN) image classifier implemented in Python using TensorFlow. The primary objective of this project is to predict the emotional state of a person or group of people, classifying them as either happy or sad based on input images.
## Key Features ##
* **Model Architecture**: The CNN architecture comprises three convolutional layers with max-pooling followed by a fully connected layer and an output layer. The model has a total of 3,696,625 parameters.

* **Data Pipeline**: The project includes a comprehensive data pipeline, covering dependency installation, data cleanup, loading, scaling, and partitioning for training, validation, and testing.

* **Training and Evaluation**: The model is trained over 20 epochs, achieving 100% accuracy on both training and validation sets. Performance metrics such as loss, accuracy, precision, recall, and binary accuracy are evaluated and visualized.

* **Testing**: A testing phase involves predicting emotions on new data, showcasing the model's ability to generalize and make accurate predictions.

* **Model Saving**: The trained model is saved in the Hierarchical Data Format (H5), ensuring easy deployment and reuse.
## Model Accuracy and Loss ##
![download-1](https://github.com/aaditya79/CNN-Image-Classifier/assets/71707744/0b3c9c22-b626-4667-aebe-ec45c6c04a56)
![download](https://github.com/aaditya79/CNN-Image-Classifier/assets/71707744/cb4c096e-646a-4be2-9331-602c7f235e26)
### Epoch 20/20: loss: 0.0252, accuracy: 1.0000, val_loss: 0.0169, val_accuracy: 1.0000 ###
## Validation Image Test ##
### Output: Prediction is Happy ###
![download-2](https://github.com/aaditya79/CNN-Image-Classifier/assets/71707744/c9ebc3b6-6f18-40e7-9a7d-74f314959745)
### Output: Prediction is Sad ###
![download-3](https://github.com/aaditya79/CNN-Image-Classifier/assets/71707744/d67ce0cc-aee6-4133-b14a-65a7b729fb83)

