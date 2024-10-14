A code developed in Python is used for the classification of MRI images from a dataset sourced from OASIS obtained from Kaggle (https://www.kaggle.com/datasets/ninadaithal/imagesoasis). 
For classification, a CNN is constructed using keras, which has also been used in Kaggle code for this dataset (see link).

## Classification

- First, the images are processed to have a single black-and-white channel.

Two approaches are followed: 

- **In the first approximation**, for both binary and multiclass classification, the number of images from the class with the lowest number of images will be selected.
- **In the second approximation**, for multiclass classification, oversampling will be performed using SMOTE.
