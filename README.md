# Speech Recognition Using CNN and FSDD

## Project Description
This project implements a convolutional neural network (CNN) to recognize spoken digits using the Free Spoken Digit Dataset (FSDD). The dataset includes recordings of spoken digits in WAV files, making it a suitable choice for developing and testing speech recognition models.

## Dataset
The FSDD is a simple audio/speech dataset that includes recordings of spoken digits in English, trimmed to minimal silence. It features:
- 6 speakers
- 3,000 recordings (50 of each digit per speaker)

## Dependencies
To run this notebook, you will need the following packages:
- hub
- numpy
- sklearn
- matplotlib
- tensorflow

Install these packages using pip:
```bash
pip install hub numpy sklearn matplotlib tensorflow
```

## Usage
1. **Data Preprocessing**: Load the dataset and split it into training, validation, and testing sets.
2. **Build and Train the Model**: Run the notebook cells to build the CNN model and train it using the training data.
3. **Evaluate the Model**: Assess the model's performance on the test dataset using accuracy metrics and a confusion matrix.
4. **Predictions**: Use the trained model to make predictions on new data.

## Model Details
The CNN model consists of several convolutional and pooling layers, followed by dense layers for classification. Training details, including the number of epochs and optimizer, are documented in the notebook.

## Results
The notebook includes visualizations of model accuracy and loss, as well as a confusion matrix and classification report for a comprehensive evaluation.

## Save and Load the Model
The trained model is saved as `Speech Recognition.h5`. It can be loaded using TensorFlow/Keras for further use or deployment.
