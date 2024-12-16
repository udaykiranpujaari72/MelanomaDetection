# Melanoma Detection Using Deep Learning
> This project aims to develop a deep learning model to detect melanoma from skin lesion images. The model uses Convolutional Neural Networks (CNNs) with Batch Normalization and Dropout to improve accuracy and generalization.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)
* [Contact](#contact)

## General Information
- **Background:** Melanoma is a serious form of skin cancer that can be fatal if not detected early. Early detection can save lives, making it crucial to have an automated tool for detection.
- **Business Problem:** This project aims to automate the detection of melanoma, providing a tool that could assist medical professionals in diagnosing skin lesions more accurately and efficiently.
- **Dataset:** The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

## Conclusions
- **Model Performance:** The model demonstrated an improvement in accuracy over the epochs, achieving an accuracy of 92.57% at the end of 30 epochs. The validation accuracy reached 84.41%, showing good generalization performance.
- **Overfitting Control:** The use of Batch Normalization helped mitigate overfitting, maintaining a balance between training and validation performance.
- **Final Results:** The model showed high accuracy in classifying skin lesions, with the final validation accuracy being 84.41%. This indicates that the model is capable of making reliable predictions on unseen data.

## Technologies Used
- TensorFlow - 2.12.0
- Keras - 2.12.0
- Python - 3.8
- Matplotlib - 3.7.1
- NumPy - 1.23.4

## Acknowledgements
- This project was inspired by research on using deep learning for melanoma detection in medical imaging.
- The dataset used is publicly available from [The ISIC Archive](https://www.isic-archive.com/).
- Special thanks to TensorFlow and Keras for their powerful tools for building deep learning models.

## Contact
Created by [https://github.com/udaykiranpujaari72] - feel free to contact me!
