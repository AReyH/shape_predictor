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
- A 6 filter 3x3 2D Convolutional Layer alongside a MaxPool Layer.
- A 16 filter 3x3 2D Convolutional Layer alongside a MaxPool Layer.
- A Fully Connected Layer
- A Fully Connected Layer
- A Softmax Activation Layer

This six layer Neural Network has Dropout implemented to it. This was done in order to reduce overfitting.

![alt text](https://github.com/AReyH/shape_predictor/blob/main/NN_Architecture.png 'Neural Network')

## Results
The model was trained on 100 epochs without Early Stopping.

The image below shoes the accuracy for the training set (blue line) and for the validation set (orange line) throughout 100 epochs.
![alt text](https://github.com/AReyH/shape_predictor/blob/main/images/model_accuracy.png)

The image below shoes the loss for the training set (blue line) and for the validation set (orange line) throughout 100 epochs.
![alt text](https://github.com/AReyH/shape_predictor/blob/main/images/model_loss.png)

![alt text](https://github.com/AReyH/shape_predictor/blob/main/images/model_cm.png)
