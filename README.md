This project builds an AI system that can identify food items from images and estimate their calorie content, helping users track their dietary intake and make healthier food choices. The model is trained on the Food-101 dataset, which contains 101 food categories and 101,000 images.


--->Project Overview

Modern lifestyle apps require automated nutrition tracking. Manually entering food details can be time-consuming and inaccurate.
This project solves that problem by:

Recognizing food objects from images

Predicting their calorie values

Providing quick, AI-powered dietary insights


The system uses a Convolutional Neural Network (CNN) or Transfer Learning (EfficientNet / ResNet50) for high accuracy.

This project builds an AI system that can identify food items from images and estimate their calorie content, helping users track their dietary intake and make healthier food choices. The model is trained on the Food-101 dataset, which contains 101 food categories and 101,000 images.


---> Model Architecture

Two approaches are implemented:

1. Transfer Learning

EfficientNetB0 / ResNet50

Image size: 224×224

Final layers replaced for classification (101 classes)


2. Custom CNN

4 convolution blocks

BatchNormalization + Dropout

Dense softmax output

--> Training Procedure

Data preprocessing

Image augmentation (flip, rotation, zoom)

Model training (20–30 epochs)

Categorical cross-entropy loss

Adam optimizer

Validation accuracy monitoring
