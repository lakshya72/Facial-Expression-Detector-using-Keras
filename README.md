# Facial-Expression-Detector-using-Keras
In this project, I built and trained a convolutional neural network (CNN) in Keras from scratch to recognize facial expressions. 
Dataset used is the 2013 Facial Emotion Recognition Dataset. The dataset consists of 48x48 pixel grayscale images of faces. 
The objective is to classify each face based on the emotion shown in the facial expression into one of seven categories (0=Angry, 1=Disgust, 2=Fear, 3=Happy, 4=Sad, 5=Surprise, 6=Neutral). 
I used OpenCV to automatically detect faces in images and draw bounding boxes around them. 
Once the model has been trained, saved, and exported the CNN, I use the trained model to a web interface and perform real-time facial expression recognition on video and image data. 
The video input can be changed to take in webcam by changing one line of code.
