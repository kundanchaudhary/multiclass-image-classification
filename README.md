# Multiclass Image Classification

## Description:
Image classification is an extremely important part of digital image analysis which has direct applications in powering self-driving cars, drones, and in boosting augmented reality. The drive in the field has been to achieve a near-perfect image classifier. Near-perfect multiclass image classification is challenging, but it is a vital step in enabling various applications which require automation of tasks and sending in objects (e.g., drones) remotely where it would be impossible for human beings to be.


## Objective:
In this project, we plan to showcase both binary and multiclass classifiers with accuracies >95%.

## Methodology:
Starting with image preprocessing, we use both classical models such as random forest, k-nearest neighbors, logistic regression, and XGBoost, and convolutional neural net to predict the test images. Initially, we perform the test on binary dataset and gradually improve the accuracy score by optimizing the model hyperparameters. Furthermore, we use data augmentation technique to increase the dataset size, and implement ensemble methods to achieve the best score possible. Taking my learnings from a simple binary classification model, we implement the methods on multiclass (6) dataset to explore the model performance.

## Results/Conclusions:
In this project, with optimal model hyperparameters, image augmentation, and ensemble methods, we show the path towards achieving near-perfect multiclass image classification. Here, an ensemble of models including random forest and k-nearest neighbors are used to calculate scores for different metrics. Based on the highest accuracy score, random forest model is used for predicting the labels on the test dataset. With image augmentation, the accuracy improved from 95% to 99% for the binary classification and from 69% to 96% for the case of multiclass classification.

## References:

[1] https://gogul.dev/software/image-classification-python

[2] https://www.datacamp.com/community/tutorials/k-nearest-neighbor-classification-scikit-learn

[3] https://becominghuman.ai/building-an-image-classifier-using-deep-learning-in-python-totally-from-a-beginners-perspective-be8dbaf22dd8

[4] https://github.com/manashpratim/Intel-image-Classification/blob/master/Intel_Image_Classification.ipynb
