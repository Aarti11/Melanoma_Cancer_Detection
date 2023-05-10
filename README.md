# Melanoma Skin Cancer Detection with Convolutional Neural Network
> The purpose of this project is to build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.


## Table of Contents
* [General Info](#general-information)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
- The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.
- The data set contains the following diseases:
Actinic keratosis
Basal cell carcinoma
Dermatofibroma
Melanoma
Nevus
Pigmented benign keratosis
Seborrheic keratosis
Squamous cell carcinoma
Vascular lesion

## Conclusions
- There is no pre-trained model have been used. The models are custom build.
- Batch Size 32 have been used and images have been resized to 180 x 180.
- There are three custom models have been build in the notebook.
- Model 1: First model shows a sign of Overfitting with high accuracy but low validation accuracy.
- Model 2: Second model shows a sign of Underfitting with low accuracy. It is possibly due to the data imbalanced.
- Model 3: Final model showing promising results with good accuracy and validation accuracy. Augmentor library have been used to increase the sample data since there was data imblanced.

## Acknowledgements
I would like to thank Upgrad and IIIT Bangalore for giving me a chance to work on this project.


## Contact
Created by Arti Saraswat (Aarti11) - feel free to contact me!
