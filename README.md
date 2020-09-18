# Intel_multiclass_image_classification
  Data science project using Deep learning for image classification.
## Overview
Built a classifier to classify an image into 6 categories ->(buildings, sea, forest, mountain, glacier, street).
The classifier is built using a Convolution neural network. The architecture used is a modified version of AlexNet.

I got an accuracy of 86% on the test set after iterating and tuning on different architectures. 


![Accuracy](https://github.com/siddarth99/Intel_multiclass_image_classification/blob/master/Screenshot%20(81).png)

## Data
This Data contains around 25k images distributed under 6 categories.

{'buildings' -> 0,
'forest' -> 1,
'glacier' -> 2,
'mountain' -> 3,
'sea' -> 4,
'street' -> 5 }

[Download the data here](https://www.kaggle.com/puneet6060/intel-image-classification)

## Prediction example

![Predicion](https://github.com/siddarth99/Intel_multiclass_image_classification/blob/master/Screenshot%20(83).png)

## Config
This model was trained on a Google Colab GPU runtime which took around 6 seconds per epoch. I recommend using this config as training this on an average computer can take around 
10-15 minutes per epoch.
