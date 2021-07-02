# FER2013 
[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)



Kaggle Challenge - https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge/data

Facial Emotion Recognition on FER2013 Dataset Using a Convolutional Neural Network. 

80-10-10 ratio for training-validation-test sets.

Winner - 71.161% accuracy

This Model -  66.369% accuracy

![emotions](https://user-images.githubusercontent.com/28602282/48102098-ab737b80-e1e6-11e8-8541-517de2be0064.png)

## Getting Started

These instructions will get this model up and running. Follow them to make use of the `fertestcusstom.py` file to recognize facial emotions using custom images. This model can also be used as facial emotion recognition part of projects with broader applications

### Prerequisites
Install these prerequisites before proceeding-
```
 pip3 install tensorflow
 pip3 install keras
 pip3 install numpy
 pip3 install sklearn
 pip3 install pandas
 pip3 install opencv-python
```

### Method : Using the built model 

If you don't want to train the classifier from scratch, you can make the use of `fertestcustom.py` directly as the the repository already has `fer.json` (trained model) and `fer.h5` (parameters) which can be used to predict emotion on any test image present in the folder. You can modify `fertestcustom.py` according to your requirements and use it to predict fatial emotion in any use case.



## Running the tests (Optional)

You can test the accuracy of trained classifier using `modXtest.npy` and `modytest.npy` by running `fertest.py` file. This would give youy the accuracy in % of the recently trained classifier.

## Getting the Confusion Matrix (Optional)

You can get the confusion matrix for this model by running `confmatrix.py` file. This would evaluate the most confused expressions and generate a `confusionmatrix.png` file for your trained model, which would look something like this.

![confusionmatrix](https://user-images.githubusercontent.com/28602282/47956084-d8186080-df64-11e8-9d07-c7eda5cf6697.png)

# Model Summary

The layers in the Convolution Neural Network used in implementing this classifier can be summarized as follows. You can git a similar summary by decommenting the `model.summar()` function before executing `fertrain.py` file.
