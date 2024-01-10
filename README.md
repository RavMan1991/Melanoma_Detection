# Project Name
> A CNN based model which can accurately detect melanoma. Melanoma is a type of skin cancer that can be deadly if not detected early & accounts for 75% of skin cancer deaths.
> A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- We build CNN architecture which can classify Cancerous Images.
- We experiment starting with a simple model.
- We then perform image transformation to improve upon the base model.
- We identify and rectify class imbalance to make more robust

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- We experiment with multiple architecture setups in terms of convolution layer and Dropouts.
- Base model without any image transformation shows overfitting (Training Accuracy - 78% and Validation Accuracy 55%).
- We augment the training images with transformations and try to fit the base model on this. The models overcomes the overfitting problem but shows signs of underfitting.
- We identify the Training Dataset is skewed/imbalance and Augment the training the dataset with synthetically generated images.
- The model built on this Augmented Dataset performs well with no signs of overfitting/underfitting.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- CNN Architecture
- Augmentor
- Tensorflow
- matplotlib
- numpy
- pandas

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- This project was in contribution to Melanoma Detection Assignment by Upgrad.


## Contact
Created by [@RavMan1991] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
