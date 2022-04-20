# Melanoma Cancer Detection
> The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- ## Problem statement:
To build a CNN based model which can accurately detect __melanoma__. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the __International Skin Imaging Collaboration (ISIC)__. All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- There are three custom models have been build in the notebook.
- We have created multiple models that solved the problems of overfitting/underfitting in the base models and our final model is able to predict 80% accureately in the validation dataset
- There is no pre-trained model have been used. The models are custom build.
- **Model 1:** First model shows a sign of Overfitting with high accuracy but low validation accuracy.
- **Model 2:** Second model shows a sign of Underfitting with low accuracy. It is possibly due to the data imbalanced.
- **Model 3:** Final model showing promising results with good accuracy and validation accuracy. Augmentor library have been used to increase the sample data since there was data imblanced.


## Technologies Used
- Numpy - v1.16.5
- Matplotlib - v3.3.2
- Sklearn - v0.21.3
- Statsmodel - v0.10.1
- Pandas - v0.25.1
- Seaborn - v0.9.0
- Tensor flow
- Augmentor-0.2.9



<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->


## Contact
Created by Kishore T- feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
