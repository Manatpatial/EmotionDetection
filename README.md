# Emotion Detection with CNN

This project implements a Convolutional Neural Network (CNN) for emotion detection. It utilizes a dataset of facial images to classify the emotions depicted in the images.

## Installation

Clone the repository: 
``` git clone https://github.com/Manatpatial/EmotionDetection.git ```

### Install the required Packages
- pip install numpy
- pip install opencv-python
- pip install keras
- pip3 install --upgrade tensorflow
- pip install pillow



## File Structure

The project has the following structure:
```
├── train.py
├── test.py
└── model/
    ├── model.json
    └── model.h5
```
- `train.py`: Python script for training the CNN model on the provided dataset.
- `test.py`: Python script for evaluating the trained model on test data or for making predictions.
- `model/`: Directory containing the trained model's architecture (`model.json`) and weights (`model.h5`).

## Usage

1. **Training the Model**: Execute `train.py` to train the CNN model using the provided dataset. Adjust parameters such as batch size, epochs, and learning rate as needed.
### run your emotion detection train file
python train.py

2. **Testing the Model**: Run `test.py` to evaluate the trained model's performance on test data or make predictions on new images.
### run your emotion detection test file
python test.py

## download FER2013 dataset
- https://www.kaggle.com/msambare/fer2013
```
data/
    ├── test
    └── train
```



