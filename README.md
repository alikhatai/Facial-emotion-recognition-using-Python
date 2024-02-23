Facial emotion recognition using Python
Ali Khatai
Project Goals:
For my Project, I will be performing Facial expression Recognition using the FER2013 Dataset. Facial Emotion recognition software allows a computer to detect emotion in human faces. It is basically a sentiment analysis tool which has many use cases such as market research and video game testing where companies can use such a tool to detect a users response to their product. Such a means of collecting market data is non-intrusive to users and can also be more reliable as it is not asking for the users response, but is instead getting it directly. This also helps to automate and scale data collection efforts and analyse data faster.

In this Project, I will be focus on 3 things which are as follows:

Implementing a convolutional neural network for emotion recognition: Convolutional neural networks are a type of neural network used most commonly in images classification and processing. These type of networks use convolutional layers which allow the networks to learn certain features in input images. In my project I will be implementing convolutional neural networks with different architectures to determine which one would work best for my task.
Looking at the effects on basic data augmentation techniques on accuracy of the model: Data augmentation is the process of applying transformation to your data which might help separate it from the original data whilst still being relevant to our use case. Basically, neural networks need a large amount of data to train well on and with data augmentation we are able to increase the size of our dataset. I will be using some basic transformations to augment and increase the size of my dataset and train a model on it to see how useful and affective data-augmentation is for emotion recognition
Using transfer learning to analyze the effects of transfer learning and maximizing the accuracy of the model: Tranfer Learning is the use of a pre-trained model and its weights that was implemented for a similar problem. Here i will be looking at the effectiveness of tranfer learning and use it to maximize the accuracy.
Dataset:
The dataset I will be using is called FER2013 which is an open-source dataset which is first, created for an ongoing project by Pierre-Luc Carrier and Aaron Courville, then shared publicly for a Kaggle competition. the data set contains 35,887 grayscale, each sized 48 X 48 pixels consisting of close-up shots of face images. Each image is labelled by a corresponding emotion which are:

0 : Angry
1 : Disgust
2 : Fear
3 : Happy
4 : Sad
5 : Surprise
6 : Neutral
The dataset can be found here

We will start by processing our dataset, implement our model, and then experiment with data-augmentation and transfer learning.
