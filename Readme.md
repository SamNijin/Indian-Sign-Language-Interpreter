#

<center> <h1 style='font-size:45px; text-align:center; font-weight:900'>Indian Sign Language Classification using Transfer Learning</h1> </center>

#

![Indian Sign Language](https://vajiramandravi.s3.us-east-1.amazonaws.com/media/2019/2/28/16/52/7/isl.jpg)

#####

# Introduction

- The basic requirement of the peoples are the communication which allows everyone to share their thoughts and emotion with some other persons, without communication we all will be stressed out and it is really a tough situation to live.
- There exists two main languages as **Speech Language** and **Sign Language**. The speech language is for the peoples who can talk and hear the voices around them whereas the sign language is for the people who can't hear or speak.
- Due to this reason there will be a communication barrier between the sign language peoples and the normal leanguage people as the learning of sign language is really a hard work to do with.
- The main objective of this project is to provide an efficient way to build a model which is to be used to interprets the sign language into speech language.
- This model is build on the **Xception architecture** which is better than the VGG-16, ResNet-152, Inception V3 models.

# Objective

- To train CNN model which is capable of classifying the alpha numeric hand gestures of Indian Sign Language.
- To improve the accuracy by using transfer learning technique.

# Reason for the project

**Sign language is one of the toughest language compared to the speech language so it isnot possible to learn this, so to overcome this situation a modern technical solution is required this problem. And this application is required for:**

- **Promotion:** This interpreter equal access to information, services, and opportunities to the sign language people

- **Better Environment:** Fosters inclusivity and diversity for the sign language people so that they wont hesitate to comminicate with the other people.

- **Relationships:** This interpreter Strengthens relationships between deaf and hearing individuals and communities.

As the world continues to recognize the importance of sign language, it is essential to continue promoting and supporting its use and growth. By utilizing this application, we can create a more inclusive and accessible society for all the people including the sign language and the speech language people.

# Libraries required to run this notebook

- tensorflow
- keras
- sklearn
- matplotlib
- seaborn
- PIL
- pandas
- numpy
- cv2
- random
- os

## Follow the command to install the above libraries

#### tensorflow

- pip install tensorflow

#### keras

- pip install keras

#### sklearn

- pip install scikit-learn

#### pandas

- pip install pandas

#### numpy

- Numpu will come along with tensorflow if it doesn't install try checking the below command line to install numpy
- pip install numpy

#### cv2

- pip install opencv-python

<img src='https://raw.githubusercontent.com/SamNijin/Indian-Sign-Language-Interpreter/master/Accuracy%20vs%20Loss%20Plot.png'/>

## Summary of the above plot

- Around epochs 4 there is huge change of loss and accuracy.
- After 5th epochs the accuracy and loss are likely to have a less diversion.

# Conclusion

- The model gives **100% accuracy and 100% precision** in the **test data.** Where the **classes 6, 7, E, R** has a **precision of 99%**
- This Xception model with 3 layers of ANN or the fully connected layers results in best classification with a learning rate of 0.0001
- The model was saved to the local system which sized around 849 MB.
