# Melanoma Detection Assignment

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
- This project is done as part of Melanoma Detection assignment.
- Background of project:

Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

Goal is to To build a custom (Without transfer learning )CNN based model which can accurately detect melanoma.

Dataset: The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

The data set contains the following diseases:
- Actinic keratosis
- Basal cell carcinoma
- Dermatofibroma
- Melanoma
- Nevus
- Pigmented benign keratosis
- Seborrheic keratosis
- Squamous cell carcinoma
- Vascular lesion

## Conclusions
- Base model was built without Batch normalization and dropouts. Difference between train and validation accuracy was very high. This model was overfitting.
- Then we observed high class imbalance in the Model, as the cause of overfitting. Augmentation strategy was used to rectify the problem. And second model was built with dropout layer. Training accuracy was not good but overfitting problem has been rectified with this model.
- We used the augmentor to generate balanced train data for all classes.
- Class imbalance problem was rectified and third model was built.
- Third model has Train accuracy 94% and Validation accuracy 83%. This can be used as final model.

## Technologies/Libraries Used
Python, Pandas, Numpy, Matplotlib, PathLib, TensorFlow, Keras, Glob, Augmentor

## Acknowledgements

- This project was inspired by Upgrad's Master of science in Machine Learning and Artificial Intelligence course.
I thank to faculty members from IIITB and support team of Upgrad.

- This project was based on CNN - Convolution Neural Network.


## Contact
Created by [@shraddhabhoir] - feel free to contact me!
https://github.com/shraddhabhoir



