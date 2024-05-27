# Multiclass classification model using a custom CNN in TensorFlow
> To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
- Melanoma is a type of cancer that can be deadly if not detected early.
- It accounts for 75% of skin cancer deaths.
- I have tried to provide a solution that can evaluate images and alert dermatologists about the presence of melanoma which has the potential to reduce a lot of manual effort needed in diagnosis.
- The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.
- The dataset can be downloaded from https://drive.google.com/file/d/1xLfSQUGDl8ezNNbUkpuHOYvSpTyxVhCs/view

## Technologies Used
- TensorFlow - version 2.16.1
- Pandas - version 2.2.2
- Matplotlib - version 3.9.0
- Numpy - version 1.26.4
- Glob - version 2.0.2
- Shutil - version 3.8


## Conclusions
- A simple CNN model with 3 numbers of Convolution + Max Pooling layers and 1 Dense layer plus one Softmax layer gives us a overfitting model.
- To overcome the above issue, data augmentation is necessary. It is observed that the overfitting issue has been resolved to some extent in the present model.
- Further, there is a need to overcome class imbalance issue in the training dataset.
- Class imbalance can be rectified using Augmentor library. After building a model using Augmentor library, it can be seen that there is no class imbalance and the issue of overfitting was resolved.


## Acknowledgements
- This project was inspired by Ramesh Sir
- This project was based on melanoma detection problem hosted on Kaggle website.


## Contact
Created by [@sandeepmilan] - feel free to contact me!
