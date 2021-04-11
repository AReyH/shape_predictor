# Shape Predictor: Project Overview
- Processed images of shapes: Triangles, Squares, Stars, and Circles.
- Downloaded dataset from [Kaggle](https://www.kaggle.com/smeschke/four-shapes).
- Trained custom Neural Network using the Keras API in order to classify between four different shapes.
- Obtained 99.95% accuracy on training set, and 100% on test set.

## Code used
- **Python Version:** 3.7.10
- **Packages:** Numpy, Pandas, Pathlib, Sklearn, Keras, Matplotlib, Seaborn.

## Neural Network
The Neural Netowork consists of 6 layers:
- A 6 filter 3x3 2D Convolutional Layer alongside a MaxPool.
- A 16 filter 3x3 2D Convolutional Layer alongside a MaxPool.
- A Fully Connected Layer
- A Fully Connected Layer
- A Softmax Activation Layer

This six layer Neural Network has Dropout implemented to it. This was done in order to reduce overfitting.

![alt text](https://github.com/AReyH/shape_predictor/blob/main/NN_Architecture.png 'Neural Network')

## Results
