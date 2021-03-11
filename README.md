# Facial-expression-recog
# Dataset:
The dataset used for this project is Facial Expression Recog Image Ver of (FERC)Dataset from Kaggle, which is a modified dataset of the original FERC dataset and contains .jpg images of the original dataset which contains images in the form of pixels in string format.
The dataset has two directories train and test and label.txt file. Both the train and test datasets contains 7 classes anger, disgust, fear, happiness, neutral, sadness and surprise.
The images have a resolution of 48*48 pixels. The entire file size of the dataset is 65.54 MB with 35.9k different image samples. It has a usability of 7.5 and is good dataset for beginners making deep learning models for classification problems.
Dataset link:
https://www.kaggle.com/manishshah120/facial-expression-recog-image-ver-of-fercdataset
# The model:
This is a deep learning model which solves a classification problem with respect to the above dataset. It is written in python and uses three different python modules: tensorflow, matplotlib.pyplot and numpy. 
# Model architecture:
Convolutional layer 1 (32,3*3)🡪Pooling layer (2*2)🡪 Convolutional layer 2 (64,3*3)🡪Pooling layer (2*2)🡪 Convolutional layer 3 (32,3*3)🡪
🡪Dense layer/hidden layer (32)🡪 Dense layer/hidden layer (64)🡪 Output layer 
The model gives an accuracy of 57% on the train dataset with a validation accuracy of 
Approach used to increase accuracy: Data augmentation with horizontal and vertical flipping
![image](https://user-images.githubusercontent.com/77062490/110834122-28392780-82c3-11eb-94b2-a18efa9798ba.png)

# Loss vs Val_loss graph
![image](https://user-images.githubusercontent.com/77062490/110833433-6eda5200-82c2-11eb-965c-ee208a79e8c2.png)
