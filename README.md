# -LiveNet-face-liveness-detection-using-convolution-neural-network 
Abstract:
Performance of face liveness detection algorithms in cross-database face liveness detection tests is one of the key issues in face-biometric based systems. Recently, Convolution Neural Networks (CNN) classifiers have shown remarkable performance in intra-database face liveness detection tests.
In this report, we propose an efficient strategy for training deep CNN classifiers for face liveness detection task. 
In this project, we have to give an input image, we’ll train a Convolutional Neural Network capable of distinguishing real faces from fake/spoofed faces as shown in figure:

Introduction:
Biometric technology continues to advance, and many of us rely on biometric technologies like facial recognition on a daily basis. But as technology advances, it’s essential to realize that security risks are also advancing.
When technology moves forward, hackers become smarter and more innovative in the ways they steal identity information. They learn the new systems and how to work around them, meaning that despite more advanced biometric technologies on the market, companies using them still face risk today.
With security issues becoming more prevalent, security companies now have to up their game, too. They’re doing so by enhancing security features to improve security while also keeping technologies easy for customers to engage with. One of the more common capabilities is liveness detection for facial recognition. This detection however requires the end user to look into the phone and perform movements such as move left, move right, blink, or even zoom the phone in and out to prove liveness.

Problem Definition
Many cybercriminals attempt to achieve illegitimate access to another individual’s rights by using videos, photos, or other materials for the authorized person’s face. For example, if you use a bank that requires facial recognition technology to identify you when you log in, cybercriminals could use a photo or video of your face they find online and use it to fool, or ‘spoof,’ the facial recognition system so they have access. So in this project, our aim is to verify fake face during facial recognition using convolution neural network. 

 Objective  
It can be divided into three parts:
1. Extracting regions of interest (images) from videos (two videos – fake and real) that are provided by the user frame wise and storing them as two different training datasets.
2. Using these datasets to train a Convolutional Neural Network to identify whether the frames provided by the live video camera are real or fake based on the training it received (binary classification problem).
3. Starting a live video stream and analysing it frame wise with the help of the trained CNN.
Technology Used
In this project, we trained convolution neural network (CNN) (LivenessNet)
A convolutional neural network (CNN) is a type of artificial neural network used in image recognition and processing that is specifically designed to process pixel data. CNN is a neural network that has one or more convolutional layers and are used mainly for image processing, classification, segmentation and also for other auto correlated data.
Problems faced
We faced one problem, when we were running the code in google collab, we were not able to open camera to take video. After we took some help from internet and from TA and then we fixed it.

Datasets Used
We are using itself creating datasets (our liveness detection datasets )
Real and fake faces, this images create by two videos ->Real and fake mp4 videos 

Result And Performance 
 
Show the result -> obtain 100% liveness detection accuracy on our validation set with limited overfitting.

Conclusion And Further Work
This work provided an overview of different approaches of face liveness detection. It presented a categorization based on the type of techniques used and types of liveness indicator/clue used for face liveness detection which helps understanding different spoof attacks scenarios and their relation to the developed solutions. A review of most interesting approaches for liveness detection was presented.
Future attack datasets must consider attacks like 3D sculpture faces and improved texture information. Our main aim is to give a clear pathway for future development of more secured, user friendly and efficient approaches for face liveness detection.
