# Team:
@Muhammad Saad Uddin, @Khalid Waleed, @Abdul Basit, @Himanshu Madan, @Muhammad.Ali

# Social Distancing Detection
In the fight against the coronavirus, social distancing has proven to be a very effective measure to slow down the spread of the disease. Few months ago millions of people are staying at home to help flatten the curve but they are doing their jobs to earn and fulfilling their needs. As vaccine for Covid-19 has not been produced yet so best way to fight against Covid-19 is to wear masks and ensure social distancing.
Social distancing is a method used to control the spread of contagious diseases. Social distancing implies that people should physically distance themselves from one another, reducing close contact, and thereby reducing the spread of a Covid-19.

To help ensure social distancing, we have developed an AI-enabled social distancing detection tool that can detect if people are keeping a safe distance from each other by analyzing real time video streams from the camera.

Our approach consists of three steps:
* Detect the humans in the frame
* Calculate the distance between all the instances of humans detected in the frame.
* Show number of social distancing violations on the screen

## Requirements
Libraries and that are required to build social distancing detector are:
* Numpy
* OpenCV
* Scipy

> We are using YOLO object detector to detect people in video stream or camera video stream

## Main Project Files
### detection.py
This Python script consists of a single function definition for detecting people by drawing bounding boxes around them with respect to threshold we specified to it

### social_distance_detector.py
This python script is our social distancing detector. We have used YOLO object detector by Using OpenCV’s DNN module. We used eucledian distance between person detection and using detection.py, draw the total number of social distancing violations on the output frame

## Input Image from Video Streaming
![Input Stream Image](https://github.com/khalidw/social_distancing/blob/master/input.jpg)

## Output Image from Video Streaming
![Output Stream Image](https://github.com/khalidw/social_distancing/blob/master/output.jpg)

## Benefits of Social Distancing Detector
* Live video surveillance to fight against covid-19 spread
* The project can be integrated with embedded systems for application in airports, railway stations, offices, schools, and public places to ensure that public safety guidelines are followed.
* Real time social distancing tracking the crowd movement across the day time.
* Hot-spot area can be monitored by security forces from central station.
* If AI based solution used by authority then there will be less chance get infected security forces.
